# previsao-de-demanda
Previsão de Demanda com Séries Temporais

Contexto
Uma empresa de distribuidora de medicamentos deseja melhorar suas previsões de demanda de produtos para otimizar seus estoques e reduzir custos operacionais. Atualmente, as previsões são feitas de forma manual e não têm sido eficazes, resultando tanto em excesso de estoque quanto em falta de produtos. Como Cientista de Dados Pleno, você foi convidado para desenvolver um modelo de previsão de demanda utilizando séries temporais.


Objetivo
Desenvolver um modelo de previsão de demanda para os próximos 12 meses, com base nos dados históricos de vendas de um produto específico.

Você deve utilizar técnicas de séries temporais para criar esse modelo, focando na escolha apropriada de métricas de erro e na análise crítica do desempenho do modelo em relação ao conjunto de dados de validação. Além disso, você deve considerar fatores como tendências, sazonalidade e possíveis anomalias.


Instruções
EDA - Exploração Inicial dos Dados: Realize uma extensa análise exploratória dos dados, identificando padrões 

Modelagem: Utilize pelo menos 2 métodos de modelagem para prever a demanda futura. Recomendamos considerar:

Modelos tradicionais de séries temporais (como ARIMA, SARIMA, ou ETS, etc).

Modelos baseados em aprendizado de máquina (como LSTM, Prophet ou outros).

Modelos de séries temporais hierarquicas (top-down, botton-up, etc)

Validação Cruzada: Justifique porque você escolheu tal método em vez de outro (levando em consideração as particularidades de séries temporais (como Time Series Split), caso use validação cruzada no fine tunning, justique também.

Métricas de Avaliação:

Avalie o desempenho do seu modelo utilizando as seguintes métricas de erro:

MAE (Mean Absolute Error)

MSE (Mean Squared Error)

RMSE (Root Mean Squared Error)

MAPE (Mean Absolute Percentage Error)

WMAPE (Weighted Mean Absolute Percentage Error)

Explique qual métrica você considera mais adequada para este tipo de problema e por quê.

Foque nas métricas de erro mas não exclua as outras

Ajuste de Hiperparâmetros: Descreva o processo de ajuste de hiperparâmetros, se aplicável e porque usou tal método em vez de outro.

Análise de Resíduos: Avalie os resíduos do modelo + o cumprimento ou não dos pressupostos estatístico e seus respectivos p-values.
