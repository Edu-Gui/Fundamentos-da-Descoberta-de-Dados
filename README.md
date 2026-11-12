# Projeto – Fundamentos da Descoberta de Dados (EBAC – Módulo 13)

Análise estatística e visual da base de produtos de um supermercado do Chile (1.107 produtos, 7 categorias).

## O que foi feito
- **Média e mediana do preço por categoria**: em quase todas as categorias a média fica acima da mediana (distribuição assimétrica à direita). A exceção é `comidas-preparadas`.
- **Desvio padrão por categoria**: `lacteos` é a categoria mais heterogênea (desvio de 3.926), com média de 2.385 contra mediana de 989.
- **Boxplot de `lacteos`**: 43 outliers (cerca de 10% da categoria) acima de 6.119, a maioria packs de 12 unidades.
- **Média de desconto por categoria**: os descontos se concentram em `congelados` (154) e `belleza-y-cuidado-personal` (123). Frutas, verduras e instantâneos não têm desconto.
- **Mapa interativo (treemap, Plotly)**: média de desconto por categoria e marca. O destaque é a Magnum (955).

## Arquivos
| Arquivo | Descrição |
|---|---|
| `Profissao_Cientista_de_Dados_M13_Projeto.ipynb` | Notebook com o código e as análises |
| `MODULO7_PROJETOFINAL_BASE_SUPERMERCADO.csv` | Base de dados |
| `graficos/` | Imagens dos gráficos (boxplot, barras e mapa) |

## Tecnologias
Python · Pandas · Matplotlib · Seaborn · Plotly Express

**Autor:** Eduardo Costa · [LinkedIn](https://www.linkedin.com/in/eduardo-costa-408029235) · [GitHub](https://github.com/Edu-Gui)
