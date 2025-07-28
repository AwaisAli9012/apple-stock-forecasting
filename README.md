# apple-stock-forecasting
# Stock Price Prediction using Machine Learning

This project predicts Apple (AAPL) stock closing prices using Linear Regression based on Open, High, Low prices and Volume data.

## 📊 Project Overview

A machine learning model that:
- Downloads real-time Apple stock data using yfinance
- Uses Open, High, Low, and Volume as features to predict Closing prices
- Implements Linear Regression for price prediction
- Evaluates model performance with MSE and R² metrics
- Visualizes actual vs predicted prices

## 🚀 Features

- **Real-time Data**: Fetches latest stock data from Yahoo Finance
- **Machine Learning**: Uses scikit-learn Linear Regression
- **Data Visualization**: Plots actual vs predicted closing prices
- **Model Evaluation**: Calculates MSE and R² score for performance assessment
- **Export Data**: Saves downloaded stock data to CSV

## 📦 Requirements

```bash
pip install yfinance pandas matplotlib seaborn scikit-learn
