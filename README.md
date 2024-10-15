# P3 Stock Price Prediction Using ML Neural Network Web App (Python 2024)

This project is a web application that predicts stock prices using a machine learning (ML) model built with a neural network. The application provides users with the ability to input a stock symbol (e.g., "GOOG" for Google, "BTC" for Bitcoin) and receive a prediction based on historical data. The model is implemented using Python and the TensorFlow/Keras library, and the web interface is built using Streamlit.

## Features
- **Live Stock Data**: Fetches historical stock data from Yahoo Finance using the yfinance library.
- **Neural Network Model**: Uses an LSTM (Long Short-Term Memory) neural network to predict future stock prices based on past trends.
- **Data Visualization**: Plots moving averages for 100, 200, and 250 days to give users a visual representation of the stock's price movements.
- **User Input**: Users can input a stock ticker symbol to view predictions and visualizations for that stock.
- **Streamlit Web App**: An interactive and easy-to-use web interface for stock price prediction and data visualization.

## Files
- `stock_price.ipynb`: Jupyter notebook that contains the ML model training code, along with data preprocessing and model evaluation.
- `web_stock_price_predictor.py`: The main Python script for running the Streamlit web app.

## Project Flow
- **Data Collection**: The app fetches stock data using the yfinance library, which provides historical stock prices.
- **Data Preprocessing**: The data is normalized using MinMaxScaler to prepare it for training with the LSTM model.
- **Model Training**: An LSTM model is trained on historical stock data to predict future prices.
- **Data Visualization**: Moving averages (100, 200, 250 days) are calculated and displayed along with the predicted stock prices.
- **Prediction**: The model predicts the future stock prices based on user input, and these predictions are displayed in both tabular and graphical format.

## Credit
This project was inspired by the "Stock Price Prediction using Python Neural Network" tutorial on the KD Code YouTube channel. Special thanks to KD Code for the comprehensive guide and insights that helped shape this project.
