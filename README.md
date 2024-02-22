# MLPRegressor

Este código treina um modelo de Regressor de Perceptron de Múltiplas Camadas (MLP) usando o MLPRegressor do scikit-learn em Python. Ele utiliza o conjunto de dados de vendas de casas do condado de King, EUA, disponível no Kaggle. O conjunto de dados é carregado do Google Drive e pré-processado para remover variáveis irrelevantes.

Em seguida, o código normaliza os dados de entrada usando o StandardScaler e os divide em conjuntos de treinamento e teste. O modelo MLPRegressor é configurado com 50 neurônios na camada oculta, função de ativação logística e outros parâmetros.

Após o treinamento do modelo, ele faz previsões no conjunto de teste e avalia seu desempenho usando métricas como Erro Médio Absoluto (MAE), Erro Quadrático Médio (MSE), Erro Quadrático Médio da Raiz (RMSE), Erro Percentual Absoluto Médio (MAPE) e R2 Score. Também gera um gráfico de barras comparando os preços reais e previstos para um subconjunto do conjunto de teste, e um gráfico da curva de perda mostrando a perda de treinamento ao longo das épocas.

Este código é útil para treinar e avaliar um modelo MLPRegressor para tarefas de regressão, como prever preços de casas com base em várias características.

***================================================***

This code trains a Multi-layer Perceptron (MLP) Regressor model using the MLPRegressor from scikit-learn in Python. It uses the House Sales dataset from Kaggle's King County, USA. The dataset is loaded from Google Drive and preprocessed to remove irrelevant variables.

The code then normalizes the input data using StandardScaler and splits it into training and testing sets. The MLPRegressor model is configured with 50 neurons in the hidden layer, logistic activation function, and other parameters.

After training the model, it makes predictions on the test set and evaluates its performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Percentage Error (MAPE), and R2 Score. It also plots a bar graph comparing the actual and predicted prices for a subset of the test set and a loss curve graph showing the training loss over epochs.

This code is useful for training and evaluating an MLPRegressor model for regression tasks, such as predicting house prices based on various features.
