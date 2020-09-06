# AppleStockLSTM
Predicting AAPL stock price using LSTM

Updated version takes into consedration of AAPL stock split - https://investor.apple.com/faq/default.aspx

## Google Collab Link
https://colab.research.google.com/drive/1G0EKzr_LezsLmpQSxq1RuGE2bbxmyAOB?usp=sharing

## Introduction
I am using Recurrent neural network called - LSTM to predict the stock price of AAPL (Apple Inc).
I am using LSTM since it has Long term price dependencies.
LSTM's are useful since we can give relavant weights to the important data in the past.
I am using the past 60 days stock price values for the LSTMs.

## Input Data
*Snapshot of data*
The missing dates are Saturdays, Sundays or Public Holidays

![Screenshot 2020-09-05 at 1 42 45 PM](https://user-images.githubusercontent.com/22790699/92319188-99a5ce00-f033-11ea-98be-ee36f6e3d130.png)

![Screenshot 2020-09-05 at 1 42 36 PM](https://user-images.githubusercontent.com/22790699/92319267-db367900-f033-11ea-968c-3b56d616d69f.png)


## Model Prediction

The model's RSME value is **3.8** when the stock prices are in the range of 100+.
This RSME is a good value, considering the abnormal increase in AAPL stock buying due to COVID

*Visualization of the model Predictions*
![Screenshot 2020-08-30 at 2 01 37 PM](https://user-images.githubusercontent.com/22790699/91654992-116f7800-eacb-11ea-8a63-6a891de7fded.png)

![Screenshot 2020-08-30 at 2 01 49 PM](https://user-images.githubusercontent.com/22790699/91655020-55fb1380-eacb-11ea-8f89-f6c1481b63f4.png)

## Improving the accuracy- Next steps

Add a Sentiment analysis of twitter feed

