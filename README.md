## 📈 Time Series Analysis & Forecasting for Stock Market

A data analytics project focused on time series forecasting of stock prices using historical data. The project applies various statistical and deep learning models to analyze and predict stock trends, including ARIMA, SARIMA, and LSTM.

---

## 📌 Project Overview

This project aims to forecast stock prices using time series models. We use the Apple (AAPL) stock data from Yahoo Finance, explore its statistical characteristics, and compare the performance of different forecasting models.

---

## 📁 Notebooks Summary

### 🟢 Notebook 1: Data Preprocessing and Visualization

- Loads historical stock data using `yfinance`
- Checks missing values and handles datetime formatting
- Plots stock closing prices
- Decomposes time series into trend, seasonality, and residuals
- Plots autocorrelation and partial autocorrelation to understand time lags

### 🔵 Notebook 2: ARIMA and SARIMA Modeling

- Resamples daily data into monthly averages
- Applies differencing to make data stationary
- Builds:
  - ARIMA model
  - SARIMA model with seasonal components
- Forecasts future prices using both models
- Plots predictions vs actuals
- Calculates Root Mean Squared Error (RMSE) for model evaluation

### 🟠 Notebook 3: LSTM Forecasting

- Scales and normalizes the data using `MinMaxScaler`
- Creates time-series sequences for LSTM input
- Builds an LSTM model using TensorFlow/Keras
- Trains the model on training data
- Makes future predictions and compares them with actual values
- Visualizes performance

---

## 🧰 Tech Stack

| Tool                        | Usage                           |
|-----------------------------|---------------------------------|
| Python                      | Programming language            |
| Pandas, NumPy               | Data manipulation               |
| Matplotlib, Seaborn, Plotly | Visualization                   |
| Statsmodels                 | ARIMA & SARIMA models           |
| Scikit-learn                | RMSE calculation, scaling       |
| TensorFlow/Keras            | Deep learning (LSTM)            |
| yfinance                    | Stock data retrieval            |

---

## 📊 Dataset

- **Stock:** Apple Inc. (AAPL)
- **Source:** Yahoo Finance
- **Date range:** 2015-01-01 to 2023-12-31
- **Features used:** Date, Close
