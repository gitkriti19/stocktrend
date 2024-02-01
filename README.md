# Stock Price Prediction using LSTM

## Overview

This project utilizes Long Short-Term Memory (LSTM) models to predict stock prices based on data sourced from Yahoo Finance. The LSTM architecture proves effective in capturing temporal dependencies within stock price data, enabling accurate forecasting.

## Key Components

1. **Data Source**
   - Yahoo Finance: The project relies on historical stock price data obtained from Yahoo Finance.

2. **LSTM Model Implementation**
   - Implementation of LSTM neural network for time series prediction.
   - Data preprocessing and feature engineering to enhance model performance.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/stock-price-prediction.git
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Execute the main prediction script:

   ```bash
   python predict_stock_prices.py
   ```

## Data Processing

- Data sourced from Yahoo Finance is preprocessed to handle missing values and ensure compatibility with the LSTM model.

## Results

- The model's predictive performance is evaluated using standard metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).



