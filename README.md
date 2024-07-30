# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Avg.wQL (0.379):

Significado: Este valor representa a média ponderada da perda quantílica. Um valor de 0.379 sugere que, em média, a discrepância entre os valores previstos e os valores reais é relativamente baixa. Isso indica que o modelo tem um bom desempenho em prever os quantis dos dados.
MAPE (0.428):

Significado: O MAPE de 0.428 indica que o erro percentual médio absoluto das previsões do modelo é de aproximadamente 42.8%. Em outras palavras, em média, as previsões do modelo estão desviando cerca de 42.8% dos valores reais. Esse valor pode ser considerado alto dependendo do contexto e da aplicação.
WAPE (0.539):

Significado: O WAPE de 0.539 indica que, quando ponderado pela importância de cada ponto de dados, o erro absoluto médio é de aproximadamente 53.9% do valor real. Assim como o MAPE, um valor alto de WAPE sugere que há uma discrepância significativa entre as previsões e os valores reais.
RMSE (25.872):

Significado: O RMSE de 25.872 indica que a raiz do erro quadrático médio das previsões é 25.872. Esse valor proporciona uma medida da magnitude dos erros das previsões em unidades da variável predita. Um RMSE alto pode indicar a presença de grandes desvios entre os valores previstos e os valores reais.
MASE (0.569):

Significado: O MASE de 0.569 sugere que o modelo preditivo está se saindo melhor do que um modelo de referência (por exemplo, uma média histórica), já que o valor é menor que 1. Um MASE de 0.569 significa que o erro absoluto médio do modelo preditivo é aproximadamente 56.9% do erro absoluto médio do modelo de referência.
Resumindo, os valores fornecem uma visão sobre a performance do modelo, destacando tanto seus pontos fortes quanto suas áreas de melhoria. Um Avg.wQL relativamente baixo e um MASE menor que 1 são indicadores positivos, enquanto os valores de MAPE e WAPE sugerem que há espaço para melhorar a precisão percentual das previsões.
