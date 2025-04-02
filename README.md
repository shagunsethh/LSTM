# Nifty50 & WIPRO Stock Price Prediction Dataset

## Overview
This dataset consists of historical stock price data for Nifty50 and WIPRO, sourced from Yahoo Finance and NSE India. It is designed for training and evaluating machine learning models, specifically LSTM-based deep learning models, to forecast stock prices based on past trends.

## Features
- **Date** - Trading date.
- **Open, High, Low, Close Prices** - Daily stock price fluctuations.
- **Volume** - Number of shares traded per day.
- **Moving Averages (50-day, 200-day)** - Long-term trend indicators.
- **RSI (Relative Strength Index) & MACD (Moving Average Convergence Divergence)** - Momentum indicators for market trends.
- **Volatility Metrics** - Standard deviation of stock returns to analyze market fluctuations.
- **Technical Indicators** - Bollinger Bands, exponential moving averages for deeper market insights.

## Usage
1. Load the dataset into a Pandas DataFrame:
```python
import pandas as pd
df = pd.read_csv('nifty50_wipro_stock_data.csv')
print(df.head())
```
2. Perform exploratory data analysis (EDA) to visualize trends:
```python
import matplotlib.pyplot as plt
df['Close'].plot(title='Stock Closing Prices')
plt.show()
```
3. Train an LSTM model for stock price prediction.

## Installation
To set up the environment, install the necessary libraries:
```bash
pip install numpy pandas matplotlib tensorflow keras scikit-learn
```

## Applications
- **Algorithmic Trading**: Use predictive models to automate stock buying/selling.
- **Risk Management**: Identify potential risks using volatility and trend analysis.
- **Investment Strategies**: Backtest strategies using historical price movements.

## Future Enhancements
- Integration of **real-time stock data** for live trading applications.
- Implementation of **sentiment analysis** from financial news and social media.
- Exploration of **Transformer-based models** for improved sequence forecasting.

## License
This dataset is intended for research and educational purposes only.

## Contributors
- Shagun Seth(055042)
- Sweta Behera(055051)
