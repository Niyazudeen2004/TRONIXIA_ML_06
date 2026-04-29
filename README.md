# TRONIXIA_ML_06
# Stock Price Prediction using Machine Learning

## Overview
This project focuses on predicting stock closing prices using historical market data and machine learning techniques. The objective is to model price trends based on previous day information and understand how basic regression methods can be applied to time series data.

---

## Dataset
- Dataset: Historical Stock Price Data
- Features:
  - Date
  - Open
  - High
  - Low
  - Close
  - Volume

Due to file size limitations, the dataset is not included in this repository.

You can download similar datasets from:
https://www.kaggle.com/datasets/borismarjanovic/price-volume-data-for-all-us-stocks-etfs

---

## Methodology

### 1. Data Preprocessing
- Converted `Date` column to datetime format
- Sorted data chronologically
- Removed unnecessary columns

### 2. Feature Engineering
- Created lag features:
  - Previous day closing price (`Prev_Close`)
  - Previous day opening price (`Prev_Open`)
- Defined target variable as next day closing price

### 3. Model Training
- Used Linear Regression model
- Converted time series data into supervised learning format

### 4. Evaluation Metrics
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

---

## Results

- The model was able to capture general stock price trends
- Predictions followed the overall direction of actual prices
- Error metrics indicated reasonable performance for a baseline model

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook
- GitHub

---

## Key Learning Outcomes

- Converting time series data into supervised learning format
- Creating lag-based features
- Applying regression models to financial data
- Evaluating regression performance using MAE and RMSE
- Visualizing actual vs predicted values

---

## Conclusion

This project demonstrates how machine learning can be applied to stock price prediction using simple regression techniques. By leveraging historical data and feature engineering, meaningful insights into price trends can be obtained without relying on complex forecasting models.
