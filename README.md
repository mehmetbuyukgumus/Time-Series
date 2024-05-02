# Intoduction

This repo includes codes, methods, functions while i was learning Time Series.


# [Smoothing Methods](smoothing_methods.py)

**Moving Averages**: This method involves calculating the average of a fixed number of consecutive data points, called the window size, and using this average to smooth out fluctuations in the data. Moving averages can be simple (SMA) or weighted (WMA), where more recent data points have higher weights.

Exponential Smoothing: Exponential smoothing assigns exponentially decreasing weights to past observations, with the weights decreasing exponentially as observations get older. This method is particularly useful for capturing trends and seasonality in the data.

**Holt-Winters Method**: Also known as triple exponential smoothing, this method extends exponential smoothing to capture both trend and seasonality in the data. It consists of three components: level (average value), trend (rate of increase or decrease), and seasonality (repeating pattern).


# [Statistical Moethods](statistical_methods.py)
**Descriptive Statistics**: Descriptive statistics involve summarizing and describing the characteristics of the time series data. This includes measures such as mean, median, standard deviation, variance, skewness, and kurtosis.
Autocorrelation and Partial Autocorrelation Analysis: Autocorrelation measures the correlation between a time series and its lagged values. Partial autocorrelation analysis helps identify the direct relationship between observations at different lags after removing the effects of intervening observations.

**Time Series Decomposition**: Time series decomposition separates a time series into its constituent components, such as trend, seasonality, and residual (or noise). Common methods for decomposition include additive decomposition and multiplicative decomposition.

**Hypothesis Testing**: Hypothesis testing techniques are used to make inferences about the parameters or characteristics of time series data. This includes tests for stationarity, unit roots (e.g., Augmented Dickey-Fuller test), and goodness-of-fit tests for models.

**Time Series Modeling**: Time series modeling involves building statistical models to capture and forecast the behavior of the time series data. This includes models such as autoregressive integrated moving average (ARIMA), seasonal ARIMA (SARIMA), autoregressive integrated moving average with exogenous variables (ARIMAX), and vector autoregression (VAR).

**Probabilistic Forecasting**: Probabilistic forecasting techniques provide not only point forecasts but also prediction intervals that quantify the uncertainty associated with the forecasts. Bayesian methods, Monte Carlo simulations, and bootstrapping are examples of probabilistic forecasting techniques.

**Time Series Clustering and Classification**: Clustering and classification techniques are applied to time series data to identify similar patterns or group similar time series together based on their characteristics. Methods such as k-means clustering, hierarchical clustering, and dynamic time warping (DTW) are commonly used for this purpose.

## [Exercise Airline Passenger](exercies_airline_passenger.py)
An exercise with the methods what i have learned


## [Demand Frecasting](demand_forecasting.py)
Prediction next time series with machine learning methods.

# Run
```bash
pip install requirements.txt
```