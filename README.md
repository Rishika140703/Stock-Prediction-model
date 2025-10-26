# Stock Price Prediction using LSTM and Sentiment Analysis

This project leverages **Deep Learning (LSTM)** and **Natural Language Processing (NLP)** to predict future stock prices by combining historical data with news sentiment. The model integrates financial time series data and real-world news sentiment to enhance the accuracy of predictions.

---

## Project Overview

The goal of this project is to predict short-term stock price trends for major tech companies (e.g., Google, Apple, Microsoft, Amazon) using a hybrid model that combines:
- **LSTM (Long Short-Term Memory)** networks for time-series forecasting.
- **FinBERT-based Sentiment Analysis** for incorporating market sentiment from financial news.

This notebook demonstrates:
1. Data collection from **Yahoo Finance** and **Alpha Vantage/Polygon API**.
2. Data preprocessing and feature engineering.
3. Building and training an **LSTM model**.
4. Integrating sentiment analysis features.
5. Visualizing predictions and evaluating performance.

---

## Tech Stack

- **Languages:** Python  
- **Libraries:** TensorFlow, Keras, scikit-learn, pandas, NumPy, Matplotlib, Seaborn  
- **NLP Model:** FinBERT (for financial sentiment analysis)  
- **Data Sources:** Yahoo Finance, Polygon API, Alpha Vantage  
- **Platform:** Google Colab / Jupyter Notebook  

---

## Features

- Fetches live historical stock data using APIs.
- Calculates technical indicators (Moving Average, Volatility, RSI, etc.).
- Performs sentiment analysis on financial news headlines.
- Combines numerical and sentiment data for prediction.
- Visualizes actual vs predicted prices for performance comparison.
- Supports multi-step forecasting and uncertainty estimation.

---

## Model Architecture

The model consists of:

- Input Layer: Stock prices + sentiment score features
- LSTM Layers: Captures temporal dependencies
- Dense Layers: For regression output
- Output: Predicted closing price

## Evaluation Metrics

- Mean Absolute Error (MAE)
- Root Mean Square Error (RMSE)
- Directional Accuracy
- Visualization of Predicted vs Actual Prices

## Results

- Achieved strong predictive performance on test data.
- Sentiment integration improved prediction accuracy by ~10%.
- Visualized smooth price trends with minimal lag.
