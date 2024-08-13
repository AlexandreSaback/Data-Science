# Ordem de Exploração
A ordem de exploração dos Jupyters é a seguinte:
- DataExploration: Análise Exploratória e Descritiva dos Dados;
- ModelsExploration: Exploração de Modelos de Regressão;
- FinalModel: Estimação do Modelo Final

# Métodos de Modelagem
- Modelo Linear OLS: Utilizado como ponto de partida inicial para fins de comparação entre outros modelos (_baseline_);
- Modelo Linear OLS com transformações _box-cox_: Utilizando para tentar modelar relações não lineares encontradas nos dados através de um método simplório;
- Modelo regressor XGBoost: Utilizado para modelar relações não lineares entre as variáveis analisadas;
- Modelo regressor XGBoost com parâmetros provenientes de um Grid Search: Após validar a eficácia do modelo anterior, um ajuste de hiperparâmetros foi aplicado para melhorar a performance do modelo.

# Métricas de Erro
- R²: Utilizado inicialmente para comparar os dois modelos lineares (OLS) estimados;
- MSE: Utilizado para ressaltar erros decorrentes de valores extremos (_outliers_) ou falhas graves de performance preditiva;
- MAE: Utilizado para ilustrar de forma mais fidedigna o desempenho do modelo, não sendo fortemente influenciado por valores extremos;
- MAPE: Utilizado apenas na avaliação do modelo final para fornecer uma métrica percentual com maior interpretabilidade. Devido à escala dos dados utilizados, tal métrica foi essencial para avaliar o modelo de forma mais direta.
