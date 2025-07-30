# Tesla Stock Price Prediction (Short-Term)

This project predicts the **next day's closing price** of Tesla Inc. (TSLA) using historical stock market data. It leverages features like Open, High, Low, and Volume and applies machine learning models to forecast future prices.

---

##  Objective

- Fetch historical stock data for **Tesla (TSLA)** using the `yfinance` Python library.
- Use features such as **Open**, **High**, **Low**, and **Volume** to predict the **next day's Close price**.
- Train a **Linear Regression** or **Random Forest Regressor**.
- Plot actual vs predicted values to evaluate the model.

---

##  Tools & Libraries

- `yfinance` – Fetch real-time and historical stock data
- `pandas` – Data manipulation
- `scikit-learn` – Machine learning models and evaluation
- `matplotlib` & `seaborn` – Visualization

---

##  Dataset

Stock data for **Tesla (TSLA)** is fetched directly using the [Yahoo Finance API](https://www.yahoofinance.com) via the `yfinance` library:

