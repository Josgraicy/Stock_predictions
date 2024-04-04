# S&P 500 Stock Predictor

## Overview
This project is dedicated to predicting the movement of the S&P 500 stock market index. Utilizing a machine learning approach, I have developed a model based on the RandomForestClassifier algorithm from the scikit-learn library. The model has been trained and tested on historical S&P 500 data, and through iterative enhancements, I've achieved a prediction accuracy of nearly 60%. The historic data for the sp500 was pulled from the yfinance library in python.

## Features
- **Data Processing:** Scripts to clean and prepare historical S&P 500 data for training and testing.
- **Model Training:** A RandomForestClassifier model is trained on a set of features derived from historical stock market data.
- **Accuracy Improvement:** Techniques employed to tune the model and improve prediction accuracy, including hyperparameter optimization and feature engineering.
- **Prediction:** A system to make daily predictions on the direction of the S&P 500 index movement.
- **Evaluation:** Metrics and methods to evaluate the model's performance.

## Requirements
- Python 3.8+
- scikit-learn
- pandas
- matplotlib (for visualization)

## Model Improvement
The initial version of the model predicted the movement of the S&P 500 index with about 40% accuracy, which is no better than random chance. Through a series of improvements, including hyperparameter tuning, and incorporating more nuanced market indicators, I were able to elevate the model's accuracy to nearly 60%. 
