# NovaTech Store Sales Forecasting Analysis

## Project Overview
This project analyzes historical daily sales data from NovaTech Store to determine the most accurate forecasting technique for predicting Lenovo PC sales.
The analysis compares multiple forecasting models and evaluates their performance using error metrics such as MAE, MSE, and MAPE.

## Dataset
365 days of historical daily sales data.

## Variables:
- Date (independent variable)
- Daily Sales (dependent variable)

## Forecasting Methods Tested:
The following forecasting techniques were evaluated:

- Naïve Forecast
- Moving Average (3-day and 7-day)
- Exponential Smoothing
- Simple Linear Regression (SLR)
- Linear Forecast
- SLR + Seasonality

## Evaluation Metrics:
Models were evaluated using the following metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Mean Absolute Percentage Error (MAPE)

## Key Insight:
- Sales show minimal long-term trend but clear seasonal patterns.  
- Models that incorporate seasonality produced the most accurate forecasts.

## Recommended Model:
SLR × Seasonality provided the lowest forecasting error and is recommended for predicting daily sales.

## Technologies Used:
- Microsoft Excel (data analysis and forecasting models)
- Microsoft PowerPoint (presentation of results)
- GitHub (project hosting and documentation)
  
## Files in this repository:
- NOVATECH COMPUTER STORE.xlsx  
  Excel workbook containing forecasting calculations and model comparisons.

- novatech_stores_report.pptx  
  PowerPoint presentation summarizing the forecasting analysis.

