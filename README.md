# Stock Price Prediction (Short-Term)

This project demonstrates how to predict the **next day's closing price** of a stock using historical data from Yahoo Finance, and a regression model.

## Dataset

- Stock market data retrieved from [Yahoo Finance](https://finance.yahoo.com/)  
- Collected using the `yfinance` Python library  
- Includes fields: Open, High, Low, Close, Volume, etc.

## Requirements

- Python 3.x  
- pandas  
- scikit-learn  
- yfinance  
- matplotlib

Install dependencies:

```bash
pip install yfinance scikit-learn matplotlib pandas
````

## How It Works

1. **Select a stock symbol** (e.g., `AAPL` for Apple)
2. **Load historical stock data** for the past 2 years
3. **Prepare features**: Open, High, Low, Volume
4. **Define the target**: next day’s closing price
5. **Train a regression model** (Random Forest or Linear Regression)
6. **Evaluate the model** on test data
7. **Plot** the actual vs. predicted prices

## Results

* The trained model will output a plot showing predicted vs actual closing prices on the test set
* Mean Squared Error (MSE) is reported to assess performance

## Possible Extensions

* Add technical indicators (SMA, EMA, RSI, etc.)
* Try other models (XGBoost, LSTM)
* Predict multiple days ahead
* Incorporate sentiment data (news headlines)

## Acknowledgments

* Yahoo Finance (`yfinance` library)
* scikit-learn
* matplotlib

>  **Disclaimer**:
> This project is for educational purposes only. It is *not* intended for live trading or investment decisions.
