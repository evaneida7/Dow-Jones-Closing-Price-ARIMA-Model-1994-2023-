## 📊 Dow Jones Closing Price Forecasting (ARIMA, 1994–2023)
This project performs a time series analysis of Dow Jones monthly closing prices (1994–2023) using ARIMA models in R. The workflow includes data cleaning, aggregation, stationarity analysis, model selection, and forecasting/predictions. 

## ⚙️ Methods

- Time series visualization
- Box-Cox transformation
- ACF and PACF analysis
- First differencing for stationarity
- ARIMA model selection using AIC/BIC
- Forecasting using ARIMA(0,1,1)

# 📊 Visualizations

# Log of Dow Jones Monthly Closed Price
This plot shows the long-term upward movement in the Dow Jones monthly closing price series after log transformation.

Log of Dow Jones Monthly Closed Price

#ARIMA Forecast Plot
This forecast plot shows projected Dow Jones monthly closing prices for the next 12 to 24 months based on the selected ARIMA model.

ARIMA Forecast Plot


<img width="603" height="352" alt="Screenshot 2026-04-07 213714" src="https://github.com/user-attachments/assets/ae3e39e1-b4da-401f-8c5c-ce43ed6f3488" />

# Forecasted Values year 2024/2025
The following output shows the predicted Dow Jones monthly closing prices after transforming forecasts back to the original scale.

Forecast Values

<img width="686" height="117" alt="Screenshot 2026-04-07 213357" src="https://github.com/user-attachments/assets/10d926d4-13e3-4b61-80b5-0c022c795df7" />

#PACF of Differenced Log Series
This partial autocorrelation plot was used to help identify candidate ARIMA terms during model selection.

PACF Plot
<img width="616" height="348" alt="Screenshot 2026-04-07 213309" src="https://github.com/user-attachments/assets/83e0312b-6a6c-418f-8344-94a6225e9102" />

---
## 📈 Results

- The original series was non-stationary and required differencing
- ARIMA(0,1,1) provided the best fit based on AIC/BIC
- Log transformation improved variance stability
- Forecasts indicate continued trend behavior

---
## 🚀 How to Run
1. Open R
2. Load required libraries
3. Import dataset
4. Run script sequentially
