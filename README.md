# Modelo_Predicao_Desempenho_Estrutural
# Documentação do Código


Este script realiza uma análise preditiva do desempenho estrutural com base em dados simulados.
Utiliza um modelo de regressão linear para prever o desempenho com base em duas variáveis de entrada:
'Resistencia_Material' e 'Carga_Aplicada'.

Passos do Código:
1. Importação de bibliotecas necessárias para análise de dados e visualização.
2. Configuração do estilo do Seaborn para gráficos mais atraentes.
3. Estimação de cargas para diferentes tipos de materiais com base em cálculos aproximados.
4. Geração de dados de treinamento aleatórios usando numpy e pandas.
5. Divisão dos dados em conjuntos de treinamento e teste.
6. Treinamento de um modelo de regressão linear utilizando a biblioteca scikit-learn.
7. Realização de previsões no conjunto de teste.
8. Avaliação do desempenho do modelo utilizando métricas como R², MAE e MSE.
9. Visualização dos resultados por meio de gráficos de dispersão utilizando Seaborn.
