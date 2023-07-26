# Time Series Forecasting for Mobile Shop Sales

This project focuses on predictive sales forecasting for a mobile shop using time series analysis and two different modeling approaches: XGBoost and FBProphet. The objective is to develop accurate forecasting models to gain insights into future sales trends and improve business decision-making.

## Project Overview

In this project, we analyze historical sales data of a mobile shop to build time series forecasting models. The dataset contains daily sales records over a certain period, and we aim to predict future sales values based on past trends and patterns.

## Data Preparation

- The raw data is preprocessed to handle missing values, if any, and formatted to have a date-time index.
- Feature engineering is performed to create additional time-related features like day of the week, month, year, etc., which are essential for time series forecasting.

## XGBoost Model

- We use the XGBoost algorithm, a powerful gradient boosting technique, to build a predictive model.
- The dataset is split into training and test sets to evaluate the model's performance accurately.
- Hyperparameter tuning is performed using RandomizedSearchCV to find the best set of parameters for the XGBoost model.

## FBProphet Model

- FBProphet, a time series forecasting library developed by Facebook, is used to build an alternative predictive model.
- FBProphet automatically handles trend changes, seasonality, and holidays in the data, making it an ideal choice for forecasting tasks.
- We evaluate the model's performance using cross-validation and compute relevant evaluation metrics.

## Comparison and Results

- Both models are compared based on various evaluation metrics such as Mean Absolute Percentage Error (MAPE), Mean Squared Error (MSE), and R-squared.
- The results show that the XGBoost model outperforms FBProphet in terms of accuracy, achieving a significantly lower MAPE of 0.11% compared to FBProphet's MAPE of 0.12%.

## Conclusion

The XGBoost model demonstrates remarkable forecasting accuracy, making it a valuable tool for optimizing inventory management, aiding business decision-making, and gaining valuable insights into future sales trends in the dynamic mobile market landscape.

For more details, you can explore the Jupyter Notebooks provided in this repository.

Feel free to reach out for any questions or feedback!

*Author: [Your Name]*

