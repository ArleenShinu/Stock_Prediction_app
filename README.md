Stock Trend Prediction App
This project is a Streamlit web application for stock trend analysis and prediction. It allows users to enter any stock ticker (e.g., 'AAPL', 'GOOG', 'MSFT') and retrieve historical data from 2010 to 2019.

Key Features:
Data Visualization: Automatically plots historical closing prices, 100-day moving averages (100MA), and 200-day moving averages (200MA).

Data Analysis: Displays a statistical summary of the selected stock's historical data.

Deep Learning Prediction: Uses a pre-trained Keras LSTM (Long Short-Term Memory) model to predict future stock prices based on the previous 100 days of data.

Prediction vs. Original: Shows a final graph comparing the model's predicted prices against the actual market prices for the test dataset.

This app is built with Streamlit, TensorFlow/Keras, yfinance, and Scikit-learn.
