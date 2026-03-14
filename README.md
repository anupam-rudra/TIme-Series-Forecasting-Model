# Time Series Forecasting Projects
## AirPassengers Forecasting & Walmart Sales Prediction

## Project Overview
This repository contains multiple **time series forecasting models** built using Python.  
The project demonstrates how statistical models and machine learning algorithms can be used to forecast future trends from historical data.

Two datasets are used in this project:

1. **AirPassengers Dataset** – Forecasting monthly airline passenger numbers.
2. **Walmart Sales Dataset** – Forecasting weekly retail sales.

The project explores **ARIMA, SARIMA/SARIMAX, and Machine Learning models like Random Forest and XGBoost**.


# Datasets

## 1. AirPassengers Dataset

This dataset contains the **monthly number of international airline passengers from 1949 to 1960**.

### Columns
- `Month` – Date of observation
- `Passengers` – Total airline passengers

### Objective
Forecast future passenger demand using **ARIMA time series modeling**.



## 2. Walmart Sales Dataset

This dataset contains historical sales data for Walmart stores.

### Files Used
- `train.csv` – Weekly sales data
- `stores.csv` – Store information
- `features.csv` – External economic and environmental features

### Important Features
- Store
- Department
- Weekly Sales
- Holiday Indicator
- Temperature
- Fuel Price
- CPI
- Unemployment
- Store Size

### Objective
Predict **future weekly sales** using statistical and machine learning models.

# AirPassengers Forecasting Pipeline

Load Data
↓
Data Cleaning
↓
Datetime Conversion
↓
Time Series Visualization
↓
Stationarity Check (ADF Test)
↓
Differencing
↓
Train/Test Split
↓
ARIMA Model Training
↓
Forecasting
↓
Model Evaluation
↓
Future Prediction

# Walmart Sales Forecasting Pipeline
Data Collection
↓
Data Cleaning & Preprocessing
↓
Exploratory Data Analysis
↓
Feature Engineering
↓
Train/Test Split
↓
Model Training
↓
Forecasting
↓
Model Evaluation
↓
Future Sales Prediction


# Models Implemented

## Time Series Models
- ARIMA
- SARIMA / SARIMAX
- Auto ARIMA

## Machine Learning Models
- Random Forest Regressor
- XGBoost Regressor



# Feature Engineering (Walmart Dataset)

### Time Features
- Month
- Week
- Year

### Lag Features
- Lag 1
- Lag 2
- Lag 3

### Rolling Statistics
- Rolling Mean
- Rolling Standard Deviation

### External Variables
- Temperature
- Fuel Price
- CPI
- Unemployment
- Store Size
- Holiday Indicator
- Store Type


# Evaluation Metrics

Model performance was evaluated using:

- **MAE** – Mean Absolute Error
- **RMSE** – Root Mean Squared Error
- **MAPE** – Mean Absolute Percentage Error













# AirPassengers Forecasting Pipeline
