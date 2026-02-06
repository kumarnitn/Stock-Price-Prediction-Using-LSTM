# Stock-Price-Prediction-Using-LSTM
Stock price prediction using LSTM neural networks based on historical market data.
This notebook predicts stock closing prices using an LSTM neural network. The data is taken from Yahoo Finance using the yfinance library. Basic preprocessing steps like normalization, time-step creation, and train-test splitting are included.

Steps in the project:

Downloaded stock data using yfinance

Prepared the sequence data needed for LSTM

Scaled features using MinMaxScaler

Created an LSTM model with Keras

Trained the model to predict next-day closing price

Compared predictions with actual values

Libraries used: Python, Pandas, NumPy, scikit-learn, TensorFlow/Keras, yfinance

File: Stock-Price-Prediction-Using-LSTM.ipynb
