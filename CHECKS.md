# CHECKS — handyman-v2

Diretrizes específicas deste curso no formato de checagem da fábrica (`FRAMEWORK.md` §4).
Criado na F1 a partir das restrições da semente; cresce a cada decisão de diretriz nova.
Os checks genéricos CG-01..CG-09 valem sempre e não precisam ser repetidos aqui.

## Checks do curso

| ID | Check | Fase onde roda | Origem (por que existe) |
|---|---|---|---|
| CC-01 | | | |
| CC-02 | | | |

<!-- Exemplos reais (curso handyman): escopo legal por skill; travas de linguagem comercial;
     frame de renda sem valores em dólar; fronteira técnica × negócio por nível do ecossistema. -->

## Regras mecânicas (CC-*)

Opcional: dá ao `fabrica check` wordlists de termos proibidos/obrigatórios por ID acima —
sem isso, o CC vira aviso "requer revisão humana" (não bloqueia gate). Preencher só os
IDs que têm regra objetiva (palavra/claim proibido, termo obrigatório); julgamento
qualitativo ("tom coerente", "opções plausíveis") fica de fora — é check humano no gate.

```yaml
# CC-01:
#   proibidos:
#     - "termo ou frase proibida"
#   obrigatorios: []
# CC-02:
#   proibidos: []
#   obrigatorios:
#     - "termo que precisa aparecer"
```

## Pendências abertas

| ID | Pendência | Aula | Dono | Fase travada | Aberta em | Fechada em |
|---|---|---|---|---|---|---|


Regra: check falhou → pendência aqui → a fase travada NÃO inicia para a aula/lote afetado até fechar (destravar sem fechar exige registro no Log do plano do curso).
