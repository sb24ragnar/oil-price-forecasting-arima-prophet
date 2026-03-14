# Oil Price Forecasting with ARIMA and Prophet

A time series forecasting project comparing ARIMA and Prophet on daily crude oil price data. The project focuses on stationarity testing, differencing, model fitting, and forecast evaluation under volatile market conditions.

## Project Objective

The goal of this project is to analyse daily oil price data and compare two forecasting approaches:

- ARIMA
- Prophet

The analysis evaluates how well each model captures trends and predicts future values using hold-out testing.

## Dataset

- Daily oil price observations
- 500 records used in the analysis
- File: `data/oil_prices_2426.csv`


## Methods Used

- Exploratory Data Analysis
- Augmented Dickey-Fuller (ADF) test
- First-order differencing
- ARIMA modelling
- Prophet forecasting
- RMSE-based model comparison

## Key Findings

- The original time series was non-stationary
- First differencing improved stationarity
- ARIMA outperformed Prophet on the test set
- Prophet provided useful trend and seasonality decomposition

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- Prophet
- Jupyter Notebook
