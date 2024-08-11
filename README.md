# Time-Series-Forecasting-of-Electric-Production
## Project Overview
This project aims to forecast the monthly electric production in the United States using time series analysis techniques. The dataset contains historical data from January 1985 to December 2018, and the objective is to build a predictive model that can be used by policymakers and energy companies for planning and decision-making.

## Dataset
Link: Electric Production Dataset

Date Range: January 1985 - December 2018
Features:
Date: Observation date
Production: Electric production in millions of megawatt hours


## Methods Used
### Statistical Tests:
Mann-Kendall Trend Test
Kruskal-Wallis Test
### Time Series Models:
Holt-Winters Exponential Smoothing
ARIMA (AutoRegressive Integrated Moving Average)
SARIMA (Seasonal ARIMA)
### Model Evaluation Metrics:
Root Mean Squared Error (RMSE)
Mean Absolute Percentage Error (MAPE)


## Results
The ARIMA model provided the best performance based on RMSE and MAPE, making it suitable for forecasting future electric production.

## Future Work
Implementing other advanced time series models like Prophet.
Extending the model to include exogenous variables like temperature, economic factors, etc.
