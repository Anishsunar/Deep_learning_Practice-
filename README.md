# Deep_learning_Practice-
Air Passengers Time Series Forecasting

This project analyzes and forecasts monthly airline passenger data (1949–1960) using ARIMA, SARIMAX, and Prophet models.

Steps Performed

Loaded and cleaned the dataset

Converted date column to datetime

Detected & removed outliers using Z-score

Visualized the cleaned time series

Performed seasonal decomposition

Applied ARIMA, SARIMAX, and Prophet forecasting

Compared model performance using MAE & RMSE

Models Used

ARIMA (2,1,2)

SARIMAX (2,1,2)(1,1,1,12)

Prophet (monthly frequency)

Results
Model	MAE	RMSE
ARIMA	41.83	55.22
SARIMAX	13.99	17.21
Prophet	33.98	41.51

SARIMAX performed the best overall.

Summary

This project demonstrates a full workflow for time-series forecasting, from cleaning and decomposition to model building and evaluation.
