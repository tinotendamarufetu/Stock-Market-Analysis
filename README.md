Title: Stock Market Analysis & Prediction Using Machine Learning

Description:
This project analyzes stock market data and predicts future stock prices using machine learning models. The dataset is sourced from Yahoo Finance (yfinance), covering five ticker symbols. The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, and predictive modeling.

Key components:

Data Collection: Historical stock data (Open, Close, High, Low, Volume) retrieved using yfinance.
Data Preprocessing: Handling missing values, removing duplicates, and feature engineering (returns, volatility, momentum).
Exploratory Data Analysis (EDA): Visualizations including line plots, correlation heatmaps, box plots, and volume trends.
Machine Learning Models:
Random Forest Regressor: Predicts stock price movement using lag features.
LSTM (Long Short-Term Memory) Neural Network: Captures sequential dependencies in stock prices.
Model Evaluation: Mean Squared Error (MSE) is used to assess performance.
🔗 Technologies Used: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, TensorFlow/Keras, Yahoo Finance API
