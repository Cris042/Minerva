## Task ativa

Aplicar a correção de contrato decidida pelo Yoda para semeadura de aplicações consumidoras, com raiz literal declarada e janela temporária de mínimo privilégio; não declarar raiz de produto e não criar `minerva-contabil`.

## Estado atual

Branch nova a partir de `main`. Alterações canônicas em `docs/agentes/severino.md`, `docs/rules.md`, `docs/pendencias-obsidian.md` e continuidade; a base Obsidian Minerva aguarda ou receberá a sincronização das notas correspondentes.

## Decisões vigentes

`raizes_semeadura` permanece vazio. A semeadura tem quatro fases: abrir a janela por PR, semear somente o repositório literal recém-criado, fazer bootstrap de dentro dele e fechar a janela por PR. O despacho comum conserva byte a byte as raízes permanentes existentes.

## Riscos e lacunas

❓ LACUNA: o bind `ro` aninhado de `$raiz_destino/.git` fora do workspace ainda é inferência; a primeira semeadura deve medir `/proc/self/mountinfo` ou confirmar `git commit` com `rc=0`. Revisão independente do Neo é obrigatória antes do merge.

## Próximo passo

Extrair e validar o bloco bash, executar os gates mecânicos, sincronizar a base Obsidian se possível, revisar o diff, fazer commit, push e abrir PR sem aprovar ou fazer merge.

## Região gerada

<!-- minerva-continuity:generated:start -->
Estado gerado para sincronização: lote 1 de governança e fundação da aplicação Minerva Finanças em andamento.
<!-- minerva-continuity:generated:end -->
