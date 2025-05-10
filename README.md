# BTC Price Prediction with LSTM

This project demonstrates how to build a deep learning model using LSTM (Long Short-Term Memory) to predict the future open prices of Bitcoin (BTC) using historical OHLCV data from Binance.

## Features

- Fetches hourly OHLCV data for BTC/USDT from Binance API
- Preprocesses and normalizes data for LSTM input
- Builds and trains a multi-variate ("open", "high", "low", "close", "volume") LSTM model
- Predicts future 90 days BTC open prices
- Visualizes predictions alongside actual prices
- Evaluates model using metrics like MAPE

## Dependencies

Install dependencies using:

```bash
pip install -r requirements.txt
```
