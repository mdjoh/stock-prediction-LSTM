# Stock Prediction with LSTM

This notebook covers predicting the price of AAPL using LSTM and completes the following tasks:

- A) Predicting the share price for five days using the prices of the past 60 days.

- B) Generating trading signals for the testing period (20% of dataset):
  - if the preidcted price is higher than the current price, buy one share
  - if the predicted price is lower than the current price, short one share

- C) Calculating the accumulated profit/loss for testing data assuming that the position will always be closed after five trading days.

- D) Repeating the A-C with historical S&P500 index data added to the features.

- E) Predicting the share price for five days after adding difference between daily high and low of AAPL.
