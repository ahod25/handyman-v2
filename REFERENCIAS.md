# REFERENCIAS - handyman-v2

Status: RASCUNHO - fase F0.5, depois do GATE-0 e antes de F1

Objetivo: transformar temas, links, videos, PDFs, textos e notas em contexto aprovado
para guiar F1/F2/F3 sem perder rastreabilidade, licenca e decisao humana.

## Politica de uso

- Material em `inbox` ou `extracted` ainda nao guia autoria.
- Apenas itens `approved_context` entram no prompt autoral de F1/F2/F3.
- Apenas itens `approved_media` podem virar asset final ou ser republicados.
- Video de terceiro nunca deve ser baixado/republicado no YouTube do curso sem autorizacao ou licenca explicita compativel.
- Fonte rejeitada permanece registrada para evitar que volte por acidente.

## Estrutura de arquivos

| Caminho | Uso |
|---|---|
| `referencias/inbox/` | Arquivos brutos e listas de links fornecidos pelo stakeholder |
| `referencias/LINKS.md` | Links, canais, videos, temas e perguntas que a IA de ingestao deve processar |
| `referencias/extracted/` | Texto extraido, transcricoes, metadados e resumos mecanicos |
| `referencias/approved/` | Briefings aprovados por aula/tema |
| `referencias/approved/IA_CONTEXT.md` | Documento consolidado que a IA autoral pode ler em F1/F2/F3 |
| `referencias/media/` | Assets com direito de uso/republicacao triado |
| `referencias/manifest.json` | Indice auditavel de todas as referencias |

## Temas de pesquisa

| ID | Tema | Aulas | Prioridade | Observacao |
|---|---|---|---|---|
| T-001 | | | alta/media/baixa | |

## Fontes candidatas

| ID | Tipo | Fonte/link/arquivo | Aulas | Status | Licenca/uso | Decisao |
|---|---|---|---|---|---|---|
| R-001 | video/texto/pdf/site/nota | | | inbox/extracted/approved_context/approved_media/rejected | | |

## Briefings aprovados

| Aula/Tema | Arquivo em `referencias/approved/` | O que usar | O que evitar |
|---|---|---|---|
| aula-00 | | | |

## Lacunas

| ID | Lacuna | Aula/Tema | Acao necessaria | Dono |
|---|---|---|---|---|
| L-001 | | | | |

## Log de decisoes

| Data | Decisao | Quem |
|---|---|---|
| AAAA-MM-DD | | |
