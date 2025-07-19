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
Python 3.x

## Libraries
pandas, numpy, matplotlib, statsmodels

## Results
The observed sales data from 2023 to 2024 show high volatility, peaking near 260 before declining to approximately 210 at the end of 2024. 
The ARIMA (1,1,1) model forecasts a continued mild decrease in sales for the first half of 2025, reflecting the recent downward trend in the data. 
This is consistent with the model’s reliance on differenced data and autoregressive patterns, projecting future values based on recent declines. 
The forecast represents expected mean values and does not incorporate external factors such as seasonality or economic influences.

## Managerial Implications
The downward forecast suggests potential challenges in sales performance, warranting strategic attention. 
Managers should consider refining the model by adjusting ARIMA parameters or employing advanced models that account for seasonality (e.g., SARIMA). 
Additionally, auto_arima automatically identifies optimal parameters (p, d, q) and, if necessary, seasonal components from the data, thereby improving forecast accuracy. 
Incorporating exogenous variables may also enhance predictive validity. Recognizing model limitations is essential for informed decision-making and proactive business planning.
