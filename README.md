Cryptocurrency (BTC) Price Prediction Using LSTM

📌 Project Overview

This project focuses on predicting Bitcoin (BTC) price movements using Deep Learning techniques, specifically Long Short-Term Memory (LSTM) networks.
The model is trained on historical cryptocurrency market data to capture temporal dependencies and forecast future price trends.

🎯 Objective

Analyze historical Bitcoin price data
Build a time-series forecasting model using LSTM
Predict future BTC closing prices
Evaluate model performance using regression metrics

📊 Dataset

Historical Bitcoin price data (Open, High, Low, Close, Volume)
Data collected using: Public crypto APIs (e.g., CoinMarketCap / Yahoo Finance API), CSV-based historical datasets

🛠️ Tech Stack

Programming Language: Python

Libraries & Frameworks:Pandas, NumPy, Matplotlib, Scikit-learn, TensorFlow, Keras

🔍 Project Workflow

1️⃣ Data Collection

Extracted historical BTC price data Selected relevant features (mainly Closing Price)

2️⃣ Data Preprocessing

Handled missing values
Normalized data using MinMaxScaler
Converted time-series data into supervised learning format
Created sequences (look-back window) for LSTM input

3️⃣ Model Building

Built Sequential LSTM model
Added: LSTM layers, Dropout layers, Dense output layer, Compiled using Adam optimizer and MSE loss

4️⃣ Model Training

Split data into training and testing sets
Trained model for multiple epochs
Monitored loss performance

5️⃣ Model Evaluation

Evaluated using:

RMSE (Root Mean Squared Error)
MAE (Mean Absolute Error)

Compared predicted vs actual BTC prices

📈 Results

The LSTM model successfully captured time-series patterns in BTC price data
Achieved low RMSE and MAE values
Generated visualization comparing predicted and actual prices
