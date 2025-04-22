# 📈 NVIDIA Stock Price Prediction using LSTM

This project implements a Long Short-Term Memory (LSTM) neural network using TensorFlow/Keras to predict NVIDIA's stock closing prices. The model is trained on historical stock data and leverages time-series techniques to forecast future prices.

---

## 🔍 Project Overview

- **Goal:** Predict the closing stock price of NVIDIA using a deep learning model.
- **Model:** Stacked LSTM with dropout and dense layers.
- **Tools:** Python, TensorFlow/Keras, Pandas, Matplotlib, Scikit-learn.
- **Data:** Historical stock prices (`NVidia_stock_history.csv`).

---

## 🧪 Features

- ✅ Time series windowing (5-day lookback)
- ✅ Data scaling using `MinMaxScaler`
- ✅ LSTM-based neural network with dropout regularization
- ✅ Model evaluation with RMSE and MAE
- ✅ Interactive plots for prediction vs actual price
- ✅ Early stopping to prevent overfitting

---

## 📊 Sample Results

Model performance on the test set:
- **Test RMSE:** ~`4.6437`
- **Test MAE:**  ~`2.0629`
- **Standard Deviation (Actual Test Prices):** `29.1257`

---



