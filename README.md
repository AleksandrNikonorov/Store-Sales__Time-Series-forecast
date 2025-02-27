# Project: Forecasting Sales Time Series at Favorita Stores

## Project Description

This project is dedicated to building a model for forecasting the sales of thousands of products across various stores in the Favorita network. Both classical time series modeling approaches and hybrid methods were used. The main goal was to predict sales volumes by considering factors such as seasonality, trends, and other temporal characteristics.

## Key Project Stages

1. **Data Preprocessing:**
   - Cleaning the data and handling missing values.
   - Creating additional features for trends, seasonal patterns, and other temporal aspects.
   - Splitting the data into training and test sets for model validation.

2. **Models and Approaches:**
   - **Classical Regression Models**: Linear regression models that account for trend, seasonality, and holiday effects, with regularization applied to prevent overfitting.
   - **Hybrid Models**: A combination of regularized linear regression and XGBoost to capture complex interactions and non-linearities.
   - **Prophet**: Utilizing the Prophet model for forecasting time series data with seasonal and holiday effects.

3. **Model Evaluation:**
   - Evaluating model performance using metrics such as MSE (Mean Squared Error), MAE (Mean Absolute Error), and RMSE (Root Mean Squared Error).
   - Visualizing forecasts against actual values to assess model adequacy.

## Libraries Used

The project was implemented using the following libraries:

- `pandas` — for data processing.
- `numpy` — for mathematical operations.
- `scikit-learn` — for implementing regression models.
- `XGBoost` — for hybrid models.
- `Prophet` — for working with time series data.
- `matplotlib` / `seaborn` — for data visualization and results presentation.
- `statsmodels`

