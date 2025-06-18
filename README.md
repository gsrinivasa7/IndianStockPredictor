# 📈 Live Indian Stock Market Prediction using Machine Learning (Google Colab)

This project aims to predict the next-day closing price of Indian stock market companies using machine learning techniques in **Google Colab**. It utilizes real-time data from **Yahoo Finance (via yfinance)** for stocks listed on the **National Stock Exchange (NSE)** of India.

---

## 🔍 Features

- Live stock data fetching using `yfinance`
- Simple Linear Regression model for price prediction
- Visualization of actual vs. predicted stock prices
- Compatible with any Indian stock (e.g., RELIANCE.NS, TCS.NS, INFY.NS)
- Ready-to-run on Google Colab
- Easily extendable to advanced models (LSTM, ARIMA, etc.)

---

## 🛠️ Tools & Libraries Used

- Python
- Google Colab
- yfinance
- pandas
- scikit-learn
- matplotlib

---

## 📊 Example

Predicting the closing price of RELIANCE.NS:
```python
stock = yf.Ticker("RELIANCE.NS")
df = stock.history(period="1y")
