# Time Series Forecasting with LSTM (Stock Price Prediction)

This project demonstrates a complete end-to-end time series forecasting pipeline using an LSTM (Long Short-Term Memory) neural network to predict stock prices. It downloads historical price data using `yfinance`, preprocesses and scales the data, constructs time-series sequences, trains a deep LSTM model in Keras, and visualizes the resulting predictions.

## Project Overview

**Goal:** Forecast a stock’s future closing prices using historical closing price data.  
**Model:** Stacked LSTM neural network (Keras / TensorFlow backend)  
**Data Source:** Yahoo Finance via `yfinance`

---

## Features

- Downloads stock price data automatically using Yahoo Finance
- Uses `MinMaxScaler` normalization for stable neural network training
- Creates rolling time-window sequences for supervised learning
- Trains a stacked LSTM model with dropout / batch norm options
- Visualizes actual vs predicted prices

---

## Tech Stack

- Python
- NumPy, Pandas
- Matplotlib
- scikit-learn (`MinMaxScaler`)
- `yfinance`
- Keras (Sequential model, LSTM layers)

---

## File Structure

- `nsdc_timeseriesforecasting.py`  
  Main pipeline script (converted from notebook)

(Optional but recommended)
- `README.md`  
  Project documentation

---

## Installation

Create a virtual environment (recommended):

```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```

Install dependencies:
pip install numpy pandas matplotlib scikit-learn yfinance tensorflow keras
```bash
pip install numpy pandas matplotlib scikit-learn yfinance tensorflow keras
```
