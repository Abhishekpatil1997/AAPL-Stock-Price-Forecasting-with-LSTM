# Project Title: AAPL Stock Price Forecasting with LSTM 

This repository implements an LSTM model to forecast the closing prices of Apple (AAPL) stock using historical price data.
# For detailed analysis and visualizations, refer to the [PDF project report](./Project_report_Final.pdf).

## Overview

This project utilizes Long Short-Term Memory (LSTM) networks, a specialized type of Recurrent Neural Network good at analyzing sequential data, to predict the close prices of AAPL stock.

Accurate stock price forecasting is invaluable for financial analysis and trading strategies. The predictive modeling approach applied here demonstrates the capabilities of deep learning in identifying patterns in time series data.

## Methodology 

The key aspects covered are:

- Data collection: Obtaining AAPL stock price history
- Data preparation: Scaling and transforming features   
- LSTM model development: Creating and compiling LSTM architecture
- Model training: Fitting model on train data 
- Evaluation: Assessing performance metrics on test set
- Visualizations: Plotting predictions against actual values

## Results

The LSTM model achieves:

- R-squared score of 93.17%
- Low error rates: MSE of 25.12, RMSE of 5.01



## Future Work

Additional explorations for improving model robustness:

- Backtesting on more data
- Architecture optimization  
- Expansion to other stocks
- Integration in trading systems

Overall, the project displays promising results for using LSTMs in financial forecasting.
