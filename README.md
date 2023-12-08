# Stock Price Prediction using LSTM

This repository houses a learning-hobby project focused on predicting stock prices utilizing Long Short-Term Memory (LSTM) networks. The project was developed while exploring Python for data analysis and machine learning within Jupyter Notebooks.

## Project Overview

The project encompasses the following steps:

1. **Data Collection:** Fetching historical stock data using Yahoo Finance API (`yfinance`) for a specified period.
2. **Data Visualization:** Visualizing the stock data with candlestick charts to illustrate price trends and fluctuations.
3. **Correlation Analysis:** Examining the correlation between stock features and their impact on the closing price.
4. **LSTM Model Building:** Implementing an LSTM neural network architecture for predicting stock prices.

## Project Details

### Data Collection and Visualization

- Using Yahoo Finance API, historical data for the Apple stock (`AAPL`) was fetched for analysis.
- A candlestick chart was plotted to visualize the stock's open, high, low, and close prices over time.

### LSTM Model Training

- Features such as open, high, low, and volume were selected for training the LSTM model.
- Data was split into training and test sets using `train_test_split`.
- A sequential LSTM neural network was constructed using Keras.
- The model was compiled and trained over multiple epochs to minimize mean squared error.

### Testing the Trained Model

- The trained LSTM model was tested by providing input values based on historical features.
- Predictions were made to estimate the future closing price of the stock.

## Accessing the Project

1. Clone or download this repository to your local machine.
   ```
   https://github.com/MTank76/Stock-Price-Prediction.git
   ```
3. Open the Jupyter Notebook (`Stock Price Prediction with LSTM.ipynb`) in Jupyter Notebook or JupyterLab to explore the project and its predictions.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, feel free to open issues for suggestions or submit pull requests with proposed enhancements.
