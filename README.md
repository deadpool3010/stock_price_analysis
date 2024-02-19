# Stock Price Prediction with Machine Learning and Deep Learning

## Purpose
The primary purpose of this research project is to develop robust predictive models for stock price prediction using machine learning and deep learning algorithms. The goal is to provide investors with valuable tools for making informed and data-driven decisions in the stock market, ultimately aiming to enhance their chances of achieving profitable outcomes while reducing risk and saving time for traders.

## Literature Review
This project builds upon previous research, including the paper titled "A Robust Predictive Model for Stock Price Prediction Using Deep Learning and Natural Language Processing." In this paper, several approaches to stock price and movement prediction on a weekly forecast horizon were presented using eight regression and classification methods based on machine learning and deep learning approaches.

## Workflow
### Data Gathering
Data for this project is obtained using the Tiingo API, which provides access to historical stock price data.

### Data Preprocessing
1. **Min-Max Scaling**: To normalize the data and ensure features with different scales do not dominate the learning process.
2. **Train-Test Splitting**: Dividing the dataset into training and testing subsets to evaluate model performance on unseen data.

### Models
Several models are explored for stock price prediction:
- LSTM (Long Short-Term Memory)
- LSTM + Dense
- LSTM with Regularization
- LSTM-CNN Hybrid
- GRU (Gated Recurrent Unit)
- LSTM + GRU

Each model offers unique advantages and is evaluated based on its performance in predicting stock prices.

## Directory Structure
