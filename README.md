**Forecasting Active Listing Counts Using Multiple Models**

**Introduction:**

In this project, I have undertaken the task of forecasting active listing counts in the real estate market using various time series and regression-based models. The goal is to evaluate the performance of these models and determine the best approach for accurate forecasting.

**Models Utilized:**

1. **Time-Based Models:**
   - ARIMA (AutoRegressive Integrated Moving Average)
   - ETS (Exponential Smoothing State Space Model)
   - Seasonal Naive
   - Random Walk

2. **Regression-Based Models:**
   - Regression model incorporating total median square footage as a predictor variable.

**Correlation Analysis:**

The correlation graph below highlights the relationship between active listing counts and total median square footage, showing a significant correlation that justifies the use of square footage as a predictor in the regression model.
![Correlation Graph](https://github.com/karthikvibuthi/House-Listings-Forecasts/assets/141452458/7fe24529-a802-4c2c-8143-2dbe756ffcaf)

**Performance Evaluation:**

- **Test Data Performance:**
  - The Seasonal Naive and Regression models demonstrated superior performance on the test dataset, indicating their robustness in handling unseen data.

- **Train Data Performance:**
  - The ARIMA models excelled in fitting the training data, suggesting strong capabilities in capturing patterns within the historical data.

**Forecasts:**

The forecast plots for both time-based and regression models are shown below, illustrating the predicted active listing counts over time.

- **Time-Based Models Forecast:**
  ![Time Based Models](https://github.com/karthikvibuthi/House-Listings-Forecasts/assets/141452458/5c484cfa-1540-462f-91d9-4fa4fd2c1f64)

- **Regression Models Forecast:**
  ![Regression Models](https://github.com/karthikvibuthi/House-Listings-Forecasts/assets/141452458/b3a9e272-ce18-4e27-bd8b-390dd60ae075)

**Accuracy Comparison:**

The accuracy of the models was evaluated using appropriate metrics. Below are the accuracy comparison charts for both regression and time-based models.

- **Regression Model Accuracy:**
  ![Regression Model Accuracy](https://github.com/karthikvibuthi/House-Listings-Forecasts/assets/141452458/4ea7e913-fbc5-4d99-b4c9-45d12823a878)

- **Time-Based Model Accuracy:**
  ![Time Based Model Accuracy](https://github.com/karthikvibuthi/House-Listings-Forecasts/assets/141452458/b92e8afb-f9c5-4a34-b0aa-48f8bc5ed20c)

**Conclusion:**

This project demonstrates the effectiveness of integrating additional predictor variables, such as total median square footage, into forecasting models. While time-based models like ARIMA are excellent for capturing historical patterns, incorporating relevant predictors can enhance model performance on new data, as evidenced by the regression and seasonal naive models.

**Future Work:**

Further research could explore the inclusion of more predictor variables and advanced machine learning techniques to improve forecast accuracy. Additionally, model performance can be enhanced by fine-tuning parameters and exploring hybrid models that combine the strengths of both time series and regression approaches.
