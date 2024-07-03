# Exchange-Rate-Forecast-USD-INR
modelling and forecasting exchange rates

Objective:
The objective of this project was to develop robust models for predicting exchange rates (INR/USD) using three different methods and subsequently evaluating their performance metrics.

Approach:
1. Data Preprocessing:
   - Z-score normalization was applied to the data to standardize it.
   - Correlation matrices were utilized to visualize relationships and identify trends among the variables.

2. Multicollinearity Analysis:
   - Variance Inflation Factor (VIF) analysis was conducted to assess multicollinearity.
   - The analysis identified and addressed potential redundancy among predictors, enhancing the model's reliability.

3. Variable Selection:
   - Independent variables like GDP growth, Trade Deficit (% of GDP), FDI (% GDP), Inflation, Real Interest Rates, Crude Oil Price (dollar per barrel) were considered.
   - Variables with high correlation with the target variable and VIF scores less than 5 were retained, while Population Growth and Total Reserves were excluded.

4. Model Implementation:
   - Time series forecasting models, including ARIMA and ARMA, were implemented.
   - Multiple Linear Regression was employed for predicting exchange rates.
   - The performance of each model was evaluated using metrics such as MAE, RMSE, and MAPE.

   - Linear Regression Performance:
     - Achieved an impressive R-squared value of 0.96, indicating a strong linear relationship between predictors and the exchange rate.
     - The adjusted R-squared value, considering model complexity, was around 0.7.

   - Time Series Models (ARIMA, ARMA):
     - ARIMA outperformed other models, exhibiting the lowest RMSE, MAE, and MAPE.ARIMA performed better than the ARMA because of the extra differencing as the data was not stationary and that differencing step made the data stationary,which is required for the ARIMA model.
     - This suggests that the time series components captured by ARIMA contributed significantly to accurate predictions.

   - ANN (Artificial Neural Network):
     - Attempted to use ANN for prediction, but no big difference compared to linear regression.

Conclusion:
   - The project demonstrated the effectiveness of various models in predicting exchange rates.
   - Linear regression showcased a strong linear relationship, while time series models, especially ARIMA, excelled in forecasting accuracy .

Outcome:
   - Linear Regression Performance:
     - Achieved an impressive R-squared value of 0.96, indicating a strong linear relationship between predictors and the exchange rate.
     - The adjusted R-squared value, considering model complexity, was around 0.7.

   - Time Series Models (ARIMA, ARMA):
     - ARIMA outperformed other models, exhibiting the lowest RMSE, MAE, and MAPE.ARIMA performed better than the ARMA because of the extra differencing as the data was not stationary and that differencing step made the data stationary,which is required for the ARIMA model.
     - This suggests that the time series components captured by ARIMA contributed significantly to accurate predictions.

   - ANN (Artificial Neural Network):
     - Attempted to use ANN for prediction, but no big difference compared to linear regression.

Conclusion:
   - The project demonstrated the effectiveness of various models in predicting exchange rates.
   - Linear regression showcased a strong linear relationship, while time series models, especially ARIMA, excelled in forecasting accuracy .
