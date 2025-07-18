# Sales Forecasting Using ARIMA Model in Python

This repository presents a practical implementation of the ARIMA (AutoRegressive Integrated Moving Average) model for forecasting monthly sales data. The dataset is simulated to demonstrate the application of time series analysis techniques.

## Abstract

ARIMA is a widely utilized statistical model for analyzing and forecasting univariate time series data. It integrates autoregressive terms, differencing to achieve stationarity, and moving average components to capture autocorrelation in residuals. This project exemplifies the fitting of an ARIMA(1,1,1) model and the subsequent projection of sales for six future periods, illustrating the model's capacity to capture underlying trends and noise in temporal data.

## Methodology

- Simulated monthly sales data exhibiting an upward trend was generated.
- The data was modeled using ARIMA with parameters (p=1, d=1, q=1).
- Forecasts for the subsequent six months were produced.
- Visualization contrasts observed data with forecasted values, facilitating model validation.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- statsmodels
