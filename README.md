# AppleStockLSTM
Predicting AAPL stock price using LSTM

## Introduction
I am using Recurrent neural network called - LSTM to predict the stock price of AAPL (Apple Inc).
I am using LSTM since it has Long term price dependencies.
LSTM's are useful since we can give relavant weights to the important data in the past.
I am using the past 60 days stock price values for the LSTMs.

## Input Data
Snapshot of data
the missing dates are Saturdays, Sundays or Public Holidays

![Screenshot 2020-08-30 at 2 00 44 PM](https://user-images.githubusercontent.com/22790699/91654888-45966900-eaca-11ea-935d-44f3ab60d9c3.png)

![Screenshot 2020-08-30 at 2 00 14 PM](https://user-images.githubusercontent.com/22790699/91654797-92c60b00-eac9-11ea-9500-51fa9d5d4d67.png)

## Model Prediction

The model's RSME value is 12.25 when the stock prices are in the range of 500+.
This RSME is a good value, considering the abnormal increase in AAPL stock buying due to COVID

Visualization of the model Predictions
![Screenshot 2020-08-30 at 2 01 37 PM](https://user-images.githubusercontent.com/22790699/91654992-116f7800-eacb-11ea-8a63-6a891de7fded.png)
