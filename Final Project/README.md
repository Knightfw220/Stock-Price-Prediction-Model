# Final Project: Stock Price Prediction using LSTM

## Objective
The goal of this project is to build a deep learning model using LSTMs to predict stock prices. The model will analyze historical stock data and predict the next 15 units of the stock's adjusted closing price. Additionally, the project will incorporate technical indicators to enhance prediction accuracy.

---

## Problem Statement
Build a stock price prediction system using Long Short-Term Memory (LSTM) networks. <br>
The system should:

1. **Take user input** for:
   - Stock name (e.g., "AAPL" for Apple, "GOOGL" for Alphabet Inc.).
   - Start date and end date to define the data range.
   - Timeframe (e.g., daily, weekly, monthly).

2. **Fetch stock data** from the internet using the `yfinance` library, based on the user's input.

3. **Visualize the data** by plotting:
   - Adjusted closing price of the stock.
   - At least two technical indicators (e.g., MACD, RSI, Moving Averages, Bollinger Bands).

4. **Build and train an LSTM model** to:
   - Predict the next 15 units of stock data based on historical trends.
   - Use adjusted closing price and technical indicators (Minimum 2) as input features.

5. **Present results graphically**, including:
   - Historical data and predicted prices.
   - Comparisons between actual and predicted values.

6. **Calculate the R² score** to evaluate model performance:
   - $`
     R^2 = 1 - \frac{\sum w_i (y_i - \hat{y}_i)^2}{\sum w_i y_i^2}
     `$

     where $`y_i`$
 and $`\hat{y}_i`$
 are the true value and predicted value respectively; and w
 is the sample weight vector.

---


Resources

### Tutorials
1. [LSTM Time Series Forecasting with TensorFlow](https://www.tensorflow.org/tutorials/structured_data/time_series)
2. [Technical Analysis Indicators](https://www.investopedia.com/terms/t/technicalindicator.asp)

### Documentation of Python Libraries
1. [Pandas](https://pandas.pydata.org/docs/)
2. [Matplotlib](https://matplotlib.org/stable/index.html)
3. [Tensorflow](https://www.tensorflow.org/api_docs)
4. [Scikit-learn](https://scikit-learn.org/stable/)
5. [yfinance](https://pypi.org/project/yfinance/)

### Videos
1. [Stock Price Prediction with LSTMs](https://www.youtube.com/watch?v=QIUxPv5PJOY)
2. [RNN/LSTM Price Movement Predictions](https://youtu.be/hpfQE0bTeA4?si=Y5RMAC6vz1Xf5lb1)
3. [Mistakes while using LSTM](https://youtu.be/lhrCz6t7rmQ?si=Ufds96Ln9lQIMQ38)

---

