# Análise: erros, padrões e eficiência na entrega do desafio MAPS (Minerva Finanças)

**Autor:** Claude (sessão orquestradora), a pedido do usuário

**Data da análise:** 2026-09-03

**Baseline:** aplicação consumidora `minerva-financas` (fork operacional deste template), PR #1
mergeado em `main` no commit `7c772c7`, cobrindo os níveis 1-3 do desafio técnico MAPS com as
opções A (multi-usuário) e B (consulta assíncrona de alto volume).

## Escopo e método

Esta análise cobre uma única sessão longa, do zero até o merge, em que o template foi usado para
entregar uma aplicação Java/Spring Boot + React real, com múltiplos agentes (Severino, Yoda, Patrick
Jane, Jarvis) despachados repetidamente. O método é retrospectivo: revisão do próprio histórico da
sessão, não leitura fria do código final — o valor está em **onde o processo gastou tempo e tokens
sem entregar valor**, não só no que ficou errado no artefato final (a aplicação em si terminou
correta, com 130 testes de backend e 21 testes E2E verdes, todos os gates de CI verdes). As correções
concretas já foram aplicadas neste mesmo commit, nos arquivos citados; esta análise é o porquê.

## 1. O maior custo da sessão: protocolo de execução em background não confiável

De longe o maior consumidor de tempo e tokens não foi nenhuma decisão de arquitetura — foi
descobrir, repetidas vezes, se um processo Codex em background estava vivo ou morto. Padrão
observado: o subagente Severino lança o comando canônico em background, e o **próprio subagente**
encerra seu turno dizendo "vou aguardar a notificação" — o que soa como conformidade com a regra
("é proibido encerrar o turno antes do sentinela"), mas na prática **é** encerrar o turno antes do
sentinela. Isso aconteceu tanto quando o processo estava genuinamente morto (sem produzir nada) quanto
quando estava vivo e só ainda não tinha subido os processos filhos da sandbox — e o orquestrador não
tinha como distinguir os dois casos sem verificação manual (`ps aux`, tamanho do arquivo de saída,
espera e nova checagem), repetida talvez quinze vezes ao longo da sessão.

**Custo:** cada rodada de "será que morreu?" consumiu uma mensagem de retomada, uma nova espera
agendada e, na pior rodada, um quase-incidente real: o orquestrador concluiu erroneamente que o
processo tinha morrido, autorizou o fallback Claude a assumir do zero, e **os dois escritores
(Codex ainda vivo + Claude fallback) editaram o mesmo working tree ao mesmo tempo** — só não corrompeu
nada porque a operação em curso (renomear DTOs) era determinística o suficiente para os dois
convergirem no mesmo resultado por acaso, não por design.

**Correção aplicada:** `docs/agentes/severino.md` ganhou uma emenda operacional dizendo
explicitamente que armar um monitor de eventos e encerrar o turno **é** uma forma válida de
aguardar — a proibição é contra declarar conclusão sem o sentinela, não contra usar o mecanismo de
notificação da própria ferramenta. Junto: janela de graça antes de concluir morte, checagem por mais
de um padrão de processo, e uma dívida registrada (não corrigida, por falta de prova) sobre adicionar
`disown`/`setsid` ao comando de background para que o processo sobreviva ao ciclo de vida do shell
que o lançou, já que ao menos duas mortes reais sem sentinela foram observadas nesta sessão sem causa
identificada com certeza.

**Sugestão de eficiência, não aplicada ainda (exige decisão do usuário sobre custo/benefício):**
avaliar se o encaminhamento a Codex em background vale o custo operacional medido nesta sessão frente
a rodar Severino direto na encarnação Claude, sem tentar Codex primeiro, para tarefas onde o
fallback já é esperado com alta probabilidade (o padrão observado nesta sessão foi Codex falhar ou
morrer em bem mais da metade das tentativas de tarefas que tocavam caminhos fora do `.git`/repo,
como escrita em `.codex/` ou na base Obsidian). Isso é decisão do usuário, não algo que este
documento decide sozinho — só nomeia o custo, com o número observado, para que a decisão seja
informada.

## 2. Migração estrutural feita pela metade, sem gate que a detectasse

A reorganização do backend por entidade (equivalente à ADR-003 da aplicação consumidora) foi
aplicada parcialmente: pacotes antigos (por camada técnica) e novos (por entidade) coexistiram,
com classes duplicadas de mesmo nome em pacotes diferentes (`ApiConfig` em dois lugares). O boot do
Spring quebrou com `ConflictingBeanDefinitionException` — um erro claro, mas só descoberto quando
alguém rodou a suíte, porque `docs/continuidade.md` já afirmava "backend completo e verde" sem essa
verificação ter sido de fato executada depois da reorganização.

**Causa raiz dupla:**
1. Nenhum gate mecânico confere, depois de uma migração estrutural, que o esquema antigo foi
   removido por completo — só a suíte de testes acusa (indiretamente, via boot quebrado), e só se
   alguém rodar a suíte antes de declarar a task concluída.
2. A regra que proíbe declarar validação não executada **já existia** (`docs/rules.md`, "Resumo
   decisório mínimo": "não pode declarar validação que não foi executada") e foi violada mesmo assim.
   Isso não é lacuna de regra — é lacuna de **enforcement**: a regra em texto não impediu a violação.

**Correção aplicada:** `docs/playbooks/playbook-backend.md` ganhou a seção A.0, prescrevendo a
escolha entre organização por camada técnica e por entidade **antes** do primeiro código, com o
sinal concreto de quando trocar — para que a migração não aconteça no meio de um projeto real, ou,
quando acontecer, seja tratada como o que é (mudança estrutural com o mesmo peso de qualquer outra).

**Sugestão de eficiência não aplicada:** um gate mecânico simples (grep) que reprova o CI se dois
arquivos `.java` do mesmo projeto declararem a mesma classe pública em pacotes diferentes evitaria
esse exato defeito chegar a rodar localmente. Não implementado aqui porque é específico da
linguagem/build da aplicação consumidora, não do template.

## 3. Convenções de nomenclatura descobertas tarde, corrigidas em massa

Sufixo `DTO`, sufixo `Enum` e sufixo `Teste`/`IntegracaoTeste` em classe de teste não estavam
fixados em nenhum documento antes desta sessão — surgiram como correção pontual do usuário no meio
do projeto, exigindo renomear ~30 arquivos e suas referências de uma vez, incluindo o ajuste do
padrão de descoberta de teste do Maven (`**/*Test.java` → `**/*Teste.java`), que **quase** causou um
falso verde: se o padrão de inclusão do `maven-surefire-plugin` não fosse atualizado no mesmo commit
da renomeação, a suíte teria parado de descobrir qualquer teste, sem erro nenhum — só "Tests run: 0"
silencioso, o pior tipo de regressão porque o build continua verde.

**Correção aplicada:** `docs/playbooks/playbook-backend.md`, seção A.0.1, fixa as três convenções e
nomeia explicitamente o risco de descoberta silenciosa de teste ao renomear, com a instrução de
sempre conferir a contagem real de testes executados depois de qualquer renomeação em massa.

## 4. Base Obsidian: quase-incidente de perda de dado por ambiguidade de escopo

O achado mais sério da sessão, encontrado por Yoda (papel de revisor, corretamente recusando
escrever) antes de qualquer dano: a base Obsidian do template (`Bases/Minerva`) já continha
conteúdo de **outro projeto** (um sistema acadêmico genérico, com seu próprio `ADR-002` e uma
decisão de roadmap do usuário registrada em 2026-09-01). Gravar ali a documentação do desafio MAPS
teria criado dois `ADR-002` no mesmo acervo e sobrescrito a decisão do usuário sem que ele tivesse
pedido — e uma tarefa anterior, sem essa checagem, **já tinha gravado uma nota errada nesse lugar**
antes de o problema ser percebido.

**Causa raiz:** `docs/rules.md` descrevia "a base Obsidian do vault do usuário" no singular, sem
nunca afirmar que cada aplicação consumidora deveria ter a própria base, isolada da base do próprio
template. O sandbox do Codex, coerentemente, também só tinha uma raiz gravável hardcoded.

**Correção aplicada:** `docs/rules.md`, seção "Documentação no Obsidian", agora afirma
explicitamente que `Bases/Minerva` é a base **deste template**, que toda aplicação consumidora
ganha sua própria base nomeada pelo produto, e que a existência/exclusividade dessa base precisa ser
confirmada **antes** da primeira escrita — não depois. `docs/agentes/severino.md` ganhou a nota
correspondente sobre atualizar `writable_roots` como parte da mesma tarefa que cria a base nova, não
como passo posterior.

**Por que isso importa mais que os outros achados:** dos erros desta sessão, este é o único que
teria produzido uma perda real e irreversível de decisão do usuário (o roadmap sobrescrito) se não
tivesse sido pego a tempo. Os outros custaram tempo e tokens; este teria custado confiança e dado.

## 5. Padrões de projeto usados — o que funcionou e onde exigiu ajuste

- **Factory** (`LancamentoActorFactory`, `MovimentacaoActorFactory`, `PosicaoActorFactory`): usada
  corretamente para operações irmãs atrás do mesmo endpoint (crédito/débito, compra/venda, posição
  síncrona/assíncrona). Funcionou bem quando aplicada só depois de já existirem as duas
  implementações concretas — a seção A.0.2 nova do playbook fixa essa condição, que antes só existia
  como convenção implícita.
- **DTO explícito em toda borda REST**: já era regra do playbook (seção B), só faltava a
  nomenclatura — corrigido acima.
- **Actor/Service/DAO com interface só quando há segunda implementação**: já era regra da seção A,
  respeitada; o único ajuste foi tornar o prefixo `I` explícito no texto em vez de implícito no
  exemplo.
- **Autenticação stateless via HTTP Basic + contexto de segurança em `ThreadLocal`**: correto e
  seguro na auditoria que fiz (hash BCrypt com defesa de timing contra enumeração de usuário,
  `ThreadLocal` limpo em `finally`, autorização sempre derivada do principal autenticado no servidor,
  nunca de parâmetro do cliente). Não é um padrão do template — é uma boa decisão da aplicação
  consumidora que vale como referência para futuros projetos com requisito parecido.
- **Streaming/particionamento manual em vez de framework de persistência com cache de entidades**:
  decisão correta e bem justificada em ADR (JPA/Hibernate foi avaliado e descartado exatamente
  porque o cache de primeira sessão contraria um requisito de memória constante sob alto volume). Um
  padrão de arquitetura que vale generalizar no playbook: quando um requisito de memória
  **constante independente de volume** existir, framework de persistência com cache de entidade por
  transação é o primeiro suspeito a descartar, não o ORM em si.

## 6. Auditoria substituída pelo orquestrador quando os agentes revisores ficaram indisponíveis

A API do modelo usado por Yoda e Neo ficou sobrecarregada (HTTP 529) por várias tentativas seguidas
durante a sessão. O orquestrador, depois de tentativas de retomada, conduziu ele mesmo as auditorias
de arquitetura e segurança que caberiam a esses agentes, de forma transparente e registrada. Isso
funcionou como rede de segurança, mas não é o desenho pretendido (regra de ferro 4: três
responsabilidades separadas, para que nenhum agente aprove o próprio trabalho — o orquestrador
substituindo o revisor é uma exceção tolerável sob indisponibilidade externa, não o padrão).

**Sugestão não aplicada:** documentar explicitamente, em `docs/rules.md` ou no catálogo de agentes,
uma cláusula de indisponibilidade externa — quando um agente revisor falha repetidamente por causa
de infraestrutura de terceiro (não por decisão de conteúdo), o orquestrador pode conduzir a revisão
ele mesmo, desde que declare isso explicitamente no relatório, sem tratar como se o agente tivesse
de fato revisado. Hoje essa decisão foi tomada ad hoc, sem apoio explícito de regra.

## Sugestões de velocidade e qualidade, com base em tempo e tokens gastos nesta sessão

1. **A dispersão de tarefas pequenas em muitos despachos separados custou caro.** Nos primeiros
   ciclos da sessão, cada achado pequeno (um gate quebrado, uma dependência faltando em
   `docs/lib.md`) virou um despacho isolado a Severino, cada um pagando de novo o custo fixo de
   lançar o Codex, aguardar, eventualmente cair no fallback. A partir da metade da sessão, o padrão
   mudou para consolidar vários achados relacionados num único despacho grande — e isso reduziu
   visivelmente o número de rodadas de espera por resultado equivalente de trabalho. Recomendação
   para sessões futuras: **agrupar achados pequenos e relacionados num único despacho** em vez de
   despachar a cada achado individual, salvo quando um achado for genuinamente bloqueante para
   entender o próximo.
2. **Verificação independente pelo orquestrador, feita sistematicamente depois de cada relatório de
   subagente, pagou o próprio custo várias vezes** — pegou pelo menos três alegações de "está tudo
   verde" que não bateriam com a realidade se aceitas sem checar (a suíte travada por processo
   concorrente relatada como "resolvida" sem nova execução limpa; o E2E "resolvido" com uma correção
   que na verdade só tocava um dos três bugs). O custo de tempo dessa verificação foi baixo perto do
   risco evitado. Manter.
3. **Perguntar ao usuário nos pontos de decisão real (base Obsidian separada, escopo de nomenclatura,
   merge) custou pouco e evitou decisão errada tomada silenciosamente** — a alternativa (o
   orquestrador decidir sozinho um ponto que a regra de ferro 10 exige subir ao usuário) teria sido
   mais rápida no momento e mais cara depois, se a decisão estivesse errada. Manter o padrão de parar
   e perguntar quando a regra exigir, em vez de inferir.
4. **O maior ralo de tokens não identificado antes desta análise:** logs de CI e de processo em
   background foram lidos repetidamente, por inteiro, em vez de filtrados na primeira leitura. Uma
   prática mais barata, adotada tarde nesta sessão, é sempre grepar por padrões de erro conhecidos
   (`Error:`, `##[error]`, contagem de "failed"/"passed") antes de pedir o log completo — isso já
   reduziu o custo das últimas rodadas de checagem de CI desta sessão e vale como prática padrão
   desde o início.

## O que este documento não é

Não é uma ADR (não decide arquitetura do template) nem uma regra nova de governança — as mudanças
de regra que este achado gerou já foram aplicadas diretamente em `docs/rules.md`,
`docs/agentes/severino.md` e `docs/playbooks/`, no mesmo commit. Este documento é o registro do
porquê, para que a próxima pessoa (ou agente) que revisitar essas seções entenda a pressão real que
as gerou, em vez de encontrar só a regra sem o incidente que a motivou.
