# Stock Price Prediction using Machine Learning

## Overview
This project implements a stock price prediction system using machine learning techniques. It retrieves historical stock data, preprocesses it, applies predictive models, and evaluates their performance. The goal is to forecast future stock prices based on past trends and features.

## Features
- Data collection using `yfinance`
- Data preprocessing and visualization
- Feature engineering using technical indicators
- Machine learning models for prediction
- Model evaluation with RMSE, MAPE, and R² scores
- Future improvements and enhancements

## Dataset
The dataset is retrieved using the `yfinance` library. The default stock symbol used is **Apple Inc. (AAPL)**, and the data spans from **January 1, 2020, to September 1, 2023**.

## Installation

### Prerequisites
Ensure you have the following libraries installed:

```sh
pip install yfinance pandas numpy matplotlib scikit-learn
```

### Clone the Repository
```sh
git clone https://github.com/yourusername/stock-price-prediction.git
cd stock-price-prediction
```

## Usage
Run the Jupyter Notebook or Python script to train and test the model.

- Open **Stock Price Prediction.ipynb** and execute the cells in order.

## Model Implementation
- **Data Preprocessing**: Handling missing values and normalizing data.
- **Feature Engineering**: Moving Averages, RSI, MACD.
- **Models Used**: Linear Regression, Random Forest, LSTM (if implemented).
- **Evaluation Metrics**: RMSE, R² Score, MAPE.

## Results
The model predicts stock prices with reasonable accuracy. Results are visualized using `Matplotlib` to compare actual vs. predicted prices.

## Future Improvements
- Implement Deep Learning models (LSTM/GRU) for better predictions.
- Integrate sentiment analysis from financial news.
- Optimize hyperparameters using `GridSearchCV`.
- Deploy the model as a web application.

## Contributing
Feel free to fork this repository and submit pull requests with improvements.
