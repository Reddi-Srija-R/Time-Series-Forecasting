## Time Series Forecasting with Novo Nordisk Stock Data
This repository contains a time series forecasting project where I applied ARIMA and SARIMA models to predict Novo Nordisk stock prices. The dataset was sourced from Yahoo Finance.

`Problem Statement`

The goal of this project is to perform a daily forecast for one month on Novo Nordisk stock data. 

NOTE: Novo Nordisk is a global healthcare company specializing in diabetes care medications and devices.

`Data Details`

- Company: Novo Nordisk
- Data Range: 10 years
- Source: Yahoo Finance Novo Nordisk Historical Data

`Approach`

- Data Collection: Acquired stock price data for Novo Nordisk from Yahoo Finance.
  
- Data Transformation: Performed a log transformation to address skewness in the data. The reasons for this transformation are briefly discussed in the notebook.
  
- Model Implementation: Implemented ARIMA and SARIMA models on both the original and transformed data.
  
- Results: Compared the performance of models using both the actual and transformed data.

`Key Findings`

Based on the analysis and results presented in the notebook:

- Log Transformed Data: The models performed better with the log-transformed data. This transformation helped to stabilize variance and improve model accuracy.
- Original Data: The models showed less reliable results when applied to the untransformed data.

For detailed reasons behind the preference for transformed data and an in-depth analysis of the models' performance, please refer to the notebook included in this repository.

Thank You!
