# Análise de Engajamento: Instagram

Este projeto realiza uma análise exploratória de dados de posts do Instagram para identificar padrões de engajamento. O objetivo é entender quais tipos de conteúdo, formatos e estratégias geram mais interação (curtidas e comentários) para auxiliar na tomada de decisão estratégica de marketing digital.

## Tecnologias Utilizadas

- **Python:** Linguagem principal utilizada para o desenvolvimento da lógica.
- **Pandas:** Biblioteca fundamental utilizada para toda a manipulação, limpeza e agrupamento dos dados de engajamento.
- **Jupyter Notebook:** Ferramenta utilizada para documentar o passo a passo da análise e visualizar as tabelas geradas.

## Por que focar no Pandas neste projeto?

Neste projeto, o foco técnico foi a manipulação de DataFrames, onde utilizei:
- **Tratamento de Dados:** Limpeza de valores nulos e correção de tipos.
- **Filtros Avançados:** Seleção de posts baseada em critérios específicos (ex: posts com pessoas vs. sem pessoas).
- **Agrupamentos (Groupby):** Extração de médias de engajamento por categoria de conteúdo para validar as hipóteses de negócio.

## Estrutura do Projeto

- `Pedido.ipynb`: Definição do problema de negócio e perguntas a serem respondidas.
- `Analisando.ipynb`: Limpeza de dados, tratamento de valores vazios e análise exploratória inicial.
- `Conclusões.ipynb`: Consolidação dos insights, agrupamentos por categoria e respostas aos problemas propostos.
- `dados/`: Base de dados utilizada na análise.
- `grafico_final.png`: Visualização principal dos resultados obtidos.

## Insights Extraídos

O projeto foca em entender os fatores que impulsionam o engajamento, respondendo a perguntas como:
1. **Presença Humana:** Posts que contêm fotos de pessoas possuem um engajamento (curtidas/comentários) superior a posts apenas com produtos?
2. **Efetividade de Campanhas:** Como as tags de categorias específicas influenciam na performance das publicações?
3. **Análise de Tendências:** Qual o comportamento das métricas de interação quando comparamos diferentes tipos de conteúdo?

## Resultado Principal

![Gráfico Final](grafico_final.png)

<hr>

Desenvolvido por [Samuel Campos Salema](https://github.com/samuelcsalema)