# A densidade de políticas públicas para mulheres associada às ideologias político-partidárias

Apresentação do andamento da pesquisa de mestrado em Ciência Política (IPOL/UnB).

**Autora:** Bruna Gomes Guimarães · **Orientador:** Prof. Frederico Bertholini

👉 **Ver a apresentação:** https://brunagguimaraes.github.io/Densidade-de-pol-ticas-de-mulheres/

## Conteúdo

| Arquivo | O que é |
|---|---|
| `index.html` | Apresentação pronta (slides em HTML, gerados com R Markdown / ioslides) |
| `apresentacao_pesquisa.Rmd` | Código-fonte da apresentação |
| `unb.css`, `logounb.jpg` | Estilo e logo |
| `dados/df_analise.rds` | Banco enxuto: 26 UFs × 3 períodos (2013, 2018, 2023) = 78 linhas |
| `dados/df_final.rds` | Banco completo (inclui os componentes da rede estadual) |

## Como rodar

1. Baixe ou clone o repositório.
2. Abra `apresentacao_pesquisa.Rmd` no RStudio e clique em **Knit**.
   Pacotes: `dplyr`, `tidyr`, `ggplot2`, `knitr`, `rmarkdown` (instalados automaticamente pelo `pacman`).

Na apresentação, use as setas do teclado para navegar; **F** abre em tela cheia.

## Fontes dos dados

- IBGE – Pesquisa de Informações Básicas Municipais (MUNIC) e Estaduais (ESTADIC): 2013, 2018 e 2023
- IBGE – Projeções da População, revisão 2024 (população feminina por UF)
- TSE – candidatos eleitos e votação presidencial (via pacote `electionsBR`)
- Bolognesi, Ribeiro e Codato (2023) – classificação ideológica dos partidos

Unidade de análise: estado-ano (26 UFs; o Distrito Federal é excluído).
