# Time Series Forecasting for Mobile Shop Sales

![Time-Series-Analysis](https://github.com/Aravinth-Megnath/Time-Series-Forecasting/assets/120720408/dfb7e257-dc8a-48cc-a856-850fccadb318)

## Abstract

This project focuses on predictive sales forecasting for a mobile shop using time series analysis and two different modeling approaches: FBProphet and XGBoost. The objective is to develop accurate forecasting models to gain insights into future sales trends and improve business decision-making. The FBProphet model achieved a MAPE of 0.12%, while XGBoost obtained a significantly lower MAPE of 0.11%. The study emphasizes the value of leveraging advanced machine learning models to enhance business analytics and optimize inventory management in the dynamic mobile market landscape.

## Objective

The objective of this project is to develop accurate sales forecasting models for a mobile shop using time series analysis. The study employs two distinct approaches, FBProphet and XGBoost, to predict future sales trends. By comparing the models' performance in terms of Mean Absolute Percentage Error (MAPE), the project aims to identify the most suitable forecasting technique.

## XGBoost Model

### Exploratory Data Analysis

In this section, we perform exploratory data analysis on the historical sales data of the mobile shop to understand the underlying patterns and trends.

Data Distribution
![1](https://github.com/Aravinth-Megnath/Time-Series-Forecasting/assets/120720408/9cbd80a0-35d8-4228-9075-1b235298551b)

### Time Series Cross-Validation: Train-Test Splits Visualization

The dataset is split into training and test sets using time series split to ensure that the model is evaluated on future time periods.

We visualize the train-test splits in the time series cross-validation to understand how the data is split for model evaluation.

![2](https://github.com/Aravinth-Megnath/Time-Series-Forecasting/assets/120720408/772d7fd4-8a24-4249-a9cd-2c03022b0976)

### Revenue by Day of Week: Box Plot

![revenue by day of week](https://github.com/Aravinth-Megnath/Time-Series-Forecasting/assets/120720408/ee7250dd-2b3c-4abf-9fa4-adb6c11e2371)

### Cross Validation

We apply cross-validation to evaluate the XGBoost model's performance and compute relevant evaluation metrics.

![cross validation](https://github.com/Aravinth-Megnath/Time-Series-Forecasting/assets/120720408/076d8aaf-1d4c-4d6c-85b0-48ae64d817ba)

### Hyperparameter Tuning

Hyperparameter tuning is performed using RandomizedSearchCV to find the best set of parameters for the XGBoost model.

![hyper](https://github.com/Aravinth-Megnath/Time-Series-Forecasting/assets/120720408/ce563cd1-7da2-4878-b7ae-3cc0b4c64120)

### Future Sales Predictions

This plot allows us to visualize the forecasted sales values for future dates in the mobile shop dataset, providing valuable insights for business planning and decision-making.

![Future predictions XG](https://github.com/Aravinth-Megnath/Time-Series-Forecasting/assets/120720408/a0b4f193-eb39-41bc-8a86-7d9ecc8f10ad)

The XGBoost model is trained on the entire dataset, and future sales predictions are made for a specific period.

The XGBoost model's predictions are compared to the actual test dataset to assess its forecasting accuracy.

### Comparison of Daily Sales Data and Predictions

The XGBoost model's predictions are compared to the actual test dataset to assess its forecasting accuracy.
We visually compare the daily sales data with the XGBoost model's predictions to understand the model's performance.

![prediction on test](https://github.com/Aravinth-Megnath/Time-Series-Forecasting/assets/120720408/dd97776d-aeb4-4f97-92c3-a4290a44d0d8)

### Model Evaluation

The XGBoost model is evaluated using various metrics such as Mean Absolute Percentage Error (MAPE), Mean Squared Error (MSE), and R-squared to quantify its forecasting accuracy.

## FBProphet Model

### Exploratory Data Analysis

![h](https://github.com/Aravinth-Megnath/Time-Series-Forecasting/assets/120720408/ed5c5a83-a75f-450b-9430-97ce0d3ee909)

Similar to the XGBoost model, we perform exploratory data analysis on the historical sales data using FBProphet.

### Feature Engineering

Feature engineering is conducted to create additional time-related features essential for FBProphet's forecasting capabilities.

### Train - Test Split

![fb train test split](https://github.com/Aravinth-Megnath/Time-Series-Forecasting/assets/120720408/4ee504e4-d2e1-41c6-91a6-af14b7371f78)

The dataset is split into training and test sets for evaluating the FBProphet model's performance.

### Model Fitting

The FBProphet model is fitted on the training dataset to capture seasonality, trends, and holidays in the sales data.

### Model Prediction

Future sales predictions are made using the fitted FBProphet model.

![fb forecast](https://github.com/Aravinth-Megnath/Time-Series-Forecasting/assets/120720408/d3a2a871-f334-49c0-9520-e37a01ec6b8b)

![fb components](https://github.com/Aravinth-Megnath/Time-Series-Forecasting/assets/120720408/201eb5ff-9807-4baf-9a62-0058a5bd1705)

### Comparing Forecast to Originals

We compare the FBProphet model's forecasts to the original sales data to assess its accuracy.

![forecst to original](https://github.com/Aravinth-Megnath/Time-Series-Forecasting/assets/120720408/2d60d64c-8ee1-4b5c-83c5-819d408cdde6)

![jan forecat to originals](https://github.com/Aravinth-Megnath/Time-Series-Forecasting/assets/120720408/80ad3d26-17d8-4588-8d0e-5a49d0812297)

### Model Evaluation

The FBProphet model's performance is evaluated using cross-validation and relevant evaluation metrics.

### Future Prediction

We utilize the trained FBProphet model to predict future sales for a specific period.

## Conclusion

Based on the evaluation results, we conclude that the XGBoost model outperforms FBProphet in terms of forecasting accuracy. The XGBoost model's significantly lower MAPE showcases its potential for optimizing inventory management, aiding business decision-making, and gaining valuable insights into future sales trends in the dynamic mobile market landscape.

For more detailed insights and code implementation, please refer to the Jupyter Notebooks provided in this repository.


## Feedback

Your feedback is important to me! If you have any suggestions, questions, or feedback regarding this project, please feel free to reach out to me at:

- Email: [aravinthmegnath@gmail.com]
- [![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue.svg)](https://www.linkedin.com/in/aravinth-meganathan-200667a1/)

I appreciate your valuable input and look forward to hearing from you!
