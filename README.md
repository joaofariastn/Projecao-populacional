# Projecao-populacional
Previsão de Crescimento Populacional com Modelos ARIMA, ARMA e SARIMAX
Este projeto utiliza séries temporais para analisar e prever o crescimento populacional anual (%) de uma região específica com base em dados históricos. Para isso, são aplicados os modelos estatísticos ARIMA (Autoregressive Integrated Moving Average), ARMA (Autoregressive Moving Average) e SARIMAX (Seasonal Autoregressive Integrated Moving Average with Exogenous Regressors).

Objetivo do Projeto
O objetivo é construir modelos preditivos para analisar o comportamento histórico do crescimento populacional e projetar cenários futuros. Este trabalho pode ser útil para análises demográficas, planejamentos estratégicos e políticas públicas.

Conjunto de Dados
Os dados utilizados neste projeto foram extraídos da World Development Indicators (WDI) são um conjunto de dados do Banco Mundial que cobre aspectos econômicos, sociais e ambientais de mais de 200 países, usados para monitorar o desenvolvimento global. Eles incluem temas como economia, saúde, educação, população e sustentabilidade. O conjunto de dados extraidos contém as seguintes informações principais:

Ano: Anos entre 1962 e 2022.
Crescimento Populacional (annual %): Taxa de crescimento populacional anual em porcentagem.
Modelos Utilizados
ARIMA
O modelo ARIMA é utilizado para séries temporais estacionárias ou transformadas em estacionárias. Ele combina três componentes principais:

Autoregressivo (AR): Relação com valores passados.
Integração (I): Transformação de dados não estacionários em estacionários.
Média Móvel (MA): Correlação entre os erros residuais.
ARMA
O modelo ARMA é uma versão simplificada do ARIMA que não utiliza integração (d=0), sendo ideal para séries temporais que já são estacionárias.

SARIMAX
O modelo SARIMAX é uma extensão do ARIMA que incorpora sazonalidade e variáveis exógenas (caso necessário). Ele é mais flexível e permite modelar séries temporais com padrões sazonais e outros fatores externos.
Os principais componentes são:

Autoregressivo (AR), Integração (I) e Média Móvel (MA), como no ARIMA.
Componentes sazonais (P, D, Q, s): Modelam padrões que se repetem em intervalos regulares.
Regressores Exógenos (opcional): Variáveis externas que podem influenciar a série temporal.
Métricas de Avaliação
Para avaliar o desempenho dos modelos, as seguintes métricas foram calculadas no conjunto de teste:

MSE (Mean Squared Error): Média dos erros quadrados.
RMSE (Root Mean Squared Error): Raiz quadrada do MSE.
MAE (Mean Absolute Error): Média dos erros absolutos.
Etapas do Projeto
Pré-processamento dos Dados:

Conversão do ano para formato de data e ajuste do índice da série.
Remoção de valores nulos e transformação logarítmica para estabilizar a variância.
Divisão dos Dados:

Divisão em conjunto de treino (90% dos dados) e conjunto de teste (10% dos dados).
Treinamento dos Modelos:

Otimização dos hiperparâmetros para ARIMA, ARMA e SARIMAX.
Ajuste dos modelos no conjunto de treino.
Avaliação e Previsões:

Avaliação das métricas de desempenho no conjunto de teste.
Projeção do crescimento populacional para os próximos 6 anos.
Resultados e Visualizações
Gráficos comparativos entre dados reais, previsões do conjunto de teste e projeções futuras.
Intervalos de confiança de 95% para as previsões.
Tabelas com previsões futuras detalhadas (valores esperados e limites de confiança).

Contato

E-mail: joaofariastn@gmail.com
LinkedIn: https://www.linkedin.com/in/joaofariastn/
