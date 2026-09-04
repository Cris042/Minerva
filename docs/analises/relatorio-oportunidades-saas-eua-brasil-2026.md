# Oportunidades de Vertical SaaS nos Estados Unidos e no Brasil

**Pesquisa aprofundada de mercado, produto e Go-to-Market**
**Data de corte:** 4 de setembro de 2026
**Janela priorizada:** setembro de 2023 a setembro de 2026

## Sumário executivo

Esta pesquisa partiu de problemas observáveis — processos manuais, obrigações regulatórias, fragmentação de dados, baixa integração e reclamações de usuários — antes de formular produtos. O resultado não é uma lista de tendências para copiar dos Estados Unidos. É uma seleção de workflows nos quais um produto brasileiro pode transformar trabalho recorrente em sistema de registro, automação e receita de assinatura.

**Conclusão.** A melhor oportunidade, sob as premissas desta pesquisa, é um SaaS de **conformidade de terceiros e SST por obra**, com um recorte inicial muito estreito: apoiar o responsável a impedir a mobilização ou permanência de trabalhadores terceirizados quando os documentos exigidos estiverem vencidos e gerar evidência auditável por obra. Sua nota-base é **77,8/100** e a nota final ajustada pela força da evidência é **73,1/100**. Em seguida aparecem o portal contábil de coleta e fechamento (**base 76,6; ajustada 72,0**) e a orquestração de MTR/CDF (**base 73,9; ajustada 65,0**). A diferença entre as duas primeiras está dentro da sensibilidade subjetiva de ±5 pontos; portanto, o ranking não substitui validação comercial.

O sinal macro é favorável, mas não autoriza otimismo indiscriminado. Nos EUA, o Census Bureau observou adoção empresarial de IA próxima de 17%–20% no fim de 2025/início de 2026, dependendo da janela e da medida, enquanto o recorte brasileiro do Cetic.br passou de 13% para 17%, e nas pequenas empresas de 10% para 15%. As pesquisas têm populações, perguntas e metodologias diferentes e **não devem ser lidas como comparação direta de maturidade** ([U.S. Census Bureau, 2026](https://www.census.gov/library/stories/2026/05/ai-use-businesses.html); [Cetic.br, 15 jun. 2026](https://cetic.br/pt/noticia/uso-de-inteligencia-artificial-por-empresas-brasileiras-avanca-e-atinge-17-aponta-pesquisa-do-cetic-br/)). No Brasil, 79% das empresas pesquisadas usavam WhatsApp ou Telegram, evidência de que o canal já faz parte do trabalho — mas também de que qualquer novo sistema precisa conviver com ele, não apenas pedir que o usuário o abandone ([Cetic.br, 2026](https://cetic.br/pt/noticia/uso-de-inteligencia-artificial-por-empresas-brasileiras-avanca-e-atinge-17-aponta-pesquisa-do-cetic-br/)).

**Tese central — HIPÓTESE respaldada por sinais de mercado.** Vertical SaaS tende a criar mais valor quando captura um workflow regulado ou repetitivo, torna-se o sistema de registro e acumula dados operacionais próprios. Os benchmarks da Tidemark associam produtos verticais de melhor desempenho à expansão para múltiplos produtos e serviços financeiros, e o benchmark da Stripe acompanha a evolução do modelo vertical; ambos são materiais de investidores/fornecedores e, portanto, sinais direcionais, não prova causal independente ([Tidemark, 2024](https://www.tidemarkcap.com/post/2024-vertical-smb-saas-benchmark-report); [Tidemark, 2025](https://www.tidemarkcap.com/post/2025-vertical-smb-saas-benchmark-report); [Stripe, 2025](https://stripe.com/lp/vertical-saas-benchmark-2025)). A IA aumenta a possibilidade de estruturar documentos e comunicações não estruturadas, porém custos de inferência, integração, supervisão humana e risco de erro podem reduzir a margem. A própria leitura da Bessemer sobre IA vertical deve ser tratada como visão de investidor, não como previsão neutra ([Bessemer Venture Partners, 2025](https://www.bvp.com/atlas/the-state-of-ai-2025)).

### Recomendação operacional

Não iniciar desenvolvimento antes de um gate de evidência:

1. realizar 20 entrevistas com construtoras e empreiteiras pequenas/médias;
2. confirmar que pelo menos 15 mantêm um fluxo manual recorrente de documentos de terceiros por obra;
3. obter cinco cartas de intenção ou pilotos pagos;
4. rejeitar a ideia se esses limiares não forem atingidos.

A oferta inicial sugerida é R$299/mês para uma obra e 50 vidas, R$699/mês para até três obras e 250 vidas e R$1.499/mês para multiobra e até mil vidas, com dois meses de desconto no anual. Esses preços são **HIPÓTESES comerciais**, não preços validados.

## 1. Método, definições e limites

### 1.1 Lógica de investigação

A análise seguiu a sequência **problema → evidência de demanda → mercado → concorrentes → brecha → SaaS → monetização → aquisição → retenção → viabilidade**. Foram usados quatro tipos de evidência:

- **fontes oficiais**, para população empresarial, obrigações, padrões e adoção tecnológica;
- **fontes de empresas e investidores**, para produto, preço, financiamento e alegações de tração, sempre identificadas como declarações interessadas;
- **avaliações de software**, para descobrir tipos de fricção, sem inferir prevalência;
- **fóruns e redes**, como sinais anedóticos úteis para formular perguntas de entrevista, nunca para dimensionar mercado.

Ao longo do documento:

- **FATO** significa informação observável na fonte citada;
- **HIPÓTESE** significa proposição a testar com clientes ou dados operacionais;
- **ESTIMATIVA** significa cálculo reproduzível a partir de premissas explicitadas;
- alegações de fornecedores são apresentadas como alegações, não como confirmação independente;
- comentários no Reddit, Capterra, G2 e Reclame Aqui são anedóticos e não representam a proporção de clientes afetados.

### 1.2 O que o score mede

As 10 finalistas receberam notas de 0 a 10 em 13 critérios. Os pesos, escritos como inteiros cuja soma é 100, são: intensidade da dor **12**; frequência **8**; disposição a pagar **10**; tamanho do mercado **8**; crescimento **7**; concorrência no Brasil **10**; facilidade de aquisição **8**; recorrência **8**; retenção **8**; switching cost **5**; simplicidade técnica **5**; velocidade do MVP **5**; expansão **6**. Em concorrência brasileira, 10 significa **pouca concorrência**. Em simplicidade técnica, 10 significa **mais simples**, inverso da escala de complexidade 1–5 usada nas fichas.

`Nota-base (0–100) = Σ(nota do critério × peso inteiro) ÷ 10`.

Depois, uma nota separada de **Força da evidência (0–10)** modifica a confiança da nota-base:

`fator de evidência = 0,70 + 0,03 × Força da evidência`
`nota final ajustada = nota-base × fator de evidência`.

Assim, evidência 10 preservaria 100% da nota-base; evidência 0 preservaria 70%. O modificador é deliberadamente conservador: reduz o risco de uma hipótese bem narrada, mas pouco observada, superar uma oportunidade com sinais oficiais, concorrência verificável e dor documentada. A força da evidência também é julgamental; não mede qualidade científica em sentido estrito nem elimina esse risco.

O score é uma síntese, não um modelo estatístico. A sensibilidade razoável da nota-base e da ajustada é **±5 pontos**: uma descoberta sobre WTP, canal, prevalência do processo ou integração pode alterar a ordem. O rebaixamento de IA/TMS, por exemplo, reflete baixa evidência direta do processo em PMEs brasileiras: é uma tese mais *solution-first* do que as três finalistas, apesar de seu potencial teórico.

### 1.3 Limitações

Não houve acesso a dados privados de receita, churn, CAC ou coortes dos concorrentes. Rodadas de investimento e aquisições são sinais de convicção de investidores, não prova de PMF ou lucratividade. Preços públicos podem mudar, omitir implantação ou ser segmentados por volume. Listas de concorrentes não garantem cobertura exaustiva, sobretudo em mercados brasileiros regionais. Os cálculos de universo teórico e penetração são cenários de sensibilidade, não TAM/SAM/SOM observados; incluem entidades sem workflow-alvo, orçamento ou prontidão digital. A janela de corte alcança setembro de 2026; fatos posteriores não estão contemplados.

## 2. Tendências e sinais de mercado

### 2.1 Estados Unidos: IA aplicada, verticalização e software para operações físicas

**FATO.** O Census Bureau encontrou crescimento rápido no uso empresarial de IA, mas advertiu que a adoção varia por setor, porte e definição. Seu estudo anterior sobre pequenas empresas também mostra heterogeneidade: empresas pequenas não são um bloco único, e intensidade digital e ocupação importam ([Census Bureau, maio de 2026](https://www.census.gov/library/stories/2026/05/ai-use-businesses.html); [Census Bureau, dez. de 2024](https://www.census.gov/newsroom/blogs/research-matters/2024/12/ai-use-small-businesses.html); [CES Working Paper 24-16](https://www.census.gov/library/working-papers/2024/adrm/CES-WP-24-16.html)).

Os sinais mais relevantes para adaptação não são chatbots horizontais, mas produtos que operam dentro de um processo específico:

- permitting de construção: a PermitFlow anunciou Série B em 13 de março de 2026 e vende coordenação de processos de licença, enquanto a GreenLite anunciou US$49,5 milhões em Série B em 15 de setembro de 2025 para combinar software e especialistas; são sinais de capital e demanda, não demonstrações públicas de rentabilidade ([PermitFlow, comunicado](https://www.permitflow.com/blog/permitflow-series-b); [GreenLite, comunicado](https://greenlite.com/greenlite-raises-49-5m-series-b-to-transform-permitting-with-ai-and-expertise/));
- serviços de campo: BuildOps anunciou Série C em 21 de março de 2025 para software de prestadores comerciais e, posteriormente, a Autodesk anunciou a aquisição da MaintainX em 28 de maio de 2026 e sua conclusão em 3 de agosto de 2026, sugerindo valor estratégico em workflows de manutenção e ativos ([BuildOps, comunicado](https://buildops.com/resources/series-c); [Autodesk, anúncio](https://investors.autodesk.com/news-releases/news-release-details/autodesk-acquire-maintainx-advancing-unified-platform-operations); [Autodesk, conclusão](https://adsknews.autodesk.com/en/news/welcoming-maintainx/));
- frotas: Fleetio combinou Série D e aquisição da Auto Integrate, evidenciando consolidação e expansão funcional; isso também é um alerta de competição para um produto brasileiro genérico de frota ([Fleetio, 2025](https://www.fleetio.com/resources/press/fleetio-raises-series-d-and-acquires-auto-integrate));
- operações locais: Skimmer recebeu investimento de crescimento em 16 de outubro de 2024 e publica preço por unidade atendida, exemplo de SaaS ultravertical em piscinas; Jobber levantou US$100 milhões, mas atende uma categoria horizontal de home services já madura ([Mainsail/Skimmer, comunicado](https://mainsailpartners.com/skimmer-receives-growth-investment-from-mainsail-partners/); [Skimmer, preços](https://www.getskimmer.com/pricing); [General Atlantic/Jobber, comunicado](https://www.generalatlantic.com/media-article/jobber-raises-100-million-growth-round/));
- restaurantes e beleza: 7shifts, Owner e GlossGenius demonstram investimento em operação vertical, pagamentos e aquisição, porém o Brasil já possui plataformas locais relevantes nesses setores ([7shifts, Série C](https://www.7shifts.com/blog/7shift-series-c-funding-announcement/); [Owner, Série C](https://www.owner.com/c); [GlossGenius, Série C](https://www.prweb.com/releases/GlossGenius_secures_28M_in_Series_C_Funding_from_L_Catterton_for_its_business_in_a_box_platform_serving_SMBs_in_the_beauty_and_wellness_industry/prweb19463006.htm)).

**Interpretação.** O padrão não é “IA substitui o SaaS”; é IA embutida em um sistema vertical que já conhece entidade, documento, estado e exceção. O moat potencial vem do histórico de aprovações, taxonomias, integrações e dados de resultado, não do acesso ao mesmo modelo fundacional usado por todos.

#### Mapa compacto das famílias pesquisadas

Esta tabela cobre as famílias solicitadas e explicita onde a pesquisa encontrou sustentação ou lacuna. “Força” se refere ao material reunido neste estudo, não à atratividade universal do setor.

| Família | Sinal observado | Força da evidência aqui | Consequência para o funil |
|---|---|---|---|
| SaaS B2B / Vertical SaaS | Benchmarks Tidemark/Stripe e capital em permitting, manutenção e field service | Média: benchmarks e anúncios têm viés de seleção | Priorizar workflow vertical; não usar múltiplos de mercado como prova |
| SaaS B2C | Pouca evidência direta e nenhum problema B2C com retenção/regulação superior | Fraca | Não levou finalista; CAC e churn exigiriam pesquisa separada |
| Micro SaaS / serviços locais | Skimmer, MoeGo, 7shifts, Jobber, GlossGenius e ofertas locais | Média para existência; fraca para transferibilidade | Piscinas, pet, beleza e restaurantes foram descartados por WTP/concorrência incertos |
| IA e automação | Census/Cetic mostram adoção crescente; Vooma/HappyRobot mostram aplicação logística | Forte para adoção geral; fraca para ROI do caso brasileiro | IA fica como função assistiva; IA/TMS é explicitamente baixa confiança |
| Construção | PAIC, CBIC, NR-18 e fornecedores locais | Forte para tamanho/regulação; média para processo manual específico | Gera compliance de terceiros e licenciamento |
| Logística | Base ANTT e fornecedores de IA/TMS | Forte para universo cadastral; fraca para prevalência do intake manual/WTP | IA/TMS permanece top 10, mas cai para #5 ajustado |
| Financeiro/contábil | CFC, reforma 2026, NFS-e, Financial Cents e concorrentes locais | Forte para universo/regulação; média para coleta manual | Portal contábil é #2; foco em coleta, não cálculo fiscal |
| Saúde | TISS oficial e fornecedores clínicos/home care | Forte para padrão; fraca para prevalência de glosa e processo de home care | Glosa/home care ficam no top 10, sem deep dive |
| Jurídico | Nenhuma subvertical com dor, distribuição e fonte proprietária suficientemente demonstradas | Fraca | Descartado; não propor gestão de prazos genérica |
| Educação | Processo recorrente sugerido, mas sem evidência específica suficiente nesta pesquisa | Fraca | Onboarding/conciliação de escolas descartado |
| Varejo | Reconciliação de canais parece relevante, mas faltam dados específicos e incumbentes são amplos | Fraca | Reconciliação PDV/adquirente/marketplace descartada |
| RH/SST | NR-18/eSocial sustentam obrigação; processo por obra é inferido da operação | Média-forte | SST por obra é #1, condicionado ao gate de entrevistas/pilotos |
| Serviços profissionais | Contabilidade, arquitetura/licenciamento, SST e consultoria ambiental têm buyers identificáveis | Média | Três das cinco primeiras são professional-side/channel-led |
| Marketing e vendas | Sinais de verticalização em Owner/GlossGenius/Rilla, mas concorrência local e CAC não foram medidos | Fraca-média | Nenhum produto genérico de marketing/vendas foi selecionado |

### 2.2 Radar de empresas americanas como sinais de demanda

As empresas abaixo não são propostas para cópia. Foram escolhidas porque materializam um workflow vertical e possuem ao menos um sinal verificável — rodada, aquisição, cliente anunciado, pricing público ou escala declarada. “Presença limitada no Brasil” é **INFERÊNCIA** baseada na ausência de produto localizado/integrações brasileiras nas fontes consultadas; não é prova de ausência comercial absoluta.

| Empresa | Produto, problema e público | Cobrança/diferencial | Sinal de crescimento ou PMF | Concorrentes | Leitura Brasil e dificuldade de adaptação |
|---|---|---|---|---|---|
| PermitFlow | Orquestra licenças de construção para developers, construtoras e profissionais | Assinatura/proposta; workflow + operação especialista | Série B anunciada em 13 mar. 2026 ([comunicado](https://www.permitflow.com/blog/permitflow-series-b)) | GreenLite, Pulley, serviços locais | Presença brasileira limitada, por inferência; dificuldade **5/5** porque regras e portais são municipais |
| GreenLite | Permitting e plan review para construção | Software combinado a especialistas; preço sob consulta | US$49,5 mi em Série B anunciada em 15 set. 2025 ([comunicado](https://greenlite.com/greenlite-raises-49-5m-series-b-to-transform-permitting-with-ai-and-expertise/)) | PermitFlow e expeditores | Presença local limitada, por inferência; modelo de serviço pode ser caro e regulamentação não é portátil |
| Avetta | Qualificação, risco e compliance de contratados/fornecedores | Contrato B2B, rede e dados de fornecedores; preço sob consulta | Produto estabelecido e base de avaliações; reviews são anedóticos ([G2](https://www.g2.com/products/avetta-avetta/reviews)) | ISNetworld, Veriforce, myComply | O problema existe, mas RoCost/GEOB/DocSafe já atuam; adaptar NR-18, eSocial, documentos e ticket PME |
| Financial Cents | Workflow, prazos, colaboração e capacidade para firmas contábeis | Assinatura por usuário/plano; página consultada em CAD | Oferta e pricing recorrente observáveis, sem conversão direta para BRL ([produto](https://financial-cents.com/); [preços em CAD](https://financial-cents.com/pricing/?currency=cad)) | Karbon, Canopy, Jetpack Workflow | Sem adequação fiscal brasileira; copiar tax workflow seria erro, mas coleta/fechamento é transferível |
| Vooma | Automatiza tarefas e comunicação de operadores/corretores logísticos | Assinatura/proposta; agentes integrados ao workflow | Nova rodada e produtos anunciados em 21 maio 2025 ([comunicado](https://www.vooma.com/resources/new-funding-and-products-launch)) | HappyRobot e automação interna | Presença brasileira limitada por inferência, mas concorrentes locais emergiram; dificuldade **5/5** em TMS e linguagem operacional |
| HappyRobot | Agentes de IA para comunicação/execução em logística | Contrato por uso/proposta; voz e canais operacionais | Série B e clientes publicados; DHL anunciou uso em 11 nov. 2025 ([HappyRobot](https://www.happyrobot.ai/blog/series-b-announcement); [DHL](https://group.dhl.com/en/media-relations/press-releases/2025/dhl-boosts-operational-efficiency-and-customer-communications-with-happyrobots-ai-agents.html)) | Vooma e contact center AI | O sinal enterprise não prova fit em PME brasileira; voz, confiabilidade e integração elevam custo |
| Fleetio | Manutenção, inspeção, custo e ativos de frota | SaaS por veículo/usuário; preços em diretório | Série D e aquisição da Auto Integrate anunciadas ([Fleetio](https://www.fleetio.com/resources/press/fleetio-raises-series-d-and-acquires-auto-integrate); [preços/Capterra](https://www.capterra.com/p/120855/Fleetio/pricing/)) | AUTOsist, Whip Around, Samsara | Categoria brasileira já concorrida; adaptação só faz sentido em subvertical documental específico |
| Skimmer | Rotas, serviço, cobrança e comunicação para empresas de piscina | SaaS com tabela pública ligada ao volume de clientes/piscinas | Investimento de crescimento em 16 out. 2024 e especialização clara ([Mainsail](https://mainsailpartners.com/skimmer-receives-growth-investment-from-mainsail-partners/); [preços](https://www.getskimmer.com/pricing)) | Pool Office Manager, Jobber | Nicho brasileiro pode ter densidade/WTP menores; exige pesquisa primária, por isso não chegou ao top 10 |
| BuildOps | ERP/field service para prestadores comerciais de HVAC, elétrica e afins | Contrato por proposta; suite operacional profunda | Série C anunciada em 21 mar. 2025 ([BuildOps](https://buildops.com/resources/series-c)) | ServiceTitan, ServiceTrade | Presença brasileira limitada por inferência, mas o escopo é grande demais para MVP; regras fiscais/trabalhistas elevam adaptação |
| MaintainX | Manutenção, ativos, ordens e procedimentos para operações industriais | Freemium/assinatura com pricing público | Autodesk anunciou aquisição em 28 maio e conclusão em 3 ago. 2026 ([anúncio](https://investors.autodesk.com/news-releases/news-release-details/autodesk-acquire-maintainx-advancing-unified-platform-operations); [conclusão](https://adsknews.autodesk.com/en/news/welcoming-maintainx/); [preços](https://webflow.getmaintainx.com/pricing)) | UpKeep, Fiix, Tractian | Tractian e plataformas locais tornam manutenção horizontal pouco atraente; sinal útil apenas para recortes regulados |

**Síntese de transferibilidade.** PermitFlow/GreenLite oferecem o sinal de crescimento mais claro para um workflow profissional ainda fragmentado, mas também a pior portabilidade regulatória. Vooma/HappyRobot mostram valor da automação dentro da operação, porém a categoria brasileira já está se formando. Financial Cents é o melhor análogo de MVP leve, mas enfrenta bundling local. Avetta é o análogo mais pertinente à tese vencedora, embora sua profundidade e ticket não sejam referência direta para construtoras brasileiras menores. Fleetio/MaintainX/BuildOps são sobretudo evidência desconfirmatória contra entrar com produto horizontal.

### 2.3 Brasil: adoção desigual e WhatsApp como infraestrutura informal

**FATO.** A TIC Empresas mostra adoção de ERP e CRM em recortes por porte e setor, com lacunas persistentes entre empresas; as tabelas devem ser lidas nos respectivos universos amostrais ([Cetic.br, ERP 2025](https://cetic.br/es/tics/pesquisa/2025/empresas/G2/); [Cetic.br, CRM 2025](https://cetic.br/es/tics/pesquisa/2025/empresas/G3/expandido/)). A notícia de 2026 do Cetic.br informa avanço de IA de 13% para 17% entre empresas, e de 10% para 15% entre pequenas, além de 79% usando WhatsApp ou Telegram ([Cetic.br, 2026](https://cetic.br/pt/noticia/uso-de-inteligencia-artificial-por-empresas-brasileiras-avanca-e-atinge-17-aponta-pesquisa-do-cetic-br/)). Barreiras reportadas à adoção de IA incluem falta de conhecimento, custos e compatibilidade, variando por segmento ([Cetic.br, barreiras 2025](https://www.cetic.br/pt/tics/pesquisa/2025/empresas/H13/expandido/)).

O país tem base extensa e dinâmica de empresas, mas quantidade de CNPJs não equivale a mercado pagante; o Mapa de Empresas é referência para demografia empresarial e deve ser segmentado por atividade, porte e atividade real antes de qualquer plano de vendas ([Mapa de Empresas](https://www.gov.br/empresas-e-negocios/pt-br/mapa-de-empresas/mapa-de-empresas)). Estudos setoriais da ABES/IDC apontam continuidade de investimentos em software, mas são materiais de associação/consultoria e servem como contexto, não sizing do nicho ([ABES/IDC](https://abes.org.br/confira-tendencias-tecnologicas-e-previsoes-de-investimentos-apresentadas-em-primeira-mao-pela-abes-e-a-idc/); [ABES, dados do setor](https://abes.com.br/en/dados-do-setor/)).

**HIPÓTESE de produto.** No Brasil, uma interface “WhatsApp-first, database-behind” pode vencer: o usuário envia documento ou solicitação no canal habitual; o SaaS estrutura, valida, cobra pendência, registra decisão e expõe painel. Isso reduz mudança de comportamento, mas cria dependência de políticas, templates, consentimento e custos do canal.

### 2.4 Gap matrix EUA → Brasil

| Workflow | Sinal nos EUA | Situação brasileira observada | O que não se transfere diretamente | Leitura |
|---|---|---|---|---|
| Licenciamento de obras | PermitFlow/GreenLite captaram capital para permitting | Portais municipais e Aprova atuam sobretudo no lado governamental | Regras, formulários, taxas e integrações variam por município e conselho | Oportunidade profissional-side; alto custo de cobertura |
| Terceiros/SST em obras | Avetta, Billy e myComply validam contractor compliance | RoCost, GEOB, DocSafe e suítes de construção/SST já existem | NR-18, eSocial, contratos, documentos e responsabilidade locais | Melhor wedge, mas não é greenfield |
| Intake logístico com IA | Vooma e HappyRobot automatizam comunicação operacional | Sacflow, VexuIA e XMACNA já anunciam IA; TMS locais são incumbentes | WhatsApp, CT-e/MDF-e, tabela/frete, APIs e qualidade de TMS | Grande valor, integração e concorrência crescentes |
| Home care | AlayaCare, WellSky e AxisCare integram escala, cuidado e billing | LonVi, Kuida e Hope Solution já atendem o setor | SUS/saúde suplementar, LGPD e modelos de cuidado distintos | Dor potencial alta, ainda não medida; venda/implementação difíceis |
| Fechamento contábil | Financial Cents, Karbon e Canopy organizam workflow | Acessórias, GuiaFlow, Domínio e Questor/Tareffa disputam atenção | Reforma tributária, documentos fiscais e ecossistemas locais | Não copiar tax engine; atacar coleta e exceções |
| Resíduos/MTR | Encamp, Wastebits e AMCS cobrem compliance/operacional | SINIR e sistemas estaduais gratuitos, Vertown e Ambisis | MTR/CDF e integrações federativas locais | Cobrar pela orquestração, não pelo formulário gratuito |
| Fire inspection/service | Inspect Point, ServiceTrade, BuildingReports | ExtinRadar, Varkon, Protecin/ExtintorWeb | Normas, AVCB/CLCB e Bombeiros por estado | Bom microvertical; mercado potencial menor |
| Claims/denial prevention | Waystar, Tebra, Experian Health | iClinic, Feegow, MV/TOTVS e faturamento | TISS, operadoras e regras de glosa brasileiras | Valor potencial alto, sem prevalência medida; integração difícil |
| Small fleet | Fleetio, AUTOsist, Whip Around | Prolog, TOTVS/NG, Drivvo | Documentos, multas, ANTT e custo de dispositivo | Mercado concorrido; só vale com recorte estreito |
| Calibração/ISO 17025 | Qualer, IndySoft, GAGEtrak | Presys ISOPLAN, Metrosys e SISMETRO | Acreditação Cgcre, certificados e laboratório local | Retenção potencial; mercado elegível não medido |

## 3. Evidências de dor e evidências desconfirmatórias

### 3.1 Sinais recorrentes de dor

1. **Documentos e aprovações fragmentados.** A CBIC descreve digitalização ainda desigual no canteiro e sua pesquisa com 130 respondentes classificou 70% das empresas como tradicionais ou iniciantes em maturidade digital ([CBIC, mar. 2024](https://cbic.org.br/digitalizacao-do-canteiro-promove-mais-produtividade-e-gestao-integrada-da-operacao/); [CBIC, dez. 2025](https://cbic.org.br/pesquisa-nacional-traca-panorama-inedito-da-maturidade-digital-na-construcao/)). Isso não mede especificamente gestão de terceiros, mas sustenta a hipótese de workflows manuais na construção.
2. **Integração e suporte.** Uma reclamação individual no Reclame Aqui descreve falta de conector bancário e atendimento deficiente no Sienge. É um caso anedótico, incapaz de representar a base, mas mostra que integração pode ser decisiva mesmo em suíte consolidada ([Reclame Aqui, relato individual](https://www.reclameaqui.com.br/starian-sistemas/insatisfacao-com-sistema-sienge-pela-falta-de-conector-para-integracao-com-o-banco-bradesco-e-deficiencia-no-atendimento_L9v5736hMwFDwEjW)).
3. **Coleta contábil por mensagens.** Discussões no Reddit perguntam como escritórios coletam documentos e se ainda enviam guias por WhatsApp em 2026. São posts anedóticos e possivelmente sujeitos a viés de autopromoção; servem apenas para orientar entrevistas ([Reddit, coleta de documentos](https://www.reddit.com/r/ContabilidadeAtual/comments/1r0j8d8/como_voc%C3%AAs_lidam_com_a_coleta_de_documentos_de/); [Reddit, envio por WhatsApp](https://www.reddit.com/r/ContabilidadeAtual/comments/1txes4x/em_2026_voc%C3%AAs_ainda_enviam_guias_e_documentos_por/)).
4. **Preço, suporte e impossibilidade de uso.** Um relato individual no Reclame Aqui atribui à Omie cobrança, suporte e cancelamento problemáticos. Não se pode inferir frequência, mas o caso reforça que PMEs valorizam implantação e atendimento, não apenas funcionalidades ([Reclame Aqui, relato individual](https://www.reclameaqui.com.br/omiexperience/plataforma-omie-cobranca-indevida-falta-de-suporte-e-impossibilidade-de-uso-levam-a-reclamacao-de-cancelamento-e-reembolso_cztyvGLFdLBsDXyn/)).
5. **Ferramentas verticais ainda geram fricção.** Avaliações públicas de Skimmer, Jobber, BuildOps, Fleetio, 7shifts e GlossGenius contêm casos individuais sobre preço, bugs, curva de aprendizado, suporte ou funcionalidades. Essas páginas agregam avaliações, mas não autorizam afirmar que a maioria está insatisfeita; seu valor aqui é revelar categorias de objeção ([Skimmer/Capterra](https://www.capterra.com/p/177014/Skimmer/); [Jobber/Capterra](https://www.capterra.com/p/127994/Jobber/reviews/); [BuildOps/Capterra](https://www.capterra.com/p/194155/BuildOps/reviews/); [Fleetio/Capterra](https://www.capterra.com/p/120855/Fleetio/reviews/); [7shifts/Capterra](https://www.capterra.com/p/123038/7shifts-Restaurant-Scheduling/reviews/); [GlossGenius/Capterra](https://www.capterra.com/p/174830/GlossGenius/reviews/)).
6. **A experiência de “mais uma ferramenta” é um risco.** Um fio de profissionais de piscina debate se Skimmer resolve o processo; é evidência anedótica e não mensura satisfação, mas mostra que migração, adequação ao fluxo e custo são perguntas centrais ([Reddit/PoolPros, relato anedótico](https://www.reddit.com/r/PoolPros/comments/1scstjf/is_skimmer_the_answer/)).
7. **Sistemas clínicos podem falhar em pontos críticos.** Uma reclamação individual relata problemas recorrentes e falta de suporte em prescrição no iClinic. É um caso isolado; sua utilidade é evidenciar a importância de suporte e confiabilidade quando o workflow afeta cuidado ([Reclame Aqui, relato individual](https://www.reclameaqui.com.br/iclinic/problemas-recorrentes-e-falta-de-suporte-tecnico-na-ferramenta-de-prescricao-do-iclinic_wlQBdfZbeImTqBYg/)).
8. **Permitting tem pouca evidência pública de usuário no Brasil.** Uma discussão recente no Reddit brasileiro sugere interesse, mas não valida disposição a pagar e pode conter viés de pesquisa do próprio autor ([Reddit/arquitetura, sinal anedótico](https://www.reddit.com/r/arquitetura/comments/1tkfgc7/arquitetos_engenheiros_e_profissionais_que_lidam/)).

### 3.2 Evidência desconfirmatória e saturação

**Tese contra 1 — vários “gaps” já têm fornecedores locais.** Frota não é espaço vazio: Prolog afirma atender operações e publica casos; TOTVS vende gestão de frotas. Beleza tem Trinks; restaurantes têm Saipos e Sischef; pet tem PetBanho e Pette ([Prolog, casos](https://www.prologapp.com/cases-de-sucesso/); [TOTVS, frota](https://www.totvs.com/totvs-gestao-de-frotas/); [Trinks](https://www.trinks.com/); [Saipos](https://saipos.com/sistema/restaurante); [Sischef](https://sischef.com/recursos-funcionalidades/); [PetBanho](https://www.petbanho.com.br/); [Pette](https://www.gestaopette.com.br/)). Entrar com produto genérico nesses mercados provavelmente cria guerra de preço e CAC alto.

**Tese contra 2 — software gratuito/regulatório comprime WTP.** O MTR nacional e sistemas estaduais permitem emitir a obrigação básica; um SaaS privado precisa vender consolidação multiunidade, validação, alertas e evidência, não “emitir MTR” ([serviço MTR](https://www.gov.br/pt-br/servicos/obter-o-documento-manifesto-de-transporte-de-residuos-mtr?id=2458&origem=servico); [portal SINIR/MTR](https://mtr.sinir.gov.br/)). Analogamente, portais públicos de licenciamento reduzem espaço para cobrar pelo protocolo puro ([Portal de Licenciamento de São Paulo](https://portaldelicenciamento.prefeitura.sp.gov.br/)).

**Tese contra 3 — investimento americano pode indicar competição, não oportunidade tardia.** PermitFlow/GreenLite, Fleetio, MaintainX e outros receberam capital ou foram adquiridos. Isso valida relevância do workflow, mas eleva a expectativa do comprador e o risco de incumbentes entrarem no Brasil por parceria ou aquisição. Em IA logística, Sacflow, VexuIA e XMACNA já anunciam ofertas locais, portanto a janela pode estar fechando ([Sacflow](https://sacflow.com.br/automacao-de-whatsapp-para-transportadoras); [VexuIA](https://vexuit.com/transportadora); [XMACNA](https://xmacna.ai/ia-transportadora)).

**Tese contra 4 — “WhatsApp-first” pode virar serviço intensivo.** Se cada cliente exigir regras, documentos, integrações e exceções próprias, margem e velocidade de implantação caem. A prevalência do WhatsApp mostra hábito, não disposição a pagar nem facilidade técnica. A integração deve ser parametrizável e supervisionada.

**Tese contra 5 — HIPÓTESE: regulação pode criar retenção e responsabilidade.** NR-18, TISS, MTR, LGPD e acreditação geram obrigações recorrentes; um erro de software pode contribuir para bloqueio, atraso ou exposição de dado. A agenda regulatória da ANPD reforça que governança continua evoluindo ([ANPD, Agenda Regulatória 2025–2026](https://www.gov.br/anpd/pt-br/assuntos/noticias/anpd-publica-agenda-regulatoria-2025-2026)). O produto deve deixar decisão humana e trilha explícitas.

## 4. Funil de 24 oportunidades candidatas até as 10 finalistas

Cada linha expressa **produto + nicho + workflow + comprador**. O funil registra o sinal disponível e a decisão; “finalista” significa apenas merecedora de avaliação detalhada.

| # | Produto / nicho / workflow / comprador | Evidência ou sinal | Decisão |
|---:|---|---|---|
| 1 | Copiloto para arquitetos/engenheiros que organiza checklist, versões, exigências e prazos de alvarás; comprador: escritório técnico/incorporadora | Fragmentação municipal; PermitFlow/GreenLite; guia federal | Finalista, com baixa cobertura inicial |
| 2 | Gate documental de terceiros por obra; comprador: gerente de SST/engenharia | NR-18, maturidade digital desigual e concorrentes locais | Finalista; melhor combinação de evidência e recorrência |
| 3 | Intake assistido de cotações no TMS para ETCs; comprador: diretor operacional/comercial | ANTT e sinais Vooma/HappyRobot; processo local é hipótese | Finalista de baixa confiança; risco técnico alto |
| 4 | Escala, evidência de visita e exportação para home care; comprador: operador assistencial | Players EUA/BR; processo e WTP pouco documentados | Finalista, mas evidência fraca e alta complexidade |
| 5 | Portal de coleta/classificação/pendências para escritórios contábeis; comprador: sócio/gerente | CFC, reforma, Financial Cents, concorrentes e sinais anedóticos | Finalista; MVP rápido, mercado concorrido |
| 6 | Reconciliação MTR→recebimento→CDF para consultorias e operadores de resíduos; comprador: gestor ambiental/dono | Obrigação oficial por transporte, sete sistemas estaduais e vendors locais | Finalista #3 ajustada; não competir com emissão grátis |
| 7 | App de ativos, inspeção e renovação para prestadoras de segurança contra incêndio; comprador: dono/gerente | Concorrentes verticais nos EUA e Brasil | Finalista; evidência de dor/WTP ainda fraca |
| 8 | Validador pré-envio TISS para clínicas; comprador: gestor financeiro/faturamento | Padrão oficial e soluções de revenue cycle; prevalência da glosa não medida | Finalista, com risco técnico/comercial alto |
| 9 | Checklist, vencimento e manutenção para pequenas frotas de um subnicho; comprador: dono/gestor | Fleetio e fornecedores brasileiros maduros | Finalista com ressalva de saturação |
| 10 | Ordem, rastreabilidade e certificado para laboratórios ISO 17025; comprador: qualidade/dono | Acreditação e fornecedores especializados | Finalista; retenção hipotética alta, universo estreito |
| 11 | Rota, serviço e cobrança para empresas de manutenção de piscinas; comprador: proprietário | Skimmer comprova formato vertical; sinal local insuficiente | Descartada: densidade e WTP brasileiros não demonstrados |
| 12 | Rota, laudo e renovação para dedetizadoras; comprador: proprietário | Workflow parece recorrente, mas pouca evidência específica | Descartada: sobreposição com field service |
| 13 | Checklist e dossiê de segurança alimentar para pequenos fabricantes/cozinhas; comprador: qualidade/dono | Obrigação é plausível, mas buyer e prevalência não foram medidos | Descartada: consultoria pode substituir software |
| 14 | Escala CLT/gorjetas para restaurantes; comprador: operador de rede | 7shifts nos EUA; Saipos/Sischef locais ([7shifts](https://www.7shifts.com/blog/7shift-series-c-funding-announcement/); [Saipos](https://saipos.com/sistema/restaurante); [Sischef](https://sischef.com/recursos-funcionalidades/)) | Descartada: oferta local madura e churn potencial |
| 15 | Onboarding e conciliação de mensalidades para escolas; comprador: mantenedor/financeiro | Recorrência sugerida, mas pouca evidência específica | Descartada: diferenciação e WTP não demonstrados |
| 16 | Calendário e evidência de manutenção condominial; comprador: administradora/síndico profissional | Workflow sugerido, sem brecha documentada | Descartada: sobreposição com ERP de administradora |
| 17 | Controle de prazos para uma subvertical jurídica; comprador: sócio do escritório | Criticidade presumida, sem dado ou distribuição exclusiva | Descartada: genérico e consolidado |
| 18 | Agenda, pagamentos e retenção para beleza/medspa; comprador: proprietário | GlossGenius nos EUA e Trinks no Brasil | Descartada: concorrência e CAC provável altos |
| 19 | Rota/agendamento para grooming móvel pet; comprador: proprietário | MoeGo captou capital e publica pricing ([Série A](https://www.prnewswire.com/news-releases/moego-secures-24-million-series-a-led-by-base10-to-revolutionize-the-pet-care-economy-302083433.html); [preços](https://www.moego.pet/pricing?companyType=0)) | Descartada: densidade local/WTP incertos e oferta barata |
| 20 | Vistoria fotográfica de locação com laudo/assinatura; comprador: imobiliária/vistoriador | Workflow claro, mas sem evidência de WTP independente | Descartada: proptech pode incorporar |
| 21 | Escala e evidência de responsável técnico veterinário; comprador: clínica/rede | Hipótese operacional, sem evidência suficiente | Descartada: buyer pequeno e tese pouco substanciada |
| 22 | Reconciliação PDV/adquirente/marketplace para varejistas multicanal; comprador: financeiro | Fragmentação é plausível, mas dados e canal não foram demonstrados | Descartada: fintech/ERP horizontal e integração cara |
| 23 | Avaliação isolada de risco psicossocial NR-1; comprador: RH/SST | Urgência regulatória sugerida | Descartada: feature copiável e demanda possivelmente episódica |
| 24 | Renovação documental para corretores de seguros; comprador: corretora | Recorrência sugerida, sem intensidade/WTP documentados | Descartada: evidência insuficiente |

O descarte não afirma inexistência de negócio; afirma que, com as evidências disponíveis, essas teses têm pior relação entre diferenciação, CAC, WTP, complexidade e possibilidade de MVP pequeno.

## 5. Ranking e matriz de score

| Pos. ajustada | Oportunidade | Dor | Freq. | WTP | Mercado | Cresc. | Conc. BR* | Aquisição | Recorr. | Retenção | Switch | Simplic. | MVP | Expansão | Base | Força da evidência | Fator | **Final ajustada** |
|---:|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| 1 | Conformidade de terceiros/SST por obra | 9 | 9 | 8 | 8 | 8 | 4 | 7 | 9 | 9 | 9 | 6 | 7 | 8 | 77,8 | 8 | 0,94 | **73,1** |
| 2 | Portal contábil de coleta/fechamento | 8 | 10 | 7 | 7 | 9 | 3 | 8 | 10 | 8 | 8 | 7 | 8 | 8 | 76,6 | 8 | 0,94 | **72,0** |
| 3 | MTR/CDF para resíduos | 8 | 9 | 7 | 6 | 8 | 6 | 6 | 9 | 8 | 8 | 6 | 7 | 8 | 73,9 | 6 | 0,88 | **65,0** |
| 4 | Frota pequena: compliance/manutenção | 8 | 9 | 7 | 8 | 7 | 2 | 7 | 9 | 8 | 8 | 6 | 7 | 8 | 71,6 | 6 | 0,88 | **63,0** |
| 5 | IA operacional sobre TMS | 8 | 9 | 8 | 9 | 9 | 5 | 6 | 9 | 8 | 8 | 3 | 4 | 9 | 74,6 | 4 | 0,82 | **61,2** |
| 6 | Copiloto de licenciamento/alvarás | 8 | 7 | 7 | 8 | 8 | 6 | 7 | 7 | 7 | 6 | 5 | 6 | 9 | 70,9 | 5 | 0,85 | **60,3** |
| 7 | Prevenção de glosas TISS | 10 | 9 | 9 | 7 | 8 | 4 | 5 | 9 | 8 | 7 | 3 | 4 | 8 | 72,8 | 4 | 0,82 | **59,7** |
| 8 | Operação de segurança contra incêndio | 8 | 8 | 7 | 5 | 7 | 5 | 7 | 9 | 8 | 8 | 7 | 8 | 7 | 71,8 | 4 | 0,82 | **58,9** |
| 9 | Workflow ISO 17025/calibração | 8 | 8 | 8 | 4 | 6 | 7 | 6 | 9 | 9 | 9 | 5 | 6 | 6 | 71,2 | 4 | 0,82 | **58,4** |
| 10 | Operação de home care | 9 | 10 | 6 | 5 | 6 | 4 | 4 | 10 | 9 | 9 | 2 | 4 | 8 | 67,7 | 3 | 0,79 | **53,5** |

\* 10 = menor concorrência brasileira. “Simplic.” também é positiva: 10 = tecnicamente mais simples. **Final ajustada**, e não Base, é a nota final de oportunidade usada no ranking.

As notas de evidência 8 para terceiros e contabilidade refletem fontes oficiais de universo/regulação combinadas a concorrentes e sinais de workflow, ainda sem WTP observado. MTR recebe 6 porque a obrigação e a fragmentação são oficiais, mas o ICP nacional não é quantificado. Frota recebe 6 por categoria amplamente observável, apesar da brecha estreita não validada. Licenciamento recebe 5; IA/TMS, glosa, incêndio e calibração recebem 4; home care recebe 3 porque dependem progressivamente mais de inferências sobre processo, intensidade e WTP.

### TOP 10 — visão executiva

| # | Ideia e nicho | Problema/comprador | Concorrência BR / EUA | Preço mensal potencial | Técnica / comercial | Evid. | Base → **Final** |
|---:|---|---|---|---:|---:|---:|---:|
| 1 | Terceiros/SST em obras | Se requisito vencer, responsável precisa impedir/liberar com evidência; engenharia/SST | BR média-alta; EUA alta | R$299–1.499 | 3/5; 3/5 | 8 | 77,8 → **73,1** |
| 2 | Portal de fechamento contábil | Documento chega disperso; sócio do escritório | BR alta; EUA alta | R$199–1.499 | 2/5; 2/5 | 8 | 76,6 → **72,0** |
| 3 | MTR/CDF | Fechamento de transporte entre MTR, recebimento e CDF; consultoria/operador | BR média + governo grátis; EUA alta | R$699–2.500 | 3/5; 3/5 | 6 | 73,9 → **65,0** |
| 4 | Frota pequena | Hipótese de manutenção/documentos dispersos; dono/gestor | BR alta; EUA alta | R$199–1.500 | 3/5; 3/5 | 6 | 71,6 → **63,0** |
| 5 | IA sobre TMS | Hipótese de redigitação de cotações; transportadora | BR emergente; EUA emergente | R$1.490–5.990 | 5/5; 4/5 | 4 | 74,6 → **61,2** |
| 6 | Copiloto de alvarás | Requisitos municipais variáveis; escritório técnico | BR incerta/moderada; ausência abrangente é inferência | R$249–1.999 | 4/5; 3/5 | 5 | 70,9 → **60,3** |
| 7 | Antiglosa TISS | Inconsistência pode gerar glosa/retrabalho; clínica | BR alta; EUA alta | R$699–5.000+ | 5/5; 5/5 | 4 | 72,8 → **59,7** |
| 8 | Segurança contra incêndio | Hipótese de inspeção/validade dispersas; prestadora | BR média; EUA alta | R$199–1.499 | 2/5; 3/5 | 4 | 71,8 → **58,9** |
| 9 | ISO 17025/calibração | Hipótese de certificado/rastreabilidade fragmentados; laboratório | BR baixa-média; EUA estabelecida | R$499–2.500 | 4/5; 4/5 | 4 | 71,2 → **58,4** |
| 10 | Home care | Hipótese de escala/evidência desconectadas; operador | BR média; EUA alta | R$1.000–6.000 | 5/5; 5/5 | 3 | 67,7 → **53,5** |

## 6. Fichas completas das 10 oportunidades

### 6.1 Conformidade de terceiros e SST por obra

**Problema. FATO regulatório + HIPÓTESE operacional.** A NR-18 estrutura obrigações de segurança na construção. Construtoras precisam definir requisitos antes/durante a obra; a hipótese é que documento vencido, ilegível ou associado à pessoa errada possa atrasar a mobilização e dificultar evidência. O software não pode prometer “conformidade automática” ([NR-18, Portaria SEPRT 3.733/2020](https://www.gov.br/trabalho-e-emprego/pt-br/assuntos/inspecao-do-trabalho/seguranca-e-saude-no-trabalho/sst-portarias/2020/Portaria_SEPRT_3.733_Altera_a_NR_18.pdf)).

**Usuário e comprador.** Usuários: analista de documentação, técnico de SST, administrativo da obra, preposto da terceirizada e portaria. Compradores: gerente de SST, engenharia, suprimentos ou diretor de operações de construtora pequena/média.

**Processo atual. HIPÓTESE a validar.** Planilha mestra, pastas em nuvem, anexos por e-mail/WhatsApp, conferência manual, lembretes individuais e dossiês montados sob demanda. A pesquisa da CBIC sustenta baixa maturidade digital geral, não a prevalência desse fluxo específico ([CBIC, 2025](https://cbic.org.br/pesquisa-nacional-traca-panorama-inedito-da-maturidade-digital-na-construcao/)).

**Intensidade/frequência. HIPÓTESE a validar.** Pode ser alta e semanal/diária enquanto houver entrada de terceiros, vencimentos e mudanças de obra. Os efeitos possíveis — não medidos nesta pesquisa — incluem atraso de mobilização, retrabalho de conferência e falta de evidência.

**Solução.** Um gate documental por obra: cada requisito possui responsável, validade e decisão; o trabalhador só recebe status liberado após aprovação humana, e o histórico fica auditável.

**Funções mínimas.** Cadastro de obra/empresa/colaborador; templates de checklist por função; upload por link e WhatsApp; OCR assistido; validade; fila de revisão; aprovar/reprovar/bloquear; alertas; dossiê PDF; log de decisão; exportação.

**Concorrentes EUA.** Avetta, Billy e myComply validam contractor compliance e onboarding. A página de avaliações da Avetta no G2 contém opiniões individuais sobre uso, suporte e complexidade; não representa toda a base ([Avetta/G2, avaliações anedóticas](https://www.g2.com/products/avetta-avetta/reviews)).

**Concorrentes Brasil.** RoCost, GEOB, DocSafe, SegWork e Inspeseg; Sienge/Mobuss são indiretos por já ocuparem o stack de construção ([RoCost](https://rocost.com.br/); [GEOB](https://www.geobobra.com.br/); [DocSafe](https://www.docsafe.app.br/); [SegWork](https://www.segworksst.com.br/); [Inspeseg](https://inspeseg.com/); [Sienge](https://sienge.com.br/blog/conheca-as-versoes-do-sienge/)).

**Brecha.** Não é ausência de concorrência. É um produto mais simples, centrado no gate de mobilização/permanência por obra, colaboração com a terceirizada pelo canal habitual e evidência pronta. Deve integrar ou exportar para suítes, não substituí-las.

**Monetização.** HIPÓTESE: R$299/mês até uma obra/50 vidas; R$699 até três/250; R$1.499 multiobra/mil; excedente por vida ativa ou obra; anual por 10 mensalidades. Ticket baixo no primeiro plano, médio nos demais; enterprise acima de R$1.500.

**Ticket potencial.** Baixo (<R$300) na entrada; médio (R$300–1.500) nos planos principais; alto (>R$1.500) em enterprise/excedentes.

**Retenção. HIPÓTESE.** Pode ser alta se histórico, templates e identidades forem incorporados ao início de cada obra. Pode cair entre obras; plano holding ou arquivo talvez reduza churn sazonal.

**Switching cost. INFERÊNCIA.** Tende a aumentar com documentos, histórico de aprovação, templates e vínculos pessoa/empresa/obra, mas não foi medido. Exportação deve existir por ética e LGPD.

**GTM.** Outbound baseado em obras ativas, parcerias com consultorias SST, contabilidades da construção, sindicatos/associações, webinars de mobilização e pilotos em uma obra.

**Complexidade técnica.** 3/5. OCR e WhatsApp são administráveis; identidade, permissão, versionamento e trilha exigem rigor.

**Complexidade comercial.** 3/5. Dor é clara, mas múltiplas áreas influenciam e cada contratante pode querer regra própria.

**Barreiras.** NR-18, eSocial como integração futura, LGPD, documentos sensíveis, responsabilidades contratuais e regras por contratante. O manual web do eSocial evidencia um ecossistema próprio que não deve ser replicado no MVP ([eSocial](https://www.gov.br/esocial/pt-br/empresas/manual-web-geral)).

**MVP.** Uma obra, templates configuráveis, upload por link, revisão humana, validade, bloqueio, alertas e PDF. Sem biometria, catraca, motor jurídico, EHS completo ou promessa de conformidade.

### 6.2 Portal contábil de coleta e fechamento

**Problema. INFERÊNCIA a validar.** Escritórios com carteiras maiores podem gastar trabalho recorrente obtendo documentos, identificando ausências, cobrando, classificando e provando o que chegou antes do fechamento; a prevalência não foi medida.

**Usuário e comprador.** Usuários: assistentes fiscal/contábil/DP e o cliente da empresa. Comprador: sócio ou gerente de operações do escritório.

**Processo atual. INFERÊNCIA apoiada por sinal anedótico.** E-mail, WhatsApp, drive, portal do ERP, planilha e memória do responsável aparecem como hipótese; posts no Reddit ilustram esse tipo de uso, mas não medem prevalência ([Reddit, coleta](https://www.reddit.com/r/ContabilidadeAtual/comments/1r0j8d8/como_voc%C3%AAs_lidam_com_a_coleta_de_documentos_de/)).

**Intensidade/frequência. INFERÊNCIA a validar.** A competência contábil sugere repetição mensal e picos de fechamento, mas intensidade e horas consumidas não foram medidas.

**Solução.** Checklist mensal por cliente e competência, caixa de entrada omnicanal, classificação assistida, cobrança de pendências e exportação para o stack existente.

**Funções mínimas.** Templates por regime/perfil; link/WhatsApp/e-mail de entrada; OCR; sugestão de tipo/competência; pendências; lembretes; trilha; painel de fechamento; exportação ZIP/CSV/API.

**Concorrentes EUA.** Financial Cents, Karbon e Canopy. Financial Cents publica planos e vende workflow para firmas contábeis; a página de preço consultada está em **CAD**, evidência de assinatura e não referência cambial ou de adequação fiscal ao Brasil ([Financial Cents, produto](https://financial-cents.com/); [preços em CAD](https://financial-cents.com/pricing/?currency=cad)).

**Concorrentes Brasil.** Acessórias, GuiaFlow, Domínio, Questor Tareffa e Omie indireto. O GuiaFlow posiciona automação de envio/cobrança de documentos, confirmando que o espaço não é vazio ([GuiaFlow](https://guiaflow.com.br/)).

**Brecha.** Experiência externa simples para o cliente do contador, WhatsApp bem integrado, ingestão sem exigir login, classificação assistida e neutralidade em relação a ERP. Não construir cálculo tributário.

**Monetização.** HIPÓTESE: R$199 até 30 clientes, R$399 até 100, R$799 até 300, R$1.499 até 700; excedente por CNPJ; anual por 10 mensalidades. Ticket baixo/médio.

**Ticket potencial.** Baixo a médio; contratos acima de R$1.500 só com carteiras maiores ou serviços adicionais.

**Retenção. HIPÓTESE.** Pode ser alta pela repetição mensal e pelos templates; pode ser baixa se o produto for apenas “disparador de mensagens”.

**Switching cost. HIPÓTESE.** Pode tornar-se médio-alto quando histórico e padrões ficam acumulados; tende a ser baixo se o valor for só lembrete.

**GTM.** Comunidades contábeis, parceiros de implantação de Domínio/Questor/Omie, conteúdo sobre fechamento e reforma, prova de conceito com 10 clientes do escritório.

**Complexidade técnica.** 2/5 no MVP; 4/5 quando integrações fiscais e ERP entram.

**Complexidade comercial.** 2/5 para pequenos escritórios; objeção de preço e inércia são centrais.

**Barreiras.** LGPD, sigilo, retenção de documento, autenticação e mudanças da reforma tributária. A Receita mantém orientações específicas para 2026, mas o produto deve apenas adaptar checklists e exportações ([Receita Federal, Reforma Tributária 2026](https://www.gov.br/receitafederal/pt-br/acesso-a-informacao/acoes-e-programas/programas-e-atividades/reforma-tributaria-do-consumo/orientacoes-2026)).

**MVP.** Checklist mensal, inbox por link/WhatsApp, OCR/classificação assistida, pendências, trilha e exportação. Sem motor fiscal, escrituração ou ERP.

### 6.3 IA operacional sobre TMS para transportadoras

**Problema. HIPÓTESE de baixa confiança, orientada pela solução.** Presume-se que parte das ETCs receba cotações por e-mail/WhatsApp, extraia rota/carga/prazo e redigite no TMS. A prevalência, o tempo perdido e a taxa de erro não foram medidos no Brasil; por isso IA/TMS permanece na ficha, mas não no deep dive.

**Usuário e comprador.** Usuários: comercial, pricing, atendimento e torre de controle. Compradores: diretor operacional/comercial ou dono de ETC pequena/média.

**Processo atual. HIPÓTESE a validar.** Caixa compartilhada, grupos, telefone, planilha, consulta a TMS e redigitação são uma descrição *solution-first* ainda sem medida de prevalência em PMEs brasileiras.

**Intensidade/frequência. HIPÓTESE a validar.** Seria alta e diária apenas em transportadoras com volume relevante de pedidos; esse limiar e a população elegível não foram medidos.

**Solução.** Camada que monitora canais autorizados, extrai campos com confiança, encontra duplicatas, monta rascunho no TMS/CSV/API e exige aprovação humana.

**Funções mínimas.** Inbox; parser de e-mail/WhatsApp/anexo; esquema de cotação; score de confiança; fila de exceções; regras por cliente; rascunho/exportação; resposta sugerida; log.

**Concorrentes EUA.** A Vooma anunciou nova rodada e produtos em 21 de maio de 2025, e a HappyRobot anunciou Série B; são sinais de financiamento e expansão de oferta, não prova independente de PMF. Em 11 de novembro de 2025, a DHL publicou o uso de agentes da HappyRobot, sinal de adoção corporativa segundo as partes, não medida independente de resultado ([Vooma, comunicado](https://www.vooma.com/resources/new-funding-and-products-launch); [HappyRobot, Série B](https://www.happyrobot.ai/blog/series-b-announcement); [DHL, comunicado](https://group.dhl.com/en/media-relations/press-releases/2025/dhl-boosts-operational-efficiency-and-customer-communications-with-happyrobots-ai-agents.html)).

**Concorrentes Brasil.** Sacflow, VexuIA e XMACNA anunciam automação/IA para transportadoras; nstech e TMSs são indiretos e podem incorporar a feature ([Sacflow](https://sacflow.com.br/automacao-de-whatsapp-para-transportadoras); [VexuIA](https://vexuit.com/transportadora); [XMACNA](https://xmacna.ai/ia-transportadora); [nstech](https://nstech.com.br/)).

**Brecha.** Começar por um caso mensurável — intake de cotação — com conectores para TMS brasileiro, português logístico e aprovação. Evitar “agente autônomo para tudo”.

**Monetização.** HIPÓTESE: R$1.490/mês com franquia, R$2.990/R$5.990 por volume e integrações; implantação R$2 mil–15 mil; anual com desconto. Ticket médio-alto, podendo superar R$1.500.

**Ticket potencial.** Médio no plano inicial; alto nos planos por volume e integração.

**Retenção. HIPÓTESE.** Poderia ser alta se inserido no fluxo e conectado ao TMS, ou baixa se for apenas sumarizador.

**Switching cost. HIPÓTESE.** Poderia tornar-se médio-alto por regras, histórico, avaliações, integrações e treinamento; não há coortes observadas.

**GTM.** Venda consultiva, listas ANTT segmentadas, parceiros TMS, associações e caso-piloto com tempo por cotação/erro antes e depois.

**Complexidade técnica.** 5/5: documentos variados, APIs legadas, observabilidade, segurança e custo de modelos.

**Complexidade comercial.** 4/5: prova de ROI e confiança operacional; múltiplos stakeholders.

**Barreiras.** LGPD, sigilo comercial, CT-e/MDF-e como expansão, integração, hallucination e responsabilidade por preço incorreto.

**MVP.** E-mail/WhatsApp autorizado → campos estruturados → rascunho TMS/CSV/API → aprovação humana. Sem voz e sem ação autônoma ampla.

### 6.4 Copiloto de licenciamento e alvarás

**Problema. FATO contextual + HIPÓTESE operacional.** O guia do MDIC documenta boas práticas para alvarás; a hipótese é que escritórios gastem trabalho relevante acompanhando requisitos, versões, protocolos e exigências diferentes por município. A fonte não mede esse tempo nem prova ausência de solução ([MDIC, Guia de Alvarás](https://www.gov.br/mdic/pt-br/assuntos/sdic/construa-brasil/produtos/GuiaOrientativodeBoasPrticasparaObtenodeAlvarsdeConstruocompressed.pdf)).

**Usuário e comprador.** Arquiteto, engenheiro, despachante e analista de legalização; comprador é sócio do escritório ou incorporadora.

**Processo atual. INFERÊNCIA a validar.** O uso combinado de portais municipais, planilhas, pastas, e-mail e consultas manuais é plausível, mas não foi quantificado. Fiscalização profissional e normas dos conselhos adicionam contexto local ([CAU, fiscalização](https://caubr.gov.br/fiscalizacao/); [Confea/CAU, decisão 2026](https://transparencia.caubr.gov.br/deliberacaoplenariadpobr0169-08-2026/)).

**Intensidade/frequência. HIPÓTESE a validar.** Pode ser alta por projeto, porém é descontínua e depende do pipeline, do município e do tipo de licença.

**Solução.** Workspace por projeto que recomenda checklist municipal, organiza versões, monitora protocolo e prepara respostas, sempre com validação profissional.

**Funções mínimas.** Cobertura inicial de 2–3 municípios; checklist versionado; armazenamento; tarefas/prazos; log de exigências; modelos; status compartilhável.

**Concorrentes EUA.** PermitFlow, GreenLite e Pulley. As duas primeiras captaram capital e combinam tecnologia com operação; isso valida relevância, mas o conteúdo regulatório não é portátil ([PermitFlow](https://www.permitflow.com/); [GreenLite](https://greenlite.com/about-greenlite/)).

**Concorrentes Brasil.** Aprova e portais municipais são fortes no lado do governo. A ausência de equivalente nacional abrangente para o profissional é **INFERÊNCIA**, não fato absoluto ([Aprova](https://aprova.com.br/solucoes/obras); [Portal SP](https://portaldelicenciamento.prefeitura.sp.gov.br/)).

**Brecha.** Cobertura por município e tipo de projeto, com comunidade/rede de especialistas; não tentar nacionalizar no primeiro ano.

**Monetização.** HIPÓTESE: R$249 individual, R$699 escritório, R$1.999 incorporadora; adicional por protocolo ou serviço especialista; anual 15%–20% menor. Ticket baixo a alto.

**Ticket potencial.** Baixo para profissional individual, médio para escritório e alto para incorporadora/volume.

**Retenção. HIPÓTESE.** Pode ser média e aumentar com portfólio, histórico e renovações; pode cair em escritórios com poucos protocolos.

**Switching cost. HIPÓTESE.** Provavelmente médio: dados de projeto ajudam, mas o usuário pode voltar à planilha ou ao portal municipal.

**GTM.** SEO hiperlocal (“alvará + município + tipo”), CAU/CREA, escritórios parceiros, cursos e concierge nos primeiros projetos.

**Complexidade técnica.** 4/5, sobretudo manutenção regulatória e integrações frágeis.

**Complexidade comercial.** 3/5; valor é claro, mas profissionais podem repassar trabalho manual ao cliente.

**Barreiras.** Responsabilidade técnica, termos claros, cobertura municipal, mudanças de formulário, documentos pessoais e LGPD.

**MVP.** Um município, um tipo de licença, checklist/versionamento/status; sem robô que protocola ou promete aprovação.

### 6.5 Orquestração de MTR/CDF para pequenas transportadoras de resíduos e consultorias ambientais

**Problema. FATO regulatório + HIPÓTESE operacional.** O MTR acompanha o transporte de resíduos sujeito ao sistema; a hipótese é que consultorias, transportadores e destinadores de alto volume gastem trabalho relevante acompanhando recebimento, CDF e evidência entre clientes e sistemas.

**Usuário e comprador.** Usuários: analista da consultoria ambiental, administrativo do transportador/destinador e gestor de unidade. Comprador: sócio da consultoria, gerente ambiental ou diretor operacional.

**Processo atual. FATO + HIPÓTESE a validar.** A emissão oficial ocorre no SINIR ou nos sistemas próprios de sete estados listados no serviço federal; o uso adicional de planilhas, e-mails e PDFs não foi quantificado. A emissão oficial gratuita limita WTP pelo ato básico ([MTR, serviço federal](https://www.gov.br/pt-br/servicos/obter-o-documento-manifesto-de-transporte-de-residuos-mtr?id=2458&origem=servico); [SINIR/MTR](https://mtr.sinir.gov.br/)).

**Intensidade/frequência. HIPÓTESE a validar.** Pode ser alta em operadores com 100+ manifestos/mês e baixa em geradores ocasionais; o corte de 100 é premissa de ICP, não estatística setorial.

**Solução.** Camada de controle multiunidade: agenda, validação, conciliação MTR–CDF–nota/peso, alertas e dossiê.

**Funções mínimas.** Cadastro de unidade/resíduo/destino; importação; status; pendência; vencimento; conciliação; evidência; relatórios; papéis.

**Concorrentes EUA.** Encamp, Wastebits e AMCS oferecem software ambiental/resíduos. São analogias de workflow; regimes não são transferíveis.

**Concorrentes Brasil.** Vertown, Ambisis, SINIR e sistemas estaduais ([Vertown](https://www.vertown.com/produtos/); [Ambisis](https://ambisis.com.br/solucoes/)).

**Brecha.** Reconciliação para consultorias e operadores com 100+ manifestos/mês, múltiplos CNPJs/unidades ou mais de um estado; não substituir os portais.

**Monetização.** HIPÓTESE: R$699/mês como preço de teste, com faixas de R$1.499–2.500 por CNPJ, unidade ou volume de manifestos; anual com dois meses de desconto.

**Ticket potencial.** Médio no plano de R$699–1.499 e alto em redes/consultorias acima de R$1.500.

**Retenção. HIPÓTESE.** Pode ser alta se histórico, pendências e dossiês forem usados em toda remessa; não há churn comparável observado.

**Switching cost. HIPÓTESE.** Pode tornar-se médio-alto por cadastros e histórico, mas portais gratuitos e exportação reduzem lock-in; mudanças de API/portal afetam confiabilidade.

**GTM.** Consultorias ambientais como canal, transportadoras/destinadores com 100+ manifestos/mês, operações multiunidade/multiestado, SEO regulatório e demonstração de reconciliação.

**Complexidade técnica.** 3/5; sobe com automação de portais sem API.

**Complexidade comercial.** 3/5; comprador entende risco, mas compara com planilha/gratuito.

**Barreiras.** Legislação ambiental federativa, credenciais de portal, segurança e responsabilidade pela classificação.

**MVP.** Receber/importar XML, PDF ou CSV, reconciliar MTR→recebimento→CDF, listar pendências e gerar dossiê; não emitir ou assinar em nome do cliente no v1.

### 6.6 Prevenção de glosas TISS

**Problema.** Clínicas podem enviar contas com campos, códigos, autorizações ou anexos inconsistentes; quando isso resulta em glosa, há retrabalho e possível atraso de caixa. Esta pesquisa não mediu a prevalência ou o valor das glosas por perfil de clínica.

**Usuário e comprador.** Faturista, recepção, auditor interno; comprador: dono, diretor financeiro ou gestor de receita da clínica.

**Processo atual. HIPÓTESE a validar.** Regras em planilhas/memória, conferência manual, portal da operadora, software clínico/faturamento e recurso posterior; a composição varia por operadora e clínica.

**Intensidade/frequência. HIPÓTESE a validar.** Pode ser alta nos prestadores com volume e glosa relevantes, mas frequência e impacto financeiro não foram quantificados nesta pesquisa.

**Solução.** Validador pré-envio que cruza TISS, regras configuradas por operadora, histórico de glosas e documentos, explicando pendências antes do envio.

**Funções mínimas.** Importação XML/CSV; regras versionadas; checklist por operadora; detecção de ausência/inconsistência; fila de correção; log; relatório de valor em risco.

**Concorrentes EUA.** Waystar, Tebra e Experian Health são análogos em revenue cycle/claims; padrões americanos não se copiam.

**Concorrentes Brasil.** iClinic, Feegow, MV/TOTVS e ferramentas especializadas de faturamento.

**Brecha.** Foco exclusivo no “pré-flight” de pequenas/médias clínicas, integração leve por arquivo e aprendizado com motivos locais de glosa.

**Monetização.** HIPÓTESE: R$699/mês até certo volume; R$1.499–5.000 por volume/operadora; possível success fee exige cuidado. Ticket médio-alto.

**Ticket potencial.** Médio em clínicas pequenas e alto em maior volume/múltiplas operadoras.

**Retenção. HIPÓTESE.** Pode ser alta se redução de glosa for demonstrada e regras permanecerem atualizadas; caso contrário, a ferramenta vira auditoria pontual.

**Switching cost. HIPÓTESE.** Pode ser médio, derivado de regras, histórico e integração; não foi observado diretamente.

**GTM.** BPOs de faturamento, consultorias, associações de clínicas, auditoria retrospectiva gratuita e piloto por especialidade.

**Complexidade técnica.** 5/5: padrões, regras, qualidade de dados e mensuração causal.

**Complexidade comercial.** 5/5: confiança, integração e acesso a dados financeiros/sensíveis.

**Barreiras.** Padrão TISS versionado pela ANS, LGPD e segurança de dados de saúde ([ANS, TISS julho de 2025](https://www.gov.br/ans/pt-br/assuntos/prestadores/padrao-para-troca-de-informacao-de-saude-suplementar-2013-tiss/padrao-tiss-julho-2025)).

**MVP.** Uma especialidade, duas operadoras e importação de lote; regras determinísticas + revisão humana; sem envio automático nem garantia de pagamento.

### 6.7 Operação de empresas de segurança contra incêndio

**Problema. HIPÓTESE a validar.** Prestadoras podem precisar coordenar inventário de equipamentos, inspeção/manutenção, evidência de serviço e renovação; esta pesquisa não mediu a fragmentação nem o custo atual.

**Usuário e comprador.** Técnico de campo, planejador e administrativo; comprador: dono/gerente da prestadora.

**Processo atual. HIPÓTESE a validar.** Planilha, etiquetas, agenda, WhatsApp, ordem em papel e software genérico são substitutos plausíveis, sem prevalência medida.

**Intensidade/frequência. HIPÓTESE a validar.** Pode ser alta e recorrente conforme parque de ativos e contratos, mas volume e disposição a pagar não foram medidos.

**Solução.** CRM operacional por ativo/local, com rota, inspeção móvel, evidência e renovação.

**Funções mínimas.** Cliente/local/ativo; QR code; agenda; checklist; foto/assinatura; laudo; validade; orçamento/renovação; offline básico.

**Concorrentes EUA.** Inspect Point, ServiceTrade e BuildingReports demonstram a vertical.

**Concorrentes Brasil.** ExtinRadar, Varkon, Protecin e ExtintorWeb. ExtinRadar publica preços, tornando inviável presumir espaço para cobrar prêmio sem diferenciação ([ExtinRadar, preços](https://www.extinradar.com.br/precos); [Varkon](https://varkon.com.br/sistema-para-empresa-de-extintores/); [Protecin](https://protecin.com.br/nosso-app/)).

**Brecha.** Aplicativo de campo realmente simples/offline e geração de evidência/renovação, com implantação rápida e migração de planilha.

**Monetização.** HIPÓTESE: R$199 solo, R$499 equipe, R$999–1.499 multiunidade; por técnico/ativo; anual com desconto. Ticket baixo/médio.

**Ticket potencial.** Baixo no plano solo e médio nos planos de equipe/multiunidade.

**Retenção. HIPÓTESE.** Pode ser alta pelo cadastro de ativos e calendário, desde que o app seja usado no campo.

**Switching cost. HIPÓTESE.** Pode tornar-se médio-alto por histórico, etiquetas e recorrências; migração simples pode reduzi-lo.

**GTM.** Outbound local, distribuidores de equipamentos, contadores do nicho, SEO e migração gratuita.

**Complexidade técnica.** 2/5 no núcleo; offline e impressão elevam.

**Complexidade comercial.** 3/5, mercado pulverizado e sensível a preço.

**Barreiras.** Normas técnicas, regras estaduais dos Bombeiros e risco de documento incorreto.

**MVP.** Cadastro/importação, agenda, checklist, foto/assinatura, validade e PDF.

### 6.8 Compliance e manutenção para pequenas frotas

**Problema. HIPÓTESE a validar.** Parte das frotas de 5–50 veículos pode perder prazos ou não consolidar inspeções, custos e disponibilidade; a concorrência madura indica que isso não é universalmente mal atendido.

**Usuário e comprador.** Motorista, assistente e gestor; comprador: dono ou operações.

**Processo atual. HIPÓTESE a validar.** Planilha, grupos, oficina, calendário e rastreamento sem módulo de manutenção são substitutos plausíveis; não há prevalência medida para o subnicho.

**Intensidade/frequência. HIPÓTESE a validar.** Pode ser diária/semanal em frota ativa, mas o problema que justifica software separado precisa ser demonstrado por subnicho.

**Solução.** Inspeção móvel, calendário por uso/tempo, documentos e visão de custo/indisponibilidade.

**Funções mínimas.** Veículo/motorista; odômetro; checklist; foto; manutenção; validade; alertas; custo; exportação.

**Concorrentes EUA.** Fleetio, AUTOsist e Whip Around. Fleetio publica preço em diretórios e realizou captação/aquisição, sinalizando categoria madura ([Fleetio/Capterra, preços](https://www.capterra.com/p/120855/Fleetio/pricing/); [Fleetio, Série D/aquisição](https://www.fleetio.com/resources/press/fleetio-raises-series-d-and-acquires-auto-integrate)).

**Concorrentes Brasil.** Prolog, TOTVS/NG e Drivvo. Prolog informa casos em operações robustas, e TOTVS já ocupa contas ([Prolog](https://www.prologapp.com/cases-de-sucesso/); [TOTVS](https://www.totvs.com/totvs-gestao-de-frotas/)).

**Brecha.** Só existe se o nicho for estreito: por exemplo, vans escolares, prestadoras de campo ou locadoras pequenas, com documentos e checklist próprios.

**Monetização.** HIPÓTESE: R$199 base + R$10–25/veículo; R$499–1.500 por empresa; anual. Ticket baixo/médio.

**Ticket potencial.** Baixo na entrada e médio para a frota-alvo; alto apenas em contas fora do ICP inicial.

**Retenção. HIPÓTESE.** Pode ser alta quando manutenção e histórico ficam no sistema; a categoria madura também facilita comparação e troca.

**Switching cost. HIPÓTESE.** Pode ser médio-alto pelo histórico; exportação e integração reduzem lock-in artificial.

**GTM.** Associações do subnicho, oficinas, seguradoras/corretoras, conteúdo de custo por km e outbound regional.

**Complexidade técnica.** 3/5.

**Complexidade comercial.** 3/5; competição intensa pressiona CAC/preço.

**Barreiras.** LGPD/geolocalização, documentos e, conforme segmento, ANTT; não incluir telemetria no MVP.

**MVP.** Checklist, manutenção e vencimentos para um subnicho, sem rastreamento em tempo real.

### 6.9 Workflow ISO 17025 e calibração

**Problema. FATO contextual + HIPÓTESE operacional.** A acreditação exige controle e rastreabilidade; a hipótese é que laboratórios pequenos ainda sofram com padrões, instrumentos, certificados, métodos e vencimentos em ferramentas fragmentadas.

**Usuário e comprador.** Metrologista, qualidade, técnico e atendimento; comprador: gerente da qualidade ou dono do laboratório.

**Processo atual. INFERÊNCIA a validar.** Planilhas, templates Word/PDF, software legado e arquivos compartilhados são plausíveis. A SISMETRO posiciona importação/migração de controles em Excel, sinal de fornecedor de que planilhas existem, sem indicar prevalência ([SISMETRO](https://www.sismetro.com/versao/smart/handling)).

**Intensidade/frequência. HIPÓTESE a validar.** Pode ser diária em laboratório ativo, mas volume, retrabalho e WTP não foram medidos.

**Solução.** Fluxo do recebimento ao certificado, com rastreabilidade de padrão/método, revisão e calendário.

**Funções mínimas.** Cliente/instrumento; ordem; método; padrão usado; cálculos parametrizados; revisão; certificado; validade; trilha; permissões.

**Concorrentes EUA.** Qualer, IndySoft e GAGEtrak.

**Concorrentes Brasil.** Presys ISOPLAN, Metrosys e SISMETRO ([Presys](https://presys.com.br/software-de-calibracao/); [Metrosys](https://metrosys.com.br/); [SISMETRO](https://www.sismetro.com/versao/smart/handling)).

**Brecha.** SaaS moderno para laboratórios pequenos, migração assistida e portal do cliente; evitar customização metrológica ilimitada.

**Monetização.** HIPÓTESE: R$499–999/mês básico; R$1.500–2.500 com múltiplas grandezas/usuários; implantação paga. Ticket médio/alto.

**Ticket potencial.** Médio no básico e alto em múltiplas grandezas/usuários.

**Retenção. HIPÓTESE.** Pode ser alta se o sistema sustentar operação e auditoria; não há coorte pública comparável.

**Switching cost. INFERÊNCIA.** Tende a crescer com templates, métodos, histórico e certificados, mas não foi medido.

**GTM.** Lista de laboratórios acreditados, consultores ISO 17025, associações, webinars técnicos e migração de uma grandeza.

**Complexidade técnica.** 4/5 por cálculos, versionamento e documentos.

**Complexidade comercial.** 4/5; confiança e validação técnica prolongam venda.

**Barreiras.** Acreditação Cgcre/Inmetro, integridade de registro, assinatura e responsabilidade. O Inmetro mantém lista de organismos/laboratórios acreditados e relatório de gestão, base útil para segmentação sem presumir que todos comprarão ([Inmetro, acreditados](https://www.gov.br/inmetro/pt-br/assuntos/acreditacao-reconhecimento-bpl/organismos-acreditados); [Relatório de Gestão 2025](https://www.gov.br/inmetro/pt-br/acesso-a-informacao/auditorias/prestacao-de-contas/prestacao-de-contas-2025/relatorio-de-gestao-do-inmetro-2025)).

**MVP.** Uma grandeza, ordem, padrão/método, revisão e certificado; sem LIMS genérico.

### 6.10 Operação de home care

**Problema. HIPÓTESE a validar.** Operadores podem enfrentar fricção ao escalar profissionais, registrar visitas/procedimentos, comunicar intercorrências e preparar faturamento; o workflow específico e sua severidade não foram medidos. Dados de saúde são sensíveis.

**Usuário e comprador.** Coordenador de escala, enfermagem, cuidador e faturista; comprador: diretor de operação/assistencial.

**Processo atual. HIPÓTESE a validar.** WhatsApp, telefone, planilha, papel e sistemas separados são substitutos plausíveis, sem pesquisa direta de prevalência nesta análise.

**Intensidade/frequência. HIPÓTESE a validar.** O workflow pode ser contínuo e uma falha operacional pode afetar a prestação do cuidado, mas frequência, severidade e WTP não foram medidos.

**Solução.** Operação centrada no episódio domiciliar, com escala, check-in, plano, evidência e preparação de faturamento.

**Funções mínimas.** Paciente/equipe; escala; disponibilidade; check-in; tarefas; ocorrência; anexos; assinatura; exportação de faturamento; auditoria.

**Concorrentes EUA.** AlayaCare, WellSky e AxisCare têm suites maduras de home care.

**Concorrentes Brasil.** LonVi, Kuida e Hope Solution confirmam oferta local ([LonVi](https://www.lonvi.com.br/); [Kuida](https://kuida.app.br/); [Hope Solution](https://www.hopesolution.com.br/)).

**Brecha.** Uma operação pequena/média com implantação rápida e um subsegmento claro, como transição hospitalar ou cuidadores; não construir prontuário completo no início.

**Monetização.** HIPÓTESE: R$1.000–6.000/mês por empresa, com faixa escalonada por pacientes ativos/profissionais, mais implantação. Ticket médio/alto.

**Ticket potencial.** Médio na entrada e alto a partir de R$1.500/mês.

**Retenção. HIPÓTESE.** Pode ser alta quando escala, histórico e faturamento convergem; implantação e qualidade de suporte podem produzir o efeito oposto.

**Switching cost. HIPÓTESE.** Pode ser alto por histórico e integrações, embora portabilidade de dados deva ser garantida.

**GTM.** Parcerias hospitalares/BPO, associações, venda consultiva e piloto em uma equipe/região.

**Complexidade técnica.** 5/5: disponibilidade, mobile/offline, integrações e segurança.

**Complexidade comercial.** 5/5: ciclo longo, confiança clínica e implantação.

**Barreiras.** LGPD/dados de saúde, controles de acesso, prontuário, responsabilidade assistencial e TISS conforme modelo.

**MVP.** Escala, confirmação de visita, checklist/evidência e exportação; sem prescrição, decisão clínica ou billing completo.

## 7. Deep dive 1 — Conformidade de terceiros e SST por obra

### 7.1 Mercado e tese de entrada

**FATO.** A PAIC 2024 contabilizou aproximadamente 191 mil empresas de construção, 2,5 milhões de pessoas ocupadas e R$522,5 bilhões em valor de incorporações, obras e/ou serviços. Esses números descrevem o setor formal coberto pela pesquisa; não significam 191 mil compradores do produto ([IBGE, PAIC 2024, divulgação de 10 jun. 2026](https://agenciadenoticias.ibge.gov.br/agencia-detalhe-de-midia.html?catid=2102&id=8872&view=mediaibge)). A pesquisa de maturidade digital da CBIC, com 130 participantes, classificou 70% como tradicionais ou iniciantes. A amostra é pequena frente ao universo e pode ter viés de seleção, mas sustenta oportunidade de digitalização ([CBIC, 5 dez. 2025](https://cbic.org.br/pesquisa-nacional-traca-panorama-inedito-da-maturidade-digital-na-construcao/)).

**Problema-alvo — HIPÓTESE operacional.** O produto não tenta digitalizar toda a obra. Ele responde à decisão: **esta empresa e esta pessoa podem entrar/permanecer nesta obra hoje?** O valor proposto é reduzir paralisações/retrabalho e deixar evidência; a frequência e a economia ainda precisam ser medidas. Cada obra pode ter requisitos gerais, contratuais e por função.

**Tendência.** A construção brasileira combina grande base econômica com maturidade digital desigual; nos EUA, Avetta, Billy e myComply mostram que contractor compliance/onboarding é categoria comprável. Isso é uma triangulação, não prova de que o mesmo preço ou produto servirá ao Brasil.

### 7.2 Universo teórico de receita e cenários de sensibilidade

Preço de referência de sizing: **R$499/mês por empresa**. É uma **ESTIMATIVA**, usada para comparar potencial e não uma previsão de receita.

- **Universo teórico de receita:** `191.000 empresas × R$499 × 12 = R$1.143.708.000`, arredondado para **R$1,144 bilhão de ARR**. Não é TAM observado: superestima o mercado porque nem toda empresa gerencia terceiros, possui múltiplas obras, tem orçamento ou compraria software separado.
- **Cenário de sensibilidade com 5%–15% do universo:** **9.550 a 28.650 empresas**, uma premissa e não um SAM medido. Receita anual: `9.550 × 499 × 12 = R$57.185.400`; `28.650 × 499 × 12 = R$171.556.200`, portanto **R$57,2 milhões a R$171,6 milhões de ARR**.
- **Cenário operacional em 36 meses:** **100 a 250 clientes**, uma meta hipotética de execução, não SOM derivado de market share observado. Receita anual: `100 × 499 × 12 = R$598.800`; `250 × 499 × 12 = R$1.497.000`, isto é, **R$0,60 milhão a R$1,50 milhão de ARR**.

Nenhuma dessas faixas incorpora implantação, excedentes ou desconto anual. O maior erro potencial está na taxa de 5%–15%; entrevistas e bases de obras ativas devem refiná-la.

### 7.3 Players e posicionamento

Nos EUA, Avetta é plataforma abrangente de qualificação de fornecedores; Billy enfatiza construção/seguro e compliance; myComply trabalha onboarding e controle de trabalhador. No Brasil, RoCost, GEOB, DocSafe, SegWork e Inspeseg já cobrem partes do problema; Sienge/Mobuss possuem distribuição e dados adjacentes. Portanto, a defesa não pode ser “somos o primeiro”. Deve ser:

1. implantação em horas/dias, não projeto;
2. experiência sem login complexo para terceirizada;
3. gate por pessoa/função/obra em vez de repositório genérico;
4. explicação da pendência e trilha imutável;
5. integração/exportação para o stack existente.

A principal ameaça é um incumbente adicionar um checklist semelhante e distribuí-lo à base. O moat precisa vir do conjunto de templates, velocidade de configuração, dados de causas de bloqueio, rede de terceirizadas reutilizáveis e integrações — não de OCR isolado.

### 7.4 Cliente, comportamento e disposição a pagar

**ICP.** Construtora/empreiteira com 50–500 trabalhadores próprios e terceiros, duas a dez obras simultâneas, responsável de SST/documentação identificável e entrada recorrente de subcontratados. Evitar no início a microempresa com uma obra esporádica e a grande incorporadora que exige integração enterprise.

**Persona.** Analista administrativo ou técnico de SST que recebe arquivos, confere validade, cobra reenvio e responde à obra/portaria. Sua dor é operacional: não saber rapidamente quem está liberado e ser responsabilizado por falha de registro.

**Buyer.** Gerente de SST, engenharia ou operações; em empresas menores, sócio/diretor. O buyer compra redução de atraso e evidência, não “gestão de documentos”.

**Mensagem de venda.**

> Ajudamos construtoras com equipes terceirizadas a liberar apenas quem está documentalmente apto e provar cada decisão, sem planilhas, cobranças manuais e pastas espalhadas por obra.

**Disposição a pagar — HIPÓTESE.** R$299–1.499/mês é plausível se um bloqueio evitado ou horas administrativas poupadas excederem a mensalidade. Precisa ser validado com escolha real, não pergunta abstrata. Oferecer piloto pago revela WTP melhor do que “você usaria?”.

### 7.5 Unit economics hipotéticos

Premissas não observadas em empresas comparáveis:

- margem bruta de 85%, possível se onboarding e revisão documental não virarem serviço humano permanente;
- churn mensal de 2%–4%; vida média simplificada de 25–50 meses;
- LTV bruto simplificado: `R$499 × 85% ÷ churn`, resultando em **R$10,6 mil** a 4% e **R$21,2 mil** a 2%; não considera expansão, desconto ou custo de capital;
- CAC de **R$1,5 mil–R$4 mil**, incluindo prospecção, venda e onboarding;
- payback em margem bruta: `CAC ÷ (499 × 85%)`, de **3,5 a 9,4 meses**.

São **HIPÓTESES de planejamento**. Se cada conta consumir consultoria, o COGS sobe, a margem cai e o payback se alonga. Se a obra encerrar e não houver nova, churn pode superar 4%.

### 7.6 Canais e primeiros clientes

**Canais prioritários.** Outbound por obra ativa, consultorias de SST, fornecedores de medicina ocupacional, contadores/administradores da construção, associações regionais e conteúdo sobre mobilização. Google Ads amplo tende a atrair busca por documento/curso e pode ter baixa intenção de SaaS.

**Primeiros 10 clientes — passo a passo.**

1. Selecionar duas cidades e montar lista de 80 empresas com obras ativas, evitando enterprise.
2. Realizar 20 entrevistas de 30–45 minutos, pedindo demonstração do fluxo real e amostras anonimizadas.
3. Mapear top 10 documentos, papéis, exceções e tempo de liberação; não começar por legislação enciclopédica.
4. Criar protótipo navegável e executar concierge em planilha/banco simples para uma obra.
5. Propor piloto de 30–45 dias, pago, com limite de 50 vidas e definição de sucesso: tempo para conferir, pendências antes da chegada e dossiê gerado.
6. Fechar cinco pilotos diretamente e cinco por duas consultorias SST.
7. Fazer revisão semanal; aceitar parametrização reutilizável e recusar customização exclusiva que quebre o produto.
8. Converter apenas se usuário e gerente confirmarem valor e uso semanal.

**Primeiros 100 clientes.**

1. Transformar as implantações iniciais em dois templates por perfil de obra.
2. Publicar dois casos com métricas auditáveis e consentidas — tempo de mobilização e taxa de pendência detectada, sem prometer redução de acidente.
3. Criar canal parceiro com consultorias: treinamento, ambiente multiempresa e comissão recorrente limitada.
4. Montar outbound de três sinais: obra nova, contratação de SST/documentação e múltiplos CNPJs/filiais.
5. Oferecer importação padronizada e onboarding em sete dias como promessa operacional.
6. Implantar referral entre terceirizadas que trabalham em diversas construtoras, respeitando segregação de dados.
7. Medir por canal: reunião/lista, piloto/reunião, conversão, CAC, tempo de ativação e churn por fim de obra.

### 7.7 Produto, IA, expansão e moat

**MVP.** Upload por link/WhatsApp; checklist por obra, empresa e colaborador; validade; fila de aprovação/bloqueio; alertas; dossiê PDF; log. A decisão final é humana.

**IA útil.** OCR e classificação; extração de nome/CPF/data; comparação com cadastro; detecção de ilegibilidade; resumo do motivo de pendência; sugestão de checklist. Toda extração deve exibir campo original, confiança e auditoria. IA generativa não decide aptidão legal.

**Expansão possível.** Reuso de identidade documental da terceirizada entre obras; integração com catraca/controle de acesso; onboarding de fornecedor; seguros/certidões; eSocial; medição/contrato; analytics de tempo de mobilização. A ordem importa: ampliar apenas após o gate documental ter uso e retenção.

**Moat potencial.** Templates por tipo de obra/função, histórico de quais documentos geram rejeição, integração com prestadores, rede de terceirizadas e qualidade do onboarding. Dados só podem ser reutilizados com base legal, finalidade e segregação adequadas.

### 7.8 Riscos e barreiras

- **Concorrentes baratos:** Extensões e sistemas locais podem resolver 80% por preço menor.
- **Incumbentes:** Sienge/Mobuss ou SST podem copiar e distribuir.
- **Baixo WTP:** empresas podem aceitar risco e custo administrativo.
- **Customização:** cada contratante pode exigir regra distinta, transformando SaaS em consultoria.
- **Campo:** terceirizada pode continuar enviando foto ruim e ignorar portal.
- **Responsabilidade:** usuário pode tratar status do sistema como parecer jurídico.
- **Ciclicidade:** fim/atraso de obras eleva churn.
- **Privacidade:** documentos trabalhistas e de saúde exigem minimização, acesso granular, retenção e resposta a incidente; a agenda regulatória da ANPD é contexto de mudança contínua ([ANPD, 2025–2026](https://www.gov.br/anpd/pt-br/assuntos/noticias/anpd-publica-agenda-regulatoria-2025-2026)).

## 8. Deep dive 2 — Portal contábil de coleta e fechamento

### 8.1 Mercado e tese de entrada

**FATO.** A consulta do CFC registrava 105.893 organizações contábeis e 547.790 profissionais no recorte usado nesta pesquisa. A página é dinâmica; os valores devem ser rechecados na data de qualquer decisão de investimento ([CFC, consulta de registros ativos](https://www3.cfc.org.br/spw/crcs/ConselhoRegionalAtivo.aspx?P1=&P2=&P3=&P4=&P5=1&P6=)). A reforma tributária do consumo tem orientações operacionais específicas para 2026 e amplia demanda informacional, mas também aumenta risco de escopo ([Receita Federal, orientações 2026](https://www.gov.br/receitafederal/pt-br/acesso-a-informacao/acoes-e-programas/programas-e-atividades/reforma-tributaria-do-consumo/orientacoes-2026)).

O produto proposto não calcula imposto. Ele fecha o “last mile” entre escritório e cliente: pedir, receber, reconhecer, cobrar o que falta e provar quando chegou. A universalização/adesão municipal à NFS-e pode reduzir alguns documentos manuais, evidência desconfirmatória importante; o valor deve migrar para exceções e consolidação, não depender de anexos eternamente ([Portal NFS-e, municípios aderentes](https://www.gov.br/nfse/pt-br/municipios/monitoramento-adesoes/municipios-aderentes)).

### 8.2 Universo teórico de receita e cenários de sensibilidade

Preço de sizing: **R$399/mês por organização contábil**.

- **Universo teórico de receita:** `105.893 × R$399 × 12 = R$507.015.684`, arredondado para **R$507,0 milhões de ARR**. Não é TAM observado: inclui organizações inativas operacionalmente, muito pequenas, já atendidas e sem WTP.
- **Cenário de sensibilidade com 10%–25% do universo:** **10.589 a 26.473 organizações**, premissa e não SAM medido. Receita: `10.589 × 399 × 12 = R$50.700.132`; `26.473 × 399 × 12 = R$126.752.724`, portanto **R$50,7 milhões–R$126,8 milhões**.
- **Cenário operacional em 36 meses:** **150–400 clientes**, meta hipotética, não SOM observado; receita `150 × 399 × 12 = R$718.200` a `400 × 399 × 12 = R$1.915.200`, ou **R$0,72–1,92 milhão de ARR**.

As faixas excluem excedentes por CNPJ, implantação e desconto. O preço efetivo pode ser inferior se concorrentes empacotarem a função.

### 8.3 Players, comportamento e WTP

Financial Cents, Karbon e Canopy mostram workflow contábil como produto nos EUA. A página de preços usada está parametrizada em **CAD (dólar canadense)** e serve apenas como evidência de cobrança recorrente, não como referência cambial para o Brasil ([Financial Cents, pricing em CAD](https://financial-cents.com/pricing/?currency=cad)). No Brasil, Acessórias e GuiaFlow atacam comunicação/rotina; Domínio e Questor/Tareffa ocupam o stack; Omie se conecta ao cliente final. A sondagem da Omie oferece contexto sobre escritórios/PMEs, mas é material de fornecedor e não dimensiona esta oportunidade ([Omie, sondagem 2/2025](https://www.omie.com.br/sondagem/e-book_report_sondagem_Omie_2_2025.pdf)).

**ICP.** Escritório com 5–30 colaboradores e 80–500 CNPJs clientes, carteira pulverizada, diferentes regimes, fechamento ainda coordenado por mensagens e sem portal bem adotado.

**Persona.** Assistente que passa parte relevante da semana cobrando anexos, renomeando arquivo e respondendo “já enviei”.

**Buyer.** Sócio ou gerente operacional que deseja aumentar carteiras por colaborador e reduzir horas extras/retrabalho.

**Mensagem de venda.**

> Ajudamos escritórios contábeis a fechar cada competência com todos os documentos certos, sem caçar anexos em conversas, e-mails e pastas de cada cliente.

**WTP — HIPÓTESE.** R$399/mês precisa economizar poucas horas de equipe ou evitar um atraso relevante. Porém, o mercado é sensível a preço e já paga ERP; a objeção “deveria estar incluído” será frequente. A venda deve quantificar carteira por assistente e tempo de cobrança.

### 8.4 Unit economics hipotéticos

- margem bruta: **85%**, condicionada a OCR e suporte escaláveis;
- churn mensal: **2%–4%**;
- LTV bruto simplificado: `399 × 85% ÷ churn` = **R$8,5 mil–R$17,0 mil**;
- CAC: **R$500–1.500**, possível com comunidade/parceiro e inside sales;
- payback: `CAC ÷ (399 × 85%)` = **1,5–4,4 meses**.

Tudo é **HIPÓTESE**. Integrações customizadas podem elevar CAC e COGS; churn pode ser maior em escritórios pequenos; expansão por CNPJ pode elevar LTV.

### 8.5 Produto, aquisição e retenção

**MVP.** Checklist mensal por cliente; inbox via link/WhatsApp; OCR/classificação assistida; lista de pendências; trilha; exportação. Sem motor fiscal/ERP.

**IA útil.** Identificar CNPJ, competência, emissor e tipo; sugerir a pasta/tarefa; detectar duplicata; resumir o que falta; gerar mensagem personalizada. Revisão humana é obrigatória para documento ambíguo.

**Retenção/moat.** Templates por perfil, histórico de entrega do cliente, regras de classificação e conectores. O moat é fraco se o software apenas envia lembretes; melhora quando reduz trabalho real e produz painel confiável de fechamento.

**Riscos.** Concorrência já intensa; ERPs embutirem função; automação da NFS-e reduzir coleta; bloqueios/custo do WhatsApp; dados fiscais sensíveis; cliente final não aderir; OCR errar; suporte consumir margem.

**Expansão.** Portal de solicitações, assinatura, aprovação de guias, SLA interno, capacity planning, cobrança e integração bancária/Pix Automático. O Banco Central lançou Pix Automático como infraestrutura de cobranças recorrentes, mas sua adoção específica deve ser validada ([Banco Central, Pix Automático](https://www.bcb.gov.br/detalhenoticia/20713/noticia)).

### 8.6 Primeiros 10 e 100 clientes

**Primeiros 10.**

1. Entrevistar 20 escritórios de duas comunidades/ERPs diferentes.
2. Pedir tela compartilhada de um fechamento real e medir mensagens, reenvios e tempo.
3. Rodar concierge em 10 CNPJs de cinco escritórios, com checklist e inbox simples.
4. Cobrar R$199–399 pelo piloto; rejeitar “gratuito até ficar perfeito”.
5. Integrar inicialmente por exportação, sem aguardar API de todos os ERPs.
6. Converter os cinco melhores e conseguir cinco via contadores/consultores parceiros.
7. Medir ativação: primeiro checklist enviado, primeiro documento classificado e competência fechada.

**Primeiros 100.**

1. Produto self-assisted com importação de clientes por planilha e templates.
2. Programa de parceiros de implantação de Domínio/Questor/Omie.
3. Conteúdo/SEO sobre checklist mensal e transição da reforma, sem aconselhamento tributário.
4. Webinars com caso real e calculadora de horas de cobrança.
5. Referral: um mês de crédito por escritório indicado e ativado.
6. Inside sales por faixa de carteira; evitar vender para microescritório de baixa ACV com reunião longa.
7. Comparar CAC, churn e expansão por canal e porte.

## 9. Deep dive 3 — Orquestração de MTR/CDF para pequenas transportadoras de resíduos e consultorias ambientais

### 9.1 Mercado, regulação e limite do sizing

**FATO.** O Manifesto de Transporte de Resíduos deve acompanhar cada transporte sujeito ao sistema, e o serviço oficial informa que sete estados mantêm sistemas próprios em vez de operar diretamente no MTR nacional. Isso cria fragmentação observável de interface e jurisdição, mas não prova que usuários façam conciliação manual ou que pagariam por um agregador ([serviço oficial MTR](https://www.gov.br/pt-br/servicos/obter-o-documento-manifesto-de-transporte-de-residuos-mtr?id=2458&origem=servico); [portal SINIR/MTR](https://mtr.sinir.gov.br/)).

**FATO, âncora local não extrapolável.** Relatório gerencial da FEPAM registrou **146.681 geradores** no Rio Grande do Sul em fevereiro de 2025. “Gerador” não equivale a cliente potencial, operação ativa de alto volume ou conta pagante; o dado não deve ser extrapolado para o Brasil ([FEPAM, relatório gerencial mensal, fev. 2025](https://www.fepam.rs.gov.br/upload/arquivos/202509/23155900-relatoriogerencialmensal-fev-2025-1.pdf)).

**Insuficiência de dados.** Não foi encontrada, no material reunido, uma contagem nacional confiável de consultorias, transportadoras/destinadores com 100+ manifestos mensais, unidades multiestado ou organizações que hoje conciliam MTR→recebimento→CDF manualmente. Por isso, este relatório **não calcula TAM, SAM ou SOM monetário para MTR/CDF**. O preço de **R$699/mês** é apenas **HIPÓTESE de sizing e teste de WTP**, não base para dimensionar mercado.

### 9.2 Tese de entrada, players e comportamento

O produto não compete com o portal gratuito nem emite formulário em nome do cliente no v1. O wedge é reconciliar cada transporte: MTR criado, resíduo recebido, divergência resolvida, CDF associado e dossiê disponível. Encamp, Wastebits e AMCS são análogos americanos de compliance/operação de resíduos; os regimes não são portáteis. No Brasil, Vertown e Ambisis já oferecem soluções ambientais, enquanto SINIR/sistemas estaduais são substitutos públicos ([Vertown](https://www.vertown.com/produtos/); [Ambisis](https://ambisis.com.br/solucoes/)).

**Tendência — INFERÊNCIA.** Obrigação por transporte e sete sistemas estaduais criam um workflow repetitivo em operadores de volume, mas a intensidade, manualidade e disposição a pagar precisam ser observadas em tela compartilhada.

**Comportamento/WTP — HIPÓTESE.** Uma consultoria ou operador pode pagar R$699/mês se reduzir conferência, localizar pendências antes do fechamento e produzir dossiê multi-CNPJ/multiestado. O portal gratuito ancora preço em zero para emissão; portanto, ninguém deve ser entrevistado com a proposta vaga de “software para MTR”. O teste é pagar pela reconciliação e evidência.

### 9.3 ICP, persona, buyer e mensagem

**ICP.** Consultoria ambiental ou transportadora/destinador que opere **100+ manifestos por mês**, múltiplos clientes/unidades ou mais de um estado. O corte de 100 é hipótese de segmentação, não estatística.

**Persona.** Analista ambiental/operacional que baixa arquivos, confere status/quantidades, cobra recebimento ou CDF e monta evidência para cliente/auditoria.

**Buyer.** Sócio da consultoria, gerente ambiental, diretor operacional ou responsável de compliance que controla várias contas/unidades.

**Mensagem de venda.**

> Ajudamos consultorias e operadores de resíduos a fechar cada transporte com MTR, recebimento e CDF reconciliados, sem conferir portais e planilhas manualmente.

### 9.4 Unit economics hipotéticos

Com preço de referência de R$699/mês:

- margem bruta: **85%**, desde que a equipe do SaaS não opere portais pelo cliente;
- churn mensal por conta: **1,5%–3%**;
- LTV bruto simplificado: `699 × 85% ÷ churn` = **R$19,8 mil–R$39,6 mil**;
- CAC: **R$1,5 mil–R$5 mil**, via venda consultiva/parceiros;
- payback em margem bruta: `CAC ÷ (699 × 85%)` = **2,5–8,4 meses**.

Tudo é **HIPÓTESE de planejamento**. Mudança de portal, implantação multiestado, suporte documental e baixa padronização podem reduzir margem. Sem coortes, o churn e a vida útil não são fatos.

### 9.5 Produto, IA, moat, expansão e riscos

**MVP.** Importar ou receber XML/PDF/CSV; associar cliente, unidade e transporte; reconciliar MTR→recebimento→CDF; sinalizar pendência/divergência; gerar dossiê e log. No v1, não emitir, assinar ou transmitir em nome do cliente.

**IA possível.** Extração de campos de PDF/XML, sugestão de correspondência entre MTR/recebimento/CDF, detecção de divergência e explicação de pendência. Toda sugestão exige revisão; regras determinísticas cuidam de campos críticos.

**Moat potencial.** Taxonomia de documentos/estados, histórico de correspondências e divergências, conectores autorizados e ambiente multi-CNPJ para consultorias. O moat enfraquece se depender de scraping frágil ou se o portal público oferecer API e reconciliação equivalentes.

**Expansão.** Calendário de condicionantes/licenças, inventário de resíduos, dashboards de cliente, integrações com balança/ERP, relatórios multiunidade e outros documentos ambientais. Expandir apenas depois de provar reconciliação recorrente.

**Riscos e barreiras.** Governo oferece emissão gratuita; API/portal pode mudar; WTP pode ser baixo; classificação/reconciliação incorreta pode gerar responsabilidade; sete sistemas ampliam fragmentação e custo; credenciais e dados exigem segurança; Vertown/Ambisis ou consultorias podem incorporar o wedge. Automatizar navegador sem acordo pode ser operacionalmente frágil.

### 9.6 Primeiros 10 e 100 clientes

**Primeiros 10.**

1. Selecionar dois estados: um no SINIR nacional e um com sistema próprio.
2. Entrevistar 15 consultorias e 15 transportadoras/destinadores, exigindo demonstração de um fechamento real.
3. Medir manifestos/mês, tempo de conferência, tipos de arquivo, taxa de pendência e prazo até CDF.
4. Rodar concierge apenas com arquivos exportados, sem credencial do portal e sem emissão.
5. Conseguir cinco pilotos em consultorias, que oferecem múltiplos CNPJs, e cinco em operadores de resíduos.
6. Cobrar R$699/mês ou piloto proporcional; definir sucesso por horas de conferência e pendências encontradas, não por “compliance garantido”.
7. Encerrar a tese se menos de cinco aceitarem pagar ou se exportação inexistente exigir operação manual permanente do fornecedor.

**Primeiros 100.**

1. Padronizar importadores dos dois estados iniciais e publicar matriz de arquivos suportados.
2. Criar workspace de consultoria com segregação por cliente e cobrança por volume/CNPJ.
3. Fazer parceria com consultorias ambientais, associações de resíduos e integradores de ERP/balança.
4. Produzir conteúdo por estado sobre fechamento e evidência, sem aconselhamento jurídico.
5. Publicar caso com volume, tempo antes/depois e taxa de pendência, explicitando metodologia.
6. Expandir um estado por vez, condicionado a 20 prospects qualificados e formato técnico sustentável.
7. Medir CAC, ativação no primeiro lote, percentual reconciliado sem intervenção, margem e churn por canal.

## Estimativas de custo, mercado e prazo de desenvolvimento

Todos os valores desta seção são **HIPÓTESES de planejamento em reais de setembro de 2026**, não cotações, propostas comerciais ou benchmarks observados de empresas equivalentes. Servem para definir ordem de grandeza, orçamento por gate e critérios de abandono. Não incluem custo de oportunidade dos fundadores, impostos sobre receita, capital de giro, inadimplência, financiamento ou expansão internacional.

### Premissas de equipe e custo

O build parte de uma equipe pequena e experiente, com a seguinte composição mensal hipotética:

- dois engenheiros experientes: **R$50 mil–70 mil/mês somados**;
- produto/design fracionado: **R$6 mil–12 mil/mês**;
- QA, DevOps e segurança fracionados: **R$5 mil–12 mil/mês**;
- especialista de domínio e/ou jurídico: **R$5 mil–20 mil/mês**;
- cloud e ferramentas durante desenvolvimento: **R$2 mil–15 mil/mês**;
- contingência: **20%** sobre o orçamento de construção.

Essas faixas não precisam ocorrer integralmente todos os meses: produto, especialista, QA e segurança podem entrar em momentos diferentes. O custo de **validação** cobre entrevistas, protótipo, concierge, apoio de domínio e preparação do piloto antes do compromisso com o build completo. O **piloto** é a primeira operação limitada com cliente real e pode começar como concierge ou protótipo funcional. **MVP vendável** é a menor versão pela qual um cliente pode pagar e obter o resultado central. **Produção/hardening** acrescenta observabilidade, backup, recuperação, permissões, auditoria, segurança, privacidade, suporte, documentação e confiabilidade suficientes para ampliar a base.

Os prazos da tabela são semanas decorridas desde o início e **não devem ser somados**: descoberta, piloto e construção podem se sobrepor. “Build estimado” representa o desembolso acumulado para chegar ao MVP e realizar o hardening inicial, já com contingência de 20%. “Infra/mês” isola cloud, mensageria, modelos, observabilidade e ferramentas em operação inicial. “Burn pós-MVP/mês” é o custo operacional total de uma configuração enxuta — engenharia/manutenção, produto/suporte/comercial e infraestrutura dentro da faixa — e não deve ser somado novamente à coluna de infraestrutura. A equipe pós-MVP pode diferir da equipe de build.

| Pos. | Oportunidade | Validação | Piloto utilizável | MVP vendável | Build estimado | Infra/mês | Burn pós-MVP/mês | Produção/hardening |
|---:|---|---:|---:|---:|---:|---:|---:|---:|
| 1 | Conformidade de terceiros/SST por obra | R$15 mil–35 mil | 4–6 sem. | 14–18 sem. | R$280 mil–480 mil | R$2 mil–6 mil | R$45 mil–80 mil | 20–28 sem. |
| 2 | Portal contábil de coleta/fechamento | R$10 mil–25 mil | 3–5 sem. | 12–16 sem. | R$220 mil–380 mil | R$2 mil–8 mil | R$40 mil–75 mil | 18–24 sem. |
| 3 | MTR/CDF para resíduos | R$20 mil–45 mil | 4–8 sem. | 16–22 sem. | R$320 mil–580 mil | R$3 mil–10 mil | R$50 mil–90 mil | 22–32 sem. |
| 4 | Frota pequena: compliance/manutenção | R$15 mil–35 mil | 4–6 sem. | 12–18 sem. | R$250 mil–450 mil | R$2 mil–8 mil | R$45 mil–80 mil | 18–26 sem. |
| 5 | IA operacional sobre TMS | R$30 mil–70 mil | 6–10 sem. | 20–28 sem. | R$550 mil–950 mil | R$10 mil–50 mil | R$100 mil–180 mil | 30–42 sem. |
| 6 | Copiloto de licenciamento/alvarás | R$20 mil–50 mil | 5–8 sem. | 18–26 sem. | R$400 mil–750 mil | R$3 mil–15 mil | R$60 mil–120 mil | 28–40 sem. |
| 7 | Prevenção de glosas TISS | R$30 mil–80 mil | 6–10 sem. | 24–36 sem. | R$650 mil–1,2 milhão | R$10 mil–40 mil | R$120 mil–220 mil | 36–52 sem. |
| 8 | Operação de segurança contra incêndio | R$15 mil–35 mil | 4–6 sem. | 12–18 sem. | R$240 mil–430 mil | R$2 mil–8 mil | R$40 mil–75 mil | 18–26 sem. |
| 9 | Workflow ISO 17025/calibração | R$20 mil–50 mil | 5–8 sem. | 18–26 sem. | R$400 mil–750 mil | R$3 mil–12 mil | R$60 mil–110 mil | 28–40 sem. |
| 10 | Operação de home care | R$40 mil–100 mil | 8–12 sem. | 28–40 sem. | R$800 mil–1,5 milhão | R$15 mil–60 mil | R$140 mil–260 mil | 40–60 sem. |

No licenciamento, deve-se acrescentar como **HIPÓTESE** cerca de **R$10 mil–30 mil por município** para mapear regras, validar conteúdo, parametrizar checklists e manter a primeira versão. Esse custo pode crescer se houver integração, protocolo assistido ou atualização normativa frequente.

### Bases de mercado disponíveis e seus limites

Esta tabela não converte automaticamente pessoas, empresas, veículos, equipes, serviços ou acreditações em clientes pagantes. Onde o subconjunto do ICP é desconhecido, o TAM, SAM e SOM monetários permanecem **não determinados**.

| Oportunidade | Base observável ou fornecida | Confiança para o universo citado | Lacuna para dimensionar mercado pagante |
|---|---|---|---|
| Conformidade de terceiros/SST | PAIC: aproximadamente **191 mil empresas** de construção e **2,5 milhões de pessoas ocupadas** | Alta para o universo PAIC ([IBGE, 2026](https://agenciadenoticias.ibge.gov.br/agencia-detalhe-de-midia.html?catid=2102&id=8872&view=mediaibge)) | Não informa quantas têm 2–10 obras, terceiros recorrentes, responsável documental e WTP |
| Portal contábil | CFC: **105.893 organizações** e **547.790 profissionais** no recorte consultado | Alta no recorte dinâmico ([CFC](https://www3.cfc.org.br/spw/crcs/ConselhoRegionalAtivo.aspx?P1=&P2=&P3=&P4=&P5=1&P6=)) | Não identifica escritórios com 80–500 CNPJs, coleta manual e orçamento para ferramenta separada |
| MTR/CDF | FEPAM: **146.681 geradores apenas no Rio Grande do Sul**, em fevereiro de 2025 | Alta para o recorte estadual ([FEPAM](https://www.fepam.rs.gov.br/upload/arquivos/202509/23155900-relatoriogerencialmensal-fev-2025-1.pdf)) | Universo nacional do ICP é desconhecido; gerador cadastrado não equivale a operador com 100+ MTR/mês nem comprador |
| Frota pequena | ANTT: **1.049.805 transportadores** e **2.846.202 veículos** | Alta para o cadastro RNTRC ([ANTT, 2025](https://www.gov.br/antt/pt-br/assuntos/cargas/dadostrc/anuario_trc_2025_antt.pdf)) | Subconjunto de empresas com 5–30 veículos, dor não coberta e WTP é desconhecido |
| IA operacional sobre TMS | ANTT: **280.036 ETCs** | Alta para o cadastro de ETCs ([ANTT, 2025](https://www.gov.br/antt/pt-br/assuntos/cargas/dadostrc/anuario_trc_2025_antt.pdf)) | Subconjunto com 20–200 veículos, TMS integrável e centenas de cotações digitais por mês é desconhecido |
| Licenciamento/alvarás | Cerca de **240 mil arquitetos** e **51.066 empresas**, base CAU informada para esta consolidação | Média até revalidação da base dinâmica | Número de protocolos por município, frequência, processo manual, comprador e WTP são desconhecidos |
| Prevenção de glosas TISS | **635.706 médicos** e cerca de **87 mil clínicas odontológicas**, bases profissionais informadas para esta consolidação | Média-alta para os universos profissionais, sujeita a data e definição | Não informa quantos faturam convênios, têm volume/glosa relevante ou comprariam validador separado |
| Segurança contra incêndio | **Sem base nacional confiável reunida** | Baixa/indeterminada | Quantidade de prestadoras, técnicos, ativos geridos, ticket e WTP são desconhecidos |
| ISO 17025/calibração | Inmetro: **2.971 acreditações de vários tipos** e **44.972 serviços de calibração em 2025**, bases informadas para esta consolidação | Média-alta para os indicadores administrativos ([Inmetro](https://www.gov.br/inmetro/pt-br/assuntos/acreditacao-reconhecimento-bpl/organismos-acreditados)) | Acreditação e serviço não equivalem a empresa compradora; número de laboratórios elegíveis e ACV são desconhecidos |
| Home care | Programa público: **985 municípios** e **2.140 equipes** | Média para o programa público informado; não revalidada nesta etapa | Não representa o TAM privado de operadores de home care, clínicas ou cuidadores |

As bases de arquitetos, empresas CAU, médicos, clínicas odontológicas, indicadores de acreditação/calibração e equipes públicas foram fornecidas como premissas para esta consolidação e não foram reconsultadas. Antes de decisão de investimento, devem ser revalidadas na fonte oficial, com data, definição do universo e ausência de dupla contagem.

### Cronograma hipotético das três finalistas

Os marcos abaixo são **HIPÓTESES**. “Primeiros 10/100 clientes” representa tempo desde o início da descoberta, não apenas após o lançamento. Piloto e build podem se sobrepor quando o piloto usa concierge, protótipo ou componente descartável; hardening só deve receber orçamento completo após prova de uso e pagamento.

| Oportunidade | Descoberta | Piloto | MVP | Hardening/produção | 10 clientes | 100 clientes |
|---|---:|---:|---:|---:|---:|---:|
| Conformidade de terceiros/SST | sem. 0–4 | sem. 5–10 | sem. 11–18 | sem. 19–28 | 4–6 meses | 18–30 meses |
| Portal contábil | sem. 0–3 | sem. 4–8 | sem. 9–16 | sem. 17–24 | 3–5 meses | 12–24 meses |
| MTR/CDF | sem. 0–5 | sem. 6–12 | sem. 13–22 | sem. 23–32 | 5–8 meses | 18–36 meses |

### Break-even operacional da oportunidade recomendada

Para conformidade de terceiros/SST, uma aproximação simples do número de clientes necessário para cobrir o burn mensal é:

`clientes para break-even = arredondar para cima[burn mensal ÷ (ARPA mensal × 85% de margem bruta)]`.

| ARPA mensal | Burn de R$45 mil/mês | Burn de R$80 mil/mês |
|---:|---:|---:|
| R$499 | aproximadamente **107 clientes** | aproximadamente **189 clientes** |
| R$699 | aproximadamente **76 clientes** | aproximadamente **135 clientes** |
| R$999 | aproximadamente **53 clientes** | aproximadamente **95 clientes** |

Exemplo: `R$45.000 ÷ (R$499 × 0,85) = 106,1`, arredondado para 107 clientes. A conta é um **cenário operacional**, não uma previsão. Não inclui impostos, capital de giro, inadimplência, desconto anual, expansão de receita, implantação, churn durante a aquisição nem custo de reposição de clientes. O break-even econômico real será maior se a margem ficar abaixo de 85% ou se o burn informado não capturar toda a estrutura.

### Plano de investimento por gates

O maior risco não é errar a tecnologia; é comprometer **R$280 mil–480 mil** no build de conformidade de terceiros antes de observar WTP. O orçamento deve ser liberado em quatro gates:

1. **Validação — R$15 mil–35 mil.** Executar as 20 entrevistas, observar o fluxo real, medir consequência e testar preço. **No-go** se menos de 15 demonstrarem fluxo manual recorrente, menos de dez relatarem consequência nos últimos 12 meses, menos de cinco aceitarem LOI com preço ou piloto pago, ou a mediana aceita ficar abaixo de R$299 sem expansão possível.
2. **Piloto pago.** Operar protótipo/concierge em uma obra por cliente, com limite de escopo e sucesso definido por tempo de conferência, pendência detectada antes da chegada e dossiê gerado. **No-go** se menos de cinco clientes pagarem, se mais de 30% dos requisitos exigirem customização não reutilizável ou se o fornecedor precisar operar permanentemente o processo.
3. **MVP.** Liberar o build progressivamente e manter decisão humana. Aplicar os falsificadores já definidos: pelo menos 70% das vidas completando envio sem intervenção telefônica, configuração mediana em até cinco dias úteis, pelo menos 60% dos usuários operacionais retornando semanalmente e custo de onboarding não superior a três mensalidades. Se os limiares falharem, corrigir o workflow antes de hardening ou interromper a tese.
4. **Escala/produção.** Financiar hardening e aquisição repetível apenas após conversão e retenção iniciais. Os gates existentes continuam: conversão de pelo menos 50% dos pilotos, margem bruta de 70% ou mais, CAC payback em até 12 meses para ACV inferior a R$12 mil e evidência de que o incumbente não oferece a função sem custo adicional na maioria das perdas.

Os gates são **HIPÓTESES de governança pré-registradas**, não benchmarks universais. Sua função é limitar perda, evitar validação retrospectiva seletiva e preservar a opção de abandonar a tese antes do desembolso principal.

## 10. Recomendação final: construir apenas um

### Escolha

**Conformidade de terceiros e SST por obra**, no wedge de apoiar o responsável a impedir mobilização/permanência quando um requisito documental estiver vencido e produzir evidência auditável por obra.

### Por que ela vence

Na hipótese que precisa ser validada, o problema combina frequência relevante, consequência operacional observável, recorrência contratual e histórico que pode aumentar switching cost, com MVP possível sem integração pesada. A PAIC oferece um universo setorial oficial, e a CBIC indica maturidade digital desigual; nenhuma das fontes mede a prevalência do workflow manual. Análogos americanos e competidores brasileiros mostram que a categoria existe, mas não demonstram WTP para este recorte.

Ela vence o portal contábil por margem pequena: ambas têm força de evidência 8, mas o gate operacional pode sustentar WTP maior, enquanto o portal contábil enfrenta concorrência e bundling mais fortes. Vence MTR/CDF porque há evidência mais direta do setor e do stack competitivo, enquanto MTR sofre ancoragem no portal gratuito, fragmentação estadual e falta de denominador nacional do ICP. Essa preferência é uma **HIPÓTESE de investimento**, sujeita ao gate comercial.

### Produto e diferenciação

**Produto.** Sistema por obra/empresa/pessoa que coleta documentos, sugere dados, exibe validade, coloca na fila de revisão, registra liberação/bloqueio e gera dossiê.

**Diferencial.** “Gate operacional auditável em uma semana”, não “plataforma completa de SST”. O upload deve funcionar por link/WhatsApp; o responsável mantém decisão; templates são configuráveis e reutilizáveis; exportação conversa com incumbentes.

**Concorrentes.** Avetta, Billy e myComply nos EUA; RoCost, GEOB, DocSafe, SegWork e Inspeseg no Brasil; Sienge/Mobuss como indiretos com distribuição. A competição local é real e justifica nota 4/10 em concorrência.

### Modelo de cobrança

- R$299/mês: uma obra, até 50 vidas;
- R$699/mês: até três obras, 250 vidas;
- R$1.499/mês: multiobra, até mil vidas;
- excedente por vida ativa/obra, após validação;
- anual equivalente a 10 mensalidades.

Preços são **HIPÓTESES**. Não subsidiar revisão manual ilimitada. Implantação pode ser gratuita no plano menor e cobrada para migração/configuração complexa.

### MVP vendável

1. cadastro/importação de obra, empresa e trabalhador;
2. checklist configurável por função;
3. upload por link simples e WhatsApp;
4. extração assistida de documento/data;
5. fila de revisão humana;
6. aprovação, reprovação e bloqueio com motivo;
7. alerta de vencimento;
8. painel “liberado/pendente/bloqueado”;
9. dossiê PDF e log de auditoria.

Fora do MVP: catraca, biometria, ponto, medicina ocupacional completa, eSocial bidirecional, motor jurídico, gestão ambiental e promessa de conformidade.

### Estratégia para os primeiros clientes

Executar o gate antes de código de produção: 20 entrevistas, no mínimo 15 fluxos manuais recorrentes e cinco LOIs ou pilotos pagos. Usar protótipo/concierge, uma obra por cliente e resultado definido. Consultorias SST devem fornecer cinco dos dez primeiros clientes, mas nenhum canal pode representar dependência exclusiva. Os casos iniciais precisam mostrar tempo de conferência, pendências detectadas antes da mobilização e tempo de geração do dossiê.

### Argumentos a favor

- workflow regulado, com repetição operacional e efeito sobre a obra ainda a validar;
- base oficial grande e setor com maturidade digital desigual;
- buyer identificável e canal por consultoria/obra ativa;
- MVP relativamente pequeno e aprovação humana reduz risco;
- dados/histórico podem aumentar retenção;
- expansão possível para fornecedores, acesso e seguros;
- pricing hipotético comporta entrada barata e expansão por obra/vida.

### Argumentos contra

- fornecedores locais já resolvem partes relevantes;
- construtoras podem considerar o recurso parte de Sienge/Mobuss/SST;
- cada contratante pode impor checklist diferente e inviabilizar padronização;
- terceirizadas podem resistir, mantendo trabalho manual;
- responsabilidade percebida pode ser maior que o ticket;
- ciclo da construção e fim de obra elevam churn;
- a base PAIC é um denominador muito amplo e o mercado elegível pode ser bem menor que os cenários de penetração;
- WTP de R$499 médio ainda não foi observado.

## 11. O que faria a ideia fracassar?

A ideia fracassa se for apenas um repositório com alerta, porque planilha, drive e concorrentes baratos já fazem parte disso. Também fracassa se a equipe vender “conformidade” e assumir responsabilidade que não controla, ou se cada implantação depender de consultor permanente.

### Falsificadores mensuráveis antes do produto

1. **Fluxo não recorrente:** menos de 15 das 20 entrevistas demonstram um fluxo manual semanal/mensal de conferência de terceiros.
2. **Dor sem consequência:** menos de 10 relatam atraso, retrabalho ou risco auditável ocorrido nos últimos 12 meses.
3. **Sem compromisso:** menos de cinco aceitam LOI com preço ou piloto pago; elogio de protótipo não conta.
4. **WTP insuficiente:** mediana das ofertas aceitas abaixo de R$299/mês, sem expansão por obra/vida.
5. **Customização excessiva:** mais de 30% dos requisitos dos pilotos não podem ser representados por templates/campos configuráveis comuns.

Se qualquer um dos itens 1, 3 ou 4 ocorrer, **não construir**; revisar o segmento ou abandonar.

### Falsificadores nos primeiros 90 dias de piloto

1. menos de 70% das vidas convidadas completam envio sem intervenção telefônica da equipe do SaaS;
2. mais de 10% dos documentos exigem operação humana do fornecedor, em vez do cliente, depois da segunda competência;
3. tempo mediano de configuração acima de cinco dias úteis;
4. menos de 60% dos usuários operacionais retornam semanalmente durante obra ativa;
5. menos de 50% dos pilotos convertem em contrato;
6. custo de onboarding superior a três mensalidades no plano contratado;
7. incidência de erro crítico de identidade/validade sem detecção humana acima do limiar acordado; o limiar final deve ser definido com clientes e assessoria jurídica.

### Falsificadores até 12 meses

1. churn mensal por conta acima de 5%, reportado separadamente do encerramento natural de obra;
2. margem bruta abaixo de 70% por suporte e revisão manual;
3. CAC payback acima de 12 meses para ACV inferior a R$12 mil;
4. menos de 20% das contas expandem obra/vida/plano após seis meses;
5. mais de metade das perdas comerciais ocorre porque a funcionalidade já está incluída no incumbente sem custo adicional;
6. um incidente de privacidade grave ou ambiguidade jurídica impede o uso do status como gate operacional.

Esses limiares são **HIPÓTESES de governança**. Devem ser registrados antes dos pilotos para evitar validação retrospectiva seletiva.

## 12. Implicações de marketing e Go-to-Market das três finalistas

| Elemento | Terceiros/SST | Portal contábil | MTR/CDF |
|---|---|---|---|
| ICP | Construtora 2–10 obras, terceiros recorrentes | Escritório 80–500 CNPJs | Consultoria/operador com 100+ MTR/mês, multi-CNPJ/estado |
| Persona | Analista documental/técnico SST | Assistente fiscal/contábil | Analista ambiental/operacional |
| Buyer | Gerente SST/engenharia/diretor | Sócio/gerente de operações | Sócio da consultoria/gerente ambiental/operações |
| Promessa | liberar e provar sem planilhas | fechar competência sem caçar anexos | reconciliar MTR, recebimento e CDF sem conferir portais/planilhas |
| Canal inicial | outbound por obra + consultoria SST | comunidades + parceiros ERP | consultorias ambientais + associações/integradores |
| Evidência de ativação | primeira vida liberada e dossiê | primeira competência fechada | primeiro lote reconciliado e dossiê gerado |
| Principal risco de CAC | múltiplos decisores | ACV baixo | cobertura estadual/integração consumir implantação |

A aquisição deve começar com demonstração do workflow real, não campanha ampla. Para os três produtos, IA é secundária: o comprador quer reduzir atraso, cobrança ou conferência. Parcerias com consultorias são fortes em SST/MTR; parceiros ERP e comunidades ajudam contabilidade. Os passos para os primeiros 10 e 100 clientes estão detalhados nos respectivos deep dives.

## 13. Conclusões críticas

O estudo não encontrou um oceano azul. Encontrou dez workflows em que obrigação, recorrência e fragmentação permitem um SaaS especializado, mas todos têm substitutos. A vantagem brasileira não é traduzir interface americana: é incorporar regra local, canal local, integração local e suporte compatível com ticket de PME.

Os sinais americanos mais fortes — funding em permitting, consolidação em manutenção/frota e adoção de agentes logísticos — mostram investimento e oferta, não provam que buyers brasileiros pagarão. Também alertam que modelos bem capitalizados podem expandir. Mercados visualmente atraentes como beleza, restaurantes e pet foram descartados; frota genérica permaneceu na lista-base, mas só subiu para #4 ajustada porque sua força de evidência supera teses mais especulativas, apesar da concorrência.

A decisão correta agora é uma sequência de testes baratos. O ranking ajustado evita premiar apenas uma narrativa atraente: conformidade de terceiros tem o melhor equilíbrio; portal contábil tem MVP rápido, mas maior risco de bundling; MTR/CDF tem obrigação e fragmentação verificáveis, mas precisa provar manualidade e WTP diante do governo gratuito. IA/TMS permanece oportunidade de alto potencial teórico e baixa confiança, classificada como *solution-first* até que pesquisa primária demonstre o processo.

## 14. Ledger de fontes e claims

O ledger registra a função probatória de cada fonte. “Confiança” avalia apenas o claim específico. Fontes de fornecedor comprovam o que o fornecedor publica, não o resultado econômico alegado.

| Claim | Evidência observável | Fonte, publisher/data | URL | Confiança | Contradições/lacunas |
|---|---|---|---|---|---|
| Uso empresarial de IA nos EUA aproximou-se de 17%–20% em janelas recentes | Série/relato do Business Trends and Outlook Survey | “AI Use Among Businesses”, U.S. Census Bureau, maio 2026 | [Census](https://www.census.gov/library/stories/2026/05/ai-use-businesses.html) | Alta para métrica da pesquisa | Não diretamente comparável ao Cetic; revisão e janela importam |
| Pequenas empresas americanas adotam IA de forma heterogênea | Análise por porte/setor | U.S. Census Bureau, dez. 2024 | [Census](https://www.census.gov/newsroom/blogs/research-matters/2024/12/ai-use-small-businesses.html) | Alta | Não prova WTP por Vertical SaaS |
| IA no Brasil avançou de 13% para 17%; pequenas, 10% para 15%; 79% usam WhatsApp/Telegram | Resultado TIC Empresas divulgado | Cetic.br, 15 jun. 2026 | [Cetic.br](https://cetic.br/pt/noticia/uso-de-inteligencia-artificial-por-empresas-brasileiras-avanca-e-atinge-17-aponta-pesquisa-do-cetic-br/) | Alta para pesquisa | Definições/metodologia distintas do Census |
| Adoção de ERP/CRM é desigual | Tabelas por porte/setor | Cetic.br, TIC Empresas 2025 | [ERP](https://cetic.br/es/tics/pesquisa/2025/empresas/G2/), [CRM](https://cetic.br/es/tics/pesquisa/2025/empresas/G3/expandido/) | Alta | Não mede workflows específicos |
| Barreiras de IA incluem conhecimento/custo/compatibilidade | Tabela H13 expandida | Cetic.br, 2025 | [Cetic.br](https://www.cetic.br/pt/tics/pesquisa/2025/empresas/H13/expandido/) | Alta | Autodeclaração; intensidade varia |
| Vertical SaaS expande valor com múltiplos produtos | Benchmark e tese de investidores | Tidemark, 2024/2025; Stripe, 2025 | [2024](https://www.tidemarkcap.com/post/2024-vertical-smb-saas-benchmark-report), [2025](https://www.tidemarkcap.com/post/2025-vertical-smb-saas-benchmark-report), [Stripe](https://stripe.com/lp/vertical-saas-benchmark-2025) | Média | Viés de seleção e publicação; não prova causalidade |
| IA vertical atrai investimento | Mapa/tese de mercado | Bessemer, 2025 | [Bessemer](https://www.bvp.com/atlas/the-state-of-ai-2025) | Média | Fonte de investidor; incentivos promocionais |
| PermitFlow e GreenLite captaram capital | Comunicados de Série B | PermitFlow, 13 mar. 2026; GreenLite, 15 set. 2025 | [PermitFlow](https://www.permitflow.com/blog/permitflow-series-b), [GreenLite](https://greenlite.com/greenlite-raises-49-5m-series-b-to-transform-permitting-with-ai-and-expertise/) | Alta para anúncio | Funding não prova PMF/lucro; regulação não portátil |
| Construção BR: 191 mil empresas, 2,5 mi ocupados, R$522,5 bi | Divulgação PAIC 2024 | IBGE, 10 jun. 2026 | [IBGE](https://agenciadenoticias.ibge.gov.br/agencia-detalhe-de-midia.html?catid=2102&id=8872&view=mediaibge) | Alta | Universo PAIC não equivale a compradores |
| 70% de 130 respondentes tradicionais/iniciantes em digital | Pesquisa nacional de maturidade | CBIC, 5 dez. 2025 | [CBIC](https://cbic.org.br/pesquisa-nacional-traca-panorama-inedito-da-maturidade-digital-na-construcao/) | Média-alta | Amostra pequena/possível viés; não mede SST especificamente |
| NR-18 cria obrigações de SST na construção | Texto normativo | Ministério do Trabalho, Portaria SEPRT 3.733/2020 | [NR-18](https://www.gov.br/trabalho-e-emprego/pt-br/assuntos/inspecao-do-trabalho/seguranca-e-saude-no-trabalho/sst-portarias/2020/Portaria_SEPRT_3.733_Altera_a_NR_18.pdf) | Alta | Interpretação requer profissional; software não garante conformidade |
| Há fornecedores BR de gestão documental/SST por obra | Páginas de produto | RoCost, GEOB, DocSafe, SegWork, Inspeseg | [RoCost](https://rocost.com.br/), [GEOB](https://www.geobobra.com.br/), [DocSafe](https://www.docsafe.app.br/), [SegWork](https://www.segworksst.com.br/), [Inspeseg](https://inspeseg.com/) | Alta para existência/posicionamento | Sem dados públicos comparáveis de clientes/receita |
| Reclamações de integração/suporte existem em software de construção | Relato individual | Reclame Aqui, usuário, data na página | [Relato](https://www.reclameaqui.com.br/starian-sistemas/insatisfacao-com-sistema-sienge-pela-falta-de-conector-para-integracao-com-o-banco-bradesco-e-deficiencia-no-atendimento_L9v5736hMwFDwEjW) | Baixa para prevalência; alta para existência do relato | Anedótico, não representa clientes Sienge |
| CFC registra 105.893 organizações e 547.790 profissionais no recorte | Consulta dinâmica de ativos | CFC, acessada até 4 set. 2026 | [CFC](https://www3.cfc.org.br/spw/crcs/ConselhoRegionalAtivo.aspx?P1=&P2=&P3=&P4=&P5=1&P6=) | Alta no recorte | Página dinâmica; revalidar valores |
| Reforma tributária tem orientações operacionais para 2026 | Página oficial | Receita Federal, 2026 | [Receita](https://www.gov.br/receitafederal/pt-br/acesso-a-informacao/acoes-e-programas/programas-e-atividades/reforma-tributaria-do-consumo/orientacoes-2026) | Alta | Não prova compra de portal de coleta |
| Coleta/envio contábil por WhatsApp é discutido por profissionais | Dois posts | Reddit/ContabilidadeAtual, 2026 | [Coleta](https://www.reddit.com/r/ContabilidadeAtual/comments/1r0j8d8/como_voc%C3%AAs_lidam_com_a_coleta_de_documentos_de/), [Guias](https://www.reddit.com/r/ContabilidadeAtual/comments/1txes4x/em_2026_voc%C3%AAs_ainda_enviam_guias_e_documentos_por/) | Baixa | Anedótico, possível autopromoção, sem prevalência |
| Financial Cents oferece assinatura/workflow contábil | Produto e preços publicados em CAD na página consultada | Financial Cents, página vigente | [Produto](https://financial-cents.com/), [preços em CAD](https://financial-cents.com/pricing/?currency=cad) | Alta para oferta/preço | Não converter diretamente em referência BRL; não prova adequação ou crescimento |
| Existem 280.036 ETCs e 769.253 TACs | Tabelas do anuário | ANTT, Anuário TRC 2025 | [ANTT](https://www.gov.br/antt/pt-br/assuntos/cargas/dadostrc/anuario_trc_2025_antt.pdf) | Alta | Cadastro não equivale a atividade/WTP; TAC excluído do sizing |
| Vooma e HappyRobot captaram capital; DHL divulgou uso de agentes HappyRobot | Comunicados de empresas | Vooma, 21 maio 2025; HappyRobot; DHL, 11 nov. 2025 | [Vooma](https://www.vooma.com/resources/new-funding-and-products-launch), [HappyRobot](https://www.happyrobot.ai/blog/series-b-announcement), [DHL](https://group.dhl.com/en/media-relations/press-releases/2025/dhl-boosts-operational-efficiency-and-customer-communications-with-happyrobots-ai-agents.html) | Alta para anúncios; média para eficácia | Fontes interessadas; não expõem coortes, margem ou acurácia comparável |
| Ofertas brasileiras de IA para transportadoras já existem | Páginas de produto | Sacflow, VexuIA, XMACNA, vigentes até corte | [Sacflow](https://sacflow.com.br/automacao-de-whatsapp-para-transportadoras), [VexuIA](https://vexuit.com/transportadora), [XMACNA](https://xmacna.ai/ia-transportadora) | Alta para existência/claim do vendor | Sem métricas independentes de tração/acurácia |
| TISS vigente é publicado e versionado pela ANS | Padrão TISS julho/2025 | ANS, jul. 2025 | [ANS](https://www.gov.br/ans/pt-br/assuntos/prestadores/padrao-para-troca-de-informacao-de-saude-suplementar-2013-tiss/padrao-tiss-julho-2025) | Alta | Não mede volume/prevalência de glosa |
| MTR acompanha o transporte; sete estados têm sistemas próprios listados | Serviço e portal | Governo Federal/SINIR | [Serviço](https://www.gov.br/pt-br/servicos/obter-o-documento-manifesto-de-transporte-de-residuos-mtr?id=2458&origem=servico), [portal](https://mtr.sinir.gov.br/) | Alta para regra/lista | Não mede manualidade, volume elegível nem WTP; gratuito comprime preço |
| FEPAM registrou 146.681 geradores no RS em fev. 2025 | Relatório gerencial mensal | FEPAM/RS, fev. 2025 | [FEPAM](https://www.fepam.rs.gov.br/upload/arquivos/202509/23155900-relatoriogerencialmensal-fev-2025-1.pdf) | Alta para recorte local | Não extrapolar ao Brasil; gerador não equivale a cliente ativo/pagante |
| Vertown/Ambisis oferecem soluções ambientais | Páginas de produto | Fornecedores, vigentes até corte | [Vertown](https://www.vertown.com/produtos/), [Ambisis](https://ambisis.com.br/solucoes/) | Alta para existência | Sem receita/churn públicos |
| Produtos brasileiros de incêndio publicam oferta e, no caso ExtinRadar, preço | Páginas dos fornecedores | ExtinRadar, Varkon, Protecin | [ExtinRadar](https://www.extinradar.com.br/precos), [Varkon](https://varkon.com.br/sistema-para-empresa-de-extintores/), [Protecin](https://protecin.com.br/nosso-app/) | Alta para oferta | Não dimensiona base pagante total |
| Fleetio captou/adquiriu Auto Integrate | Comunicado corporativo | Fleetio, 2025 | [Fleetio](https://www.fleetio.com/resources/press/fleetio-raises-series-d-and-acquires-auto-integrate) | Alta para transação anunciada | Não prova lucratividade; categoria madura |
| Prolog/TOTVS já competem em frota no Brasil | Páginas e casos de fornecedor | Prolog/TOTVS | [Prolog](https://www.prologapp.com/cases-de-sucesso/), [TOTVS](https://www.totvs.com/totvs-gestao-de-frotas/) | Alta para presença | Alegações de escala são dos vendors |
| Inmetro mantém referência de acreditados | Diretório oficial | Inmetro, vigente até corte | [Inmetro](https://www.gov.br/inmetro/pt-br/assuntos/acreditacao-reconhecimento-bpl/organismos-acreditados) | Alta | Não equivale ao número de compradores do produto |
| Softwares brasileiros de calibração existem | Páginas de produto | Presys, Metrosys, SISMETRO | [Presys](https://presys.com.br/software-de-calibracao/), [Metrosys](https://metrosys.com.br/), [SISMETRO](https://www.sismetro.com/versao/smart/handling) | Alta para existência | Não há métricas comparáveis de preço/market share |
| Home care tem fornecedores brasileiros | Páginas de produto | LonVi, Kuida, Hope Solution | [LonVi](https://www.lonvi.com.br/), [Kuida](https://kuida.app.br/), [Hope](https://www.hopesolution.com.br/) | Alta para existência | Sem TAM específico e sem satisfação comparável |
| Reclamações/reviews revelam categorias de fricção | Casos/páginas individuais | G2, Capterra, Reclame Aqui, Reddit | [Avetta/G2](https://www.g2.com/products/avetta-avetta/reviews), [Fleetio/Capterra](https://www.capterra.com/p/120855/Fleetio/reviews/), [iClinic/RA](https://www.reclameaqui.com.br/iclinic/problemas-recorrentes-e-falta-de-suporte-tecnico-na-ferramenta-de-prescricao-do-iclinic_wlQBdfZbeImTqBYg/) | Baixa para prevalência | Evidência anedótica, vieses de seleção e autenticidade |
| Agenda regulatória de dados segue em evolução | Agenda publicada | ANPD, 2025–2026 | [ANPD](https://www.gov.br/anpd/pt-br/assuntos/noticias/anpd-publica-agenda-regulatoria-2025-2026) | Alta | Não substitui análise jurídica por produto |
| Pix Automático cria infraestrutura para recorrência | Lançamento/regra do BCB | Banco Central, 2025 | [BCB](https://www.bcb.gov.br/detalhenoticia/20713/noticia) | Alta | Adoção/WTP nos nichos não demonstrados |

### Nota final de integridade

TAM, SAM, SOM, CAC, LTV, margem, churn, payback, preços sugeridos e metas de conversão deste documento são **ESTIMATIVAS ou HIPÓTESES explicitamente marcadas**. Não foram apresentados como fatos observados. Qualquer decisão de investimento deve revalidar números dinâmicos, disponibilidade dos concorrentes, preços e regras após a data de corte.
