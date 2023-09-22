# Statistical Time Series Models

This README file provides an overview of some fundamental statistical models used in time series analysis. These models are used to analyze time series data, make forecasts, and predict the future.

## 1. SES (Simple Exponential Smoothing)

- **Definition**: Simple Exponential Smoothing is a method that uses a basic exponentially weighted moving average. It relies only on current values and adjusts its weights based on the data.
- **Features**: Useful for single-variable forecasts.

## 2. DES (Double Exponential Smoothing)

- **Definition**: Double Exponential Smoothing is a second-order exponentially weighted moving average method. It is used to forecast both current values and trends.
- **Features**: Includes forecasts for both the trend and current values.

## 3. TES (Triple Exponential Smoothing)

- **Definition**: Triple Exponential Smoothing is a third-order exponentially weighted moving average method. It includes forecasts for current values, trends, and seasonal components.
- **Features**: Used for forecasting time series with trends and seasonality.

## 4. AR (AutoRegressive)

- **Definition**: The AutoRegressive model relates current values to previous values. It relies on past values to make forecasts.
- **Features**: Makes predictions based on the time series' historical values.

## 5. MA (Moving Average)

- **Definition**: The Moving Average model relates current values to previous forecast errors. It relies on past errors to make forecasts.
- **Features**: Makes predictions based on the time series' past errors.

## 6. ARMA (AutoRegressive Moving Average)

- **Definition**: The AutoRegressive Moving Average model combines both auto-regressive and moving average terms. It utilizes both past values and past errors for predictions.
- **Features**: Includes both auto-regressive and moving average components.

## 7. ARIMA (AutoRegressive Integrated Moving Average)

- **Definition**: The AutoRegressive Integrated Moving Average model uses previous values, differences, and errors. The integration process helps make the data stationary.
- **Features**: Ensures stationarity in time series data.

## 8. SARIMA (Seasonal AutoRegressive Integrated Moving Average)

- **Definition**: The Seasonal AutoRegressive Integrated Moving Average model extends ARIMA by adding seasonal components. It is used to predict seasonal patterns in time series data.
- **Features**: Includes both seasonal and stationary components.

