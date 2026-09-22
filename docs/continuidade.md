## Task ativa

Corrigir o contrato de despacho do Severino na branch `docs/correcao-contrato-semeadura-20260921`.
O escopo está fechado a `docs/agentes/severino.md` e este arquivo; não declarar raiz de produto,
não criar `minerva-contabil` e não fazer push, merge ou aprovação.

## Estado atual

Alterações aplicadas somente nos dois arquivos permitidos e commitadas na branch. O bloco Bash passa
em `bash -n`; a recusa por raiz com newline termina com `EXIT_CODE_CODEX=2` na saída específica do
despacho.

## Decisões vigentes

Estado: `raizes_semeadura` continua vazio e, nesse estado, `raizes` conserva byte a byte as duas
raízes permanentes. O contrato agora exige `SEVERINO_DESPACHO_ID`, cria a saída específica antes
das guardas, registra recusas com sentinela final `EXIT_CODE_CODEX=2`, rejeita newline/`..` antes
do `grep`, usa `git init -q --template=''` com rc verificado e documenta a ressalva de filesystem
na auto-revogação. A revisão independente do Neo foi registrada no histórico de Severino.

## Riscos e lacunas

O bind `ro` aninhado de `$raiz_destino/.git` fora do workspace continua não medido; a primeira
semeadura deve conferir `/proc/self/mountinfo` ou um `git commit` com rc 0. A auto-revogação também
depende de o filesystem permitir observar existência e conteúdo; erro de leitura não prova vazio.

## Próximo passo

Próximo passo: comentar no PR #7 as correções e evidências, sem aprovar nem fazer merge; aguardar a
rerrevisão do Neo.

## Região gerada

<!-- minerva-continuity:generated:start -->
Estado gerado: correção do contrato de despacho do Severino commitada e aguardando rerrevisão do Neo.
<!-- minerva-continuity:generated:end -->
