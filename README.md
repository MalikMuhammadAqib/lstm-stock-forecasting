# LSTM Stock Price Direction & Forecasting

## Overview
This project demonstrates how deep learning (LSTM) can be applied to financial
time-series data to predict next-day stock price direction and forecast short-term trends.

**Stock:** Apple Inc. (AAPL)  
**Data Source:** Tiingo API  
**Model:** Stacked LSTM  

## Objectives
- Predict whether the next day's closing price goes up or down
- Capture temporal patterns using LSTM
- Produce short-horizon trend forecasts (exploratory)

## Tech Stack
- Python
- Pandas, NumPy
- TensorFlow / Keras
- Scikit-learn
- Matplotlib

## Project Structure
lstm-stock-forecasting/
│
├── data_collection.ipynb
├── feature_engineering.ipynb
├── lstm_model.ipynb
├── forecasting.ipynb
├── forecast_results.csv
└── README.md
## Key Insights
- Financial markets are noisy; prediction accuracy is intentionally modest
- LSTM captures short-term momentum and volatility patterns
- This project is for educational and analytical purposes, not trading advice

## Limitations
- No sentiment or macroeconomic data
- Transaction costs not modeled
- Market efficiency constraints

## Author
Aqib
