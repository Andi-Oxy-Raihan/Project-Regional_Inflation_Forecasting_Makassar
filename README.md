# Project-regional_inflation_forecasting_indonesia

notebook link: https://www.kaggle.com/code/andioxy/dmy-2-makassar-inflation-time-series-analysis

## Project Overview
This repository contains an end-to-end Data Science project analyzing **30 years of makassar city inflation data** in Indonesia. The project transitions from historical data cleaning to advanced time series forecasting using the **SARIMA** model.

The goal is to understand historical economic shocks (like the 1998 crisis) and provide a data-driven projection for inflation trends in **2026**.

## 🚀 Key Features
- **Data Preprocessing:** Transforming wide-format BPS (Bureau of Statistics) tables into long-format time series.
- **Statistical Analysis:** Stationarity testing using the **Augmented Dickey-Fuller (ADF) Test**.
- **Visual Storytelling:** Stacked bar plots and seasonal decomposition to visualize 3 decades of economic shifts.
- **Forecasting:** Predictive modeling for the next 12 months using **SARIMA (Seasonal ARIMA)**.

## 📊 Dataset
- **Source:** [BPS Indonesia](https://www.bps.go.id)
- **Period:** January 1995 - December 2025
- **Frequency:** Monthly

## 🛠️ Tech Stack
- **Language:** Python 3.x
- **Libraries:** - `pandas` & `numpy` (Data Manipulation)
  - `matplotlib` & `seaborn` (Visualization)
  - `statsmodels` (Statistical Testing & Decomposition)
  - `pmdarima` (Auto-ARIMA Modeling)

## 📈 Key Insights
### 1. The 1998 Hyperinflation Spike
The analysis highlights the massive outlier in 1998, where monthly inflation reached **14.78%** due to the Asian Financial Crisis.
### 2. Stationarity Confirmed
Despite historical volatility, the ADF Test confirmed that the data is stationary ($p < 0.05$), allowing for reliable long-term forecasting.
### 3. Seasonal Patterns
Inflation peaks consistently align with year-end holidays and religious festivities, suggesting that consumption-driven inflation is a dominant recurring factor.
