# Time-Series-Forecasting
Time series forecasting of Tesla stock price using ARIMA and SARIMA models with error metric evaluation.
# Tesla Stock Price Time Series Forecasting

This project applies classical time series forecasting models—**ARIMA** and **SARIMA**—to predict the stock price movements of **Tesla Inc. (TSLA)** using daily closing price data.

Stock Dataset was scraped from the web using Alpha Vantage

## Objectives

- Forecast Tesla’s stock closing price using historical data
- Compare ARIMA and SARIMA model performance
- Evaluate forecasting accuracy using standard error metrics

## Tools & Techniques

- **Libraries**: Pandas, Matplotlib, Seaborn, Statsmodels, pmdarima
- **Models**: ARIMA, SARIMA
- **Data Transformations**:
  - Differencing
  - Box-Cox Transformation
  - ACF/PACF Plot Analysis

## Workflow

1. Load and clean Tesla stock data
2. Perform stationarity tests and apply transformations
3. Select optimal ARIMA/SARIMA parameters (using AIC/BIC)
4. Forecast and evaluate using MAE, RMSE, MAPE

## Output

Both ARIMA and SARIMA models were implemented and compared. Forecast accuracy was assessed with multiple error metrics, highlighting the trade-offs between simplicity and seasonal fit. The project illustrates the application of statistical time series models in real-world financial forecasting.

---
