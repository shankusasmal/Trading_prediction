# Algorithmic Trading Project

## Overview
This project implements an algorithmic trading strategy using machine learning. The strategy predicts stock price movements based on technical indicators and backtests the performance using historical stock data.

## Requirements
Ensure you have Python installed along with the following dependencies:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost ta
```

## Dataset Download (Kaggle)
You need a stock price dataset, which can be obtained from Kaggle:

1. Go to [Kaggle](https://www.kaggle.com/).
2. Search for stock price datasets (e.g., "Apple stock historical data").
3. Download the dataset and save it locally (e.g., `AAPL_daily_update.csv`).
4. Update the file path in the script:
   ```python
   file_path = '/your/local/path/AAPL_daily_update.csv'
   ```

## Running the Project
To execute the trading prediction:

```bash
python algorithmic_trading.py
```

## Features
- **Technical Indicators:** SMA, RSI, MACD
- **Machine Learning Models:** Logistic Regression, Random Forest, XGBoost
- **Backtesting Strategy:** Predicts buy/sell signals and evaluates strategy performance

## Output
- Displays model accuracy.
- Prints the last 10 Buy/Sell signals.
- Optimizes the model using GridSearchCV.

## Notes
Ensure your dataset contains a `Date` column and price features such as `Close`, `High`, and `Low` for correct processing.
 

