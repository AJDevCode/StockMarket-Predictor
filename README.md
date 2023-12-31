# Stock Price Prediction with Python


## Description
The Stock Price Prediction with Python is a program that uses machine learning, specifically TensorFlow and scikit-learn, to predict stock prices. It retrieves historical stock data from Yahoo Finance using pandas, trains a neural network on this data, and then makes predictions for the next day's stock value. It also outputs the graphs of the real and prediction model generated. 

![Stock Prediction Picture](https://github.com/AJDevCode/StockMarket-Predictor/assets/67168409/4f6895d9-8573-45c2-9cb2-e23ddc3a19c1)



## Table of Contents
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies Used](#technologies-used)


## Prerequisites
Before you begin, ensure you have the following requirements:

- **Python**: Make sure you have Python installed on your system. You can download it from [python.org](https://www.python.org/).

- **TensorFlow, scikit-learn, pandas**: Install these libraries using the following command:
  ```bash
  pip install tensorflow scikit-learn pandas
  ```
## Installation
Follow these steps to set up the Stock Price Prediction program:

### Step 1: Clone the Repository
``` bash
git clone https://github.com/AJDevCode/stock-price-prediction.git
```
### Step 2: Install Dependencies
Install all the libraries needed

### Step 3: Selecting Yahoo Finance Stock Data
Either use the same company value selected or change the company stock and date of time to what is required. 

## Usage
To run the Stock Price Prediction program, execute the following command:
``` bash
python predict_stock_prices.py
```
Or run this in Pycharm/Visual Studio Code alternative

The program will retrieve historical stock data, train a neural network, and output a prediction for the next day's stock value.

## Features
The Stock Price Prediction program offers the following key features:

- Retrieves historical stock data from Yahoo Finance.

- Uses TensorFlow and scikit-learn to train a neural network.

- Predicts the stock value for the next day based on historical data.

Example Provided:

![Prediction of price](https://github.com/AJDevCode/StockMarket-Predictor/assets/67168409/a5194d3c-2c54-467d-9eed-ae3b002d9daa)

## Technologies Used

- Python
- TensorFlow
- Scikit-learn
- Yahoo Finance API
- Pandas
