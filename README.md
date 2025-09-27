# Air-quality-index-prediction-using-LSTM

This project predicts the Air Quality Index (AQI) proxy via PM2.5 levels of a city in China using a Long Short-Term Memory (LSTM) neural network. LSTM is well-suited for time series data, making it effective for forecasting pollutant trends over time.

## Project Overview

- Implements a univariate LSTM model using PM2.5 concentration values.

- Performs exploratory data analysis (EDA) and visualization to understand pollutant trends.

- Uses time series data spanning 4 years for training and testing.

- Evaluates model performance with error metrics (e.g., Mean Squared Error).

## Dataset

Timeframe: January 1, 2013 → February 28, 2017.

Features:

- Pollutant used for modeling: PM2.5 (hourly values).

- Other pollutants and environmental conditions (PM10, SO₂, NO₂, CO, O₃, temperature, pressure, dew point, rainfall, wind direction, wind speed) are available in the dataset but not included in this notebook’s LSTM model.

## Key steps:

- Load and clean the dataset.

- Conduct exploratory analysis and visualizations.

- Normalize and split PM2.5 time series for training/testing.

- Build and train a univariate LSTM model.

- Evaluate predictions using test data.

## Technologies Used

Python

- Pandas, NumPy → data processing

- Matplotlib, Seaborn → visualization

- TensorFlow / Keras → LSTM modeling

- Scikit-learn → preprocessing & evaluation

## Results

- The univariate LSTM model learns temporal dependencies in PM2.5 levels.

- Predictions closely follow actual test sequences with some variance.

- To avoid long outputs, only the first 5 entries of predicted arrays are displayed.


