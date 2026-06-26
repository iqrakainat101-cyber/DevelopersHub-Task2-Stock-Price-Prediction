# Stock Price Prediction Using Machine Learning

## Project Overview

This project was developed as part of the AI/ML Engineering Internship at DevelopersHub Corporation.

The objective is to predict Apple's stock closing price using historical stock market data and a Linear Regression model.


## Objective

To build a machine learning model that predicts stock closing prices using:

- Open Price
- High Price
- Low Price
- Volume


## Dataset

Source: Yahoo Finance

Stock Selected:

Apple Inc. (AAPL)

Period:

2020 – 2025

Data retrieved using the yfinance Python library.


## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- yFinance


## Machine Learning Model

Model Used:

Linear Regression

Target Variable:

Close Price

Features:

- Open Price
- High Price
- Low Price
- Volume


## Project Workflow

1. Download historical stock data
2. Explore and analyze dataset
3. Select features and target
4. Split data into training and testing sets
5. Train Linear Regression model
6. Generate predictions
7. Evaluate model performance
8. Visualize actual vs predicted prices


## Evaluation Metrics

| Metric | Value |
|----------|----------|
| MAE | 0.7419 |
| RMSE | 0.9982 |
| R² Score | 0.9994 |


## Results

The model achieved excellent performance:

- Very low prediction error
- Strong agreement between actual and predicted prices
- R² score close to 1.0

The predicted stock prices closely follow actual market values.


## Visualizations

The repository includes:

- Dataset Preview
- Summary Statistics
- Evaluation Metrics
- Actual vs Predicted Prices
- Final Conclusion


## Conclusion

A Linear Regression model was successfully trained to predict Apple stock closing prices.

The model achieved high accuracy with an R² score of approximately 99.94%, demonstrating that historical market features can effectively predict short-term stock price movements.
AI/ML Engineering Internship

Task 2: Predict Future Stock Prices (Short-Term)
