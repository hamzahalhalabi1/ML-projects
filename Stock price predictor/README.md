# Stock Price Prediction with LSTM

This repository contains Python code that demonstrates how to predict the stock prices of NVIDIA (NVDA) using Long Short-Term Memory (LSTM) networks. LSTM is a type of recurrent neural network (RNN) architecture well-suited for sequence prediction tasks.

## Overview

The code provided here fetches historical stock price data for NVIDIA from Yahoo Finance using the `pandas_datareader` library. It preprocesses the data, scales it, and then trains an LSTM model to predict future stock prices. Finally, it evaluates the model's performance and visualizes the predicted prices against the actual prices.

## Requirements

To run this code, you need the following Python libraries:

- `pandas`
- `pandas_datareader`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `yfinance`
- `keras`

You can install these libraries using pip:

```
pip install pandas pandas_datareader numpy scikit-learn matplotlib yfinance keras
```

This script will fetch the data, train the LSTM model, make predictions, and visualize the results.

## License

This code is provided under the MIT License. Feel free to use it for educational or commercial purposes.
