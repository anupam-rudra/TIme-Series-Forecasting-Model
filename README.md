### Time Series Forecasting Projects

This repository contains end-to-end time series forecasting projects implemented in Python. The goal is to demonstrate different forecasting techniques including classical statistical models and machine learning approaches.

The file Forecasting.pdf and Forecasting.ipynb  contains python code for forecasting two different time series.
The data used are AirPassengers.csv for first analysis(AirPassengers model).
And train.csv for second analysis(Wall Mart Sales model) 
stores.csv and features.csv have been used with train.csv to bulid the sencond model(Wall Mart Sales model)



## Airline passenger demand forecasting

# Dataset: AirPassengers dataset(AirPassengers.csv)

# Objective

Forecast monthly airline passenger numbers using classical time series models.

# Methods Used

Time series visualization

Stationarity testing (ADF test)

Rolling mean & variance analysis

ACF / PACF analysis

Seasonal decomposition

Model building using

ARIMA

SARIMA

# Key Steps

Data loading and preprocessing

Stationarity check

Parameter selection using ACF/PACF

Model training

Forecast generation

#Model evaluation

Evaluation Metrics

MAE

RMSE

MAPE


## Walmart Sales Forecasting

# Dataset: Weekly sales data from Walmart stores including economic and holiday features(train.csv, stores.csv,features.csv)

# Objective

Predict weekly retail sales using machine learning models with exogenous variables.

# Features Used

Store and department information

Temperature

Fuel price

CPI

Unemployment

Holiday indicator

Lagged sales features

Rolling statistics

#Models Implemented

Random Forest

XGBoost

# Feature Engineering

Lag features

Rolling mean and standard deviation

Time-based features (week, month, year)

Categorical encoding

# Model Evaluation

Evaluation Metrics

MAE

RMSE

MAPE

WMAPE




