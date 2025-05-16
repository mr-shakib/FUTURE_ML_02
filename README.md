# 📈 Stock Price Forecasting using LSTM

This project implements a time series forecasting model to predict future stock prices using Long Short-Term Memory (LSTM) neural networks. The model is trained on historical stock data retrieved from Yahoo Finance using the `yfinance` API.

## 🔍 Objective

To build a deep learning model that can predict stock prices by capturing temporal patterns in historical stock market data.

## 🚀 Project Highlights

- Collected real-time stock data using `yfinance`
- Preprocessed and scaled time series data using MinMaxScaler
- Created time series sequences using a sliding window approach
- Built and trained an LSTM model using Keras and TensorFlow
- Visualized predicted vs actual prices for model evaluation
- Evaluated model performance using MSE and MAE

## 🛠️ Tools & Technologies Used

- **Python** – Programming Language
- **Pandas & NumPy** – Data manipulation and analysis
- **yfinance** – To fetch historical stock data
- **Scikit-learn** – For evaluation metrics and data scaling
- **Keras & TensorFlow** – Deep learning framework for building the LSTM model
- **Matplotlib & Seaborn** – Data visualization

## 📊 Results & Visualizations

- Predicted vs. Actual Stock Prices  
- Training vs. Validation Loss Curve

![Prediction vs Actual](https://i.imgur.com/MB2EqvD.png)


## 🧠 Skills Demonstrated

- Time Series Forecasting  
- LSTM Neural Networks  
- Model Evaluation and Tuning  
- Data Visualization for Financial Insights  
- Deep Learning for Regression Problems

## 📁 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/stock-price-forecasting-lstm.git
   cd stock-price-forecasting-lstm
