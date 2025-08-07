# 📈 Time Series Forecasting – Apple Stock Prices (ARIMA Model)

This project showcases time series analysis and forecasting of Apple Inc. (AAPL) stock prices using ARIMA models.

## 📌 Objective
To forecast stock closing prices by:
- Decomposing the time series to understand trend and seasonality
- Applying smoothing techniques (Moving Average & Exponential Smoothing)
- Building an ARIMA model for future predictions
- Evaluating model performance using RMSE
- Visualizing actual vs predicted stock trends

## 🛠️ Tools & Libraries
- Python
- yfinance
- pandas
- matplotlib
- seaborn
- statsmodels
- scikit-learn

## 🔍 Key Steps
1. **Data Collection:** AAPL stock prices from Yahoo Finance (2018–2023)
2. **Decomposition:** Extracting trend, seasonality, and residual components
3. **Smoothing:** Using Moving Average and Exponential Smoothing to remove noise
4. **Modeling:** Building and fitting an ARIMA(5,1,2) model
5. **Evaluation:** RMSE score used to measure model accuracy
6. **Visualization:** Train/Test/Forecast plots for clear interpretation


## 📁 Dataset
- [Apple Stock Data (AAPL)](https://finance.yahoo.com/quote/AAPL/)

## 📎 References
- [ARIMA Theory](https://en.wikipedia.org/wiki/Autoregressive_integrated_moving_average)
- [Statsmodels ARIMA Docs](https://www.statsmodels.org/stable/generated/statsmodels.tsa.arima.model.ARIMA.html)
- [Yahoo Finance Python API](https://pypi.org/project/yfinance/)
