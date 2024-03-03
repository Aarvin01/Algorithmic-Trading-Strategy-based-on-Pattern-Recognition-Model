## Algorithmic Trading Strategy based on Pattern-Recognition Model
# Overview

This project implements an algorithmic trading strategy using machine learning techniques. It leverages financial data fetched from Yahoo Finance API, preprocesses the data, computes various technical indicators, generates trading signals, trains a Random Forest Classifier model, and backtests the strategy on multiple stocks.

# Features
Fetches historical financial data using Yahoo Finance API.

Preprocesses data by calculating candlestick shapes, relative positions, and technical indicators such as EMA, VWAP, ATR, and Bollinger Bands.

Generates buy/sell signals based on computed indicators.

Trains a Random Forest Classifier model using a randomized search for hyperparameter tuning.

Evaluates model performance using accuracy score and classification report.

Backtests the strategy by simulating trades and calculating returns.

Visualizes performance metrics such as Sharpe Ratio and Drawdown.
