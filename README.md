# Time Series Forecasting: Daily Minimum Temperatures

This project focuses on time series forecasting of daily minimum temperatures using ARIMA and LSTM models. The primary goal is to predict future temperatures based on historical data, showcasing the effectiveness of traditional statistical methods and advanced machine learning techniques.

## Dataset

The dataset used is `daily-min-temperatures.csv`, which contains daily minimum temperatures in Melbourne, Australia, from 1981 to 1990. The dataset can be downloaded from [Kaggle](https://www.kaggle.com/datasets/jbrownlee/daily-min-temperatures).

## Project Overview

1. **Data Loading and Visualization**:
    - Load the dataset and visualize the time series.
2. **Time Series Decomposition**:
    - Decompose the time series to observe trend, seasonality, and residuals.
3. **Stationarity Test**:
    - Conduct the Augmented Dickey-Fuller test to check for stationarity.
4. **Differencing**:
    - Difference the time series to make it stationary, if necessary.
5. **ARIMA Model**:
    - Fit an ARIMA model to the training data and make forecasts.
6. **Data Scaling and Preparation for LSTM**:
    - Scale the data and prepare it for the LSTM model.
7. **LSTM Model**:
    - Build and train an LSTM model on the training data.
8. **Predictions and Evaluation**:
    - Make predictions using the trained LSTM model and evaluate performance.

## Technologies Used

- **Python**: For general programming and scripting.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For data visualization.
- **Statsmodels**: For statistical modeling, specifically ARIMA.
- **Keras**: For building and training the LSTM model.
- **Scikit-learn**: For data preprocessing and performance evaluation.

## Installation

To run this project, you need to have Python installed along with the following libraries:

```bash
pip install pandas numpy matplotlib statsmodels keras scikit-learn
