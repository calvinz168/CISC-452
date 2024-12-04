# Stock Price Prediction Using Sentiment Analysis

This project combines sentiment analysis of tweets with neural network models to predict stock prices. By analyzing the sentiment of stock-related tweets using VADER and BERT, the models aim to uncover relationships between public sentiment and stock price movements.

---

## Project Overview

1. **Data Preprocessing and Sentiment Analysis**:  
   Tweets are preprocessed and analyzed for sentiment using VADER and BERT, producing cleaned datasets with sentiment scores.  
   File: `preprocessing_sentiment_analysis.ipynb`

2. **Neural Network Models**:  
   Three deep learning models are built to predict stock prices:  
   - CNN + LSTM  
   - LSTM  
   - CNN  
   File: `neural_networks.ipynb`

3. **Data Sources**:  
   - **Raw Data**:  
     - `data/stock_tweets.csv`: Contains stock-related tweets.  
     - `data/stock_yfinance_data.csv`: Contains historical stock price data from Yahoo Finance.  
   - **Processed Data**:  
     - `data/cleaned_data_bert.csv`: Tweets with sentiment scores from BERT.  
     - `data/cleaned_data_vader.csv`: Tweets with sentiment scores from VADER.  

---

## File Structure

```plaintext
├── preprocessing_sentiment_analysis.ipynb  # Sentiment analysis with VADER and BERT
├── neural_networks.ipynb                    # Neural network models for stock price prediction
├── data/                                   # Folder containing CSV files
│   ├── stock_tweets.csv                    # Raw tweets dataset
│   ├── stock_yfinance_data.csv             # Raw stock price data
│   ├── cleaned_data_bert.csv               # Processed data with BERT sentiment scores
│   ├── cleaned_data_vader.csv              # Processed data with VADER sentiment scores
