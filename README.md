# Cross Over Trade Simulator

## Overview
The "Cross Over Trade Simulator" is an algorithmic trading model designed to capitalize on trends identified through the moving averages of the S&P 500 index. By tracking the 10-day and 50-day rolling averages, this strategy aims to execute buy and sell orders at optimal points to maximize returns.

## Strategy
The core of the strategy involves:
- **Buying** when the 10-day rolling average (AV10) exceeds the 50-day rolling average (AV50).
- **Selling** when the AV10 falls below the AV50.

This approach is based on the premise that short-term movements above long-term trends indicate bullish conditions, while the opposite suggests bearish conditions.

## Installation

### Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- yfinance

You can install the necessary dependencies via pip:
```bash
pip install pandas numpy matplotlib yfinance
