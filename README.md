# Mene Tekel · dados abertos

Índice público de risco global: quatro cavaleiros (Conquista, Guerra, Fome e Morte)
medidos com dados oficiais e convertidos em uma escala de sete selos.

Este repositório é atualizado automaticamente. Cada commit corresponde a uma mudança
nos dados ou no cálculo, o que mantém o histórico público e auditável.

| Arquivo | Conteúdo |
| --- | --- |
| [`latest.json`](https://cdn.jsdelivr.net/gh/rodrigo13f/menetekel-data@main/latest.json) | Índice atual: selos, total, tendência, projeção, cavaleiros e indicadores |
| [`historico.json`](https://cdn.jsdelivr.net/gh/rodrigo13f/menetekel-data@main/historico.json) | Série anual desde 1990 |
| [`indicadores.csv`](https://cdn.jsdelivr.net/gh/rodrigo13f/menetekel-data@main/indicadores.csv) | Valor e nota de cada indicador, ano a ano |
| `metodologia/` | Metodologia vigente (versão 1.0.0): âncoras, pesos e regras |

Anos sem dado de um indicador são preenchidos (interpolação ou último valor) e
marcados como `estimado`.

Licença: CC BY 4.0 (veja `LICENSE`). Os valores brutos seguem a licença de cada fonte.

O Mene Tekel usa imagens do livro do Apocalipse como metáfora cultural. Não faz
previsões religiosas: a data projetada é condicional ("no ritmo atual").
