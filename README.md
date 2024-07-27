#LSTM Crypto Prediction
This project uses an LSTM neural network to predict Bitcoin prices based on historical data.

##Introduction
The goal is to predict Bitcoin's closing price using historical price data with an LSTM neural network.

##Dataset
Bitcoin price data (BTC_USD.csv) is used, focusing on:
1.Date
2.Open
3.Close

##Preprocessing
Load and format data.
Normalize data using MinMaxScaler.
Create sequences of 100 time steps for training and testing.

#Model
LSTM layers
Dropout layer
Dense output layer

##Training
The model is compiled with adam optimizer and mean_squared_error loss function, then trained for 50 epochs.

##Evaluation
Predictions on the test set are inverted to the original scale. The Mean Absolute Percentage Error (MAPE) is calculated.
