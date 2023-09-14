# Problem Statement.
## Stock prices are prone to more noise and hence forecasting them is very difficult task. The idea here was to understand the daily prices of BankNifty and use LSTM networks for forecasting the prices with least possible error.
## Daily data was chosen with idea that daily charts are more cleaner and noise free as compared to 1 hour or 4 hour data.


# BankNifty-LSTM
## The following jupyter file contains indepth analysis of BankNifty Daily Data from Jan 2022 to Jan 2023.
## Different techniques have been used to understand the best way for forecasting the close price.
### 1. Assuming close prices as function of its previous values.
### 2. Assuming close prices as function of Volume,Open,High and Low made on daily basis to predict close price for that day.

# Conclusions.
## Close prices as function of Volume,Open,High and Low gives minimum error when tested on test set.
## Upcoming work will include the prediction of Daily Mean prices.
