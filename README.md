# Previsão de demanda & precificação

- Previsão de Demanda : Usando séries temporais com modelos ARIMA, SARIMA e Prophet. <br>
- Estratégia de Preço : Explorando a relação entre preço e vendas com regressão linear, regressão polinomial e clusterização.<br>

## Dataset
Os dados utilizados nestas análises foram extraídos do dataset "Store Sales - Time Series Forecasting" disponível no Kaggle.<br>
Este dataset contém informações sobre vendas diárias de várias lojas ao longo do tempo. <br>

*Link do Dataset:* https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data

## Previsão de Demanda
A previsão de demanda é uma área crítica na gestão de operações e cadeias de suprimentos. Ela permite que empresas antecipem necessidades futuras de estoque, otimizem a produção e reduzam custos operacionais. Nesta análise, comparamos três modelos de séries temporais:<br>

- ARIMA : Modelo clássico para séries temporais não sazonais.<br>
- SARIMA : Extensão do ARIMA que inclui componentes sazonais.<br>
- Prophet : Ferramenta desenvolvida pelo Facebook para lidar com séries temporais complexas.<br>

Segundo Box et al. (2015) no livro "Time Series Analysis: Forecasting and Control" , o modelo ARIMA é amplamente utilizado devido à sua flexibilidade e capacidade de lidar com diferentes tipos de séries temporais. Além disso, Hyndman & Athanasopoulos (2021) em "Forecasting: Principles and Practice" destacam a importância de avaliar métricas como o Erro Quadrático Médio (MSE) para medir a precisão das previsões.


## Estratégia de Preço

A precificação é uma decisão crítica para maximizar receitas e lucros. <br>

Nesta análise, exploramos a relação entre preço e vendas para identificar se a relação é linear ou não linear, com o emprego de:

- Regressão Linear : Para modelar a relação linear entre preço e vendas.
- Regressão Polinomial : Para capturar relações não lineares.

- Clusterização : Para agrupar produtos com base em preço e vendas, permitindo estratégias diferenciadas.

Segundo Kotler & Keller (2016) em "Marketing Management" , a elasticidade-preço pode ser usada para identificar o ponto ótimo de preço que maximiza a receita ou o lucro. Além disso, Anderson & Simester (2013) em "Pricing Strategy: Setting Price Levels, Managing Price Discounts, and Establishing Price Structures" discutem como modelos econométricos podem ser aplicados para entender a dinâmica de preços e vendas.<br>

## Referências Bibliográficas
Box, G. E. P., Jenkins, G. M., & Reinsel, G. C. (2015). Time Series Analysis: Forecasting and Control . Wiley.<br>

Hyndman, R. J., & Athanasopoulos, G. (2021). Forecasting: Principles and Practice . OTexts. Disponível em: https://otexts.com/fpp3/<br>

Kotler, P., & Keller, K. L. (2016). Marketing Management (15ª ed.). Pearson.<br>

Anderson, E. T., & Simester, D. I. (2013). Pricing Strategy: Setting Price Levels, Managing Price Discounts, and Establishing Price Structures . Cengage Learning.<br>
