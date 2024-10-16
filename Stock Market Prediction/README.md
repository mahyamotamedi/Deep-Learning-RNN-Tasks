# Stock Market Prediction Using RNN

## Overview
This project involves predicting stock prices of Apple (AAPL) and Google (GOOG) using Recurrent Neural Networks (RNNs). The dataset consists of historical stock prices, and the task is to forecast the stock prices for the next day.

## Dataset
- **AAPL.csv**: Historical stock data for Apple.
- **GOOG.csv**: Historical stock data for Google.
- Each row in the dataset represents one day, including the "close" price, which is the target variable for prediction.

## Methods
- **Models**: LSTM, GRU, and Vanilla RNN are used to build predictive models.
- **Metrics**: The performance of each model is evaluated using MSE and MAPE.
- **Optimizers**: Adam, RMSprop, and ADAgrad optimizers are tested, with results compared.
- **Regularization**: Dropout layers are applied to prevent overfitting.

## Results
The prediction accuracy and error rates for each model are compared. The training time for a fixed number of epochs is also measured and analyzed.

