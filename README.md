#  Stock Price Forecasting & Portfolio Optimization

A dual-purpose project that performs **stock price forecasting** using the ARIMA model and **portfolio optimization** using Modern Portfolio Theory. It uses real-time financial data for practical and statistical analysis of investments.

---

## Technologies Used

- Python
- yfinance
- pandas
- matplotlib
- scikit-learn
- statsmodels
- scipy

---

## Features

- ARIMA-based time series forecasting for Apple (AAPL) stock.
- Portfolio optimization using Sharpe Ratio maximization.
- Efficient Frontier plotted with 5000 random portfolios.
- Visualization of actual vs predicted prices.
- Performance evaluation using MAE, RMSE, and Sharpe Ratio.

---

## Installations Required

```
pip install yfinance numpy pandas matplotlib scipy scikit-learn statsmodels
```

---

## Time Series Forecasting (ARIMA)

- **Stock**: AAPL (Apple Inc.)
- **Date Range**: 2015-01-01 to 2023-01-01
- **Model**: ARIMA(5, 1, 0)
- **Train/Test Split**: 80/20

## Evaluation Metrics

| Metric | Value  |
|--------|--------|
| MAE    | 25.80  |
| RMSE   | 28.91  |

---

## Portfolio Optimization

- **Assets**: AAPL, MSFT, GOOG, AMZN
- **Optimization Objective**: Maximize Sharpe Ratio
- **Constraints**:
  - No short selling (weights between 0 and 1)
  - Total portfolio weight = 100%

## Optimal Portfolio Allocation

| Ticker | Allocation (%) |
|--------|----------------|
| AAPL   | 27.84%         |
| MSFT   | 21.90%         |
| GOOG   | 0.00%          |
| AMZN   | 50.26%         |

- **Sharpe Ratio**: 0.9095

---

## Visuals Included

* Actual vs Forecasted AAPL Stock Prices (ARIMA)

* Efficient Frontier with Optimal Portfolio Highlighted

* Historical AAPL Stock Price Plot (2015–2023)

---

## Skills Demonstrated

- Financial time series modeling
- Portfolio theory and investment strategy
- Data cleaning, transformation, and visualization
- Working with real-world financial APIs
- Optimization using SciPy
