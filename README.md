# 📈 Stock Price Forecasting using TS + ML + DL Ensemble

## Overview
This project builds an end-to-end stock forecasting pipeline using:
- Time Series models (ARIMA)
- Machine Learning (Random Forest)
- Deep Learning (LSTM)
- Walk-Forward Optimization
- Ensemble learning
- Strategy backtesting

The model predicts **next-day log returns**, which are converted into trading signals and expected prices.

---

## Methodology
1. Time Series Analysis & Stationarity (ADF)
2. ARIMA modeling with Walk-Forward Optimization
3. Feature engineering from log returns
4. Random Forest forecasting with WFO
5. LSTM sequence modeling
6. Stacked ensemble (ARIMA + RF + LSTM)
7. Backtesting with Sharpe ratio & drawdowns
8. Paper trading framework

---

## Key Results
- Random Forest outperformed Gradient Boosting
- LSTM slightly outperformed RF individually
- Ensemble achieved best RMSE
- Backtesting used to evaluate economic value

---

## Disclaimer
This project is for **educational and research purposes only**.
Not financial advice.

---

## Tech Stack
Python, Pandas, NumPy, scikit-learn, statsmodels, TensorFlow, yfinance
