# MLPRegressor

This code trains a Multi-layer Perceptron (MLP) Regressor model using the MLPRegressor from scikit-learn in Python. It uses the House Sales dataset from Kaggle's King County, USA. The dataset is loaded from Google Drive and preprocessed to remove irrelevant variables.

The code then normalizes the input data using StandardScaler and splits it into training and testing sets. The MLPRegressor model is configured with 50 neurons in the hidden layer, logistic activation function, and other parameters.

After training the model, it makes predictions on the test set and evaluates its performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Percentage Error (MAPE), and R2 Score. It also plots a bar graph comparing the actual and predicted prices for a subset of the test set and a loss curve graph showing the training loss over epochs.

This code is useful for training and evaluating an MLPRegressor model for regression tasks, such as predicting house prices based on various features.
