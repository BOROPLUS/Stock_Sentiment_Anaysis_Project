# Stock_Sentiment_Anaysis_Project

##Overview
Stock Sentiment Analysis is a machine learning project that predicts stock price movements based on financial news sentiment. The project integrates web scraping, natural language processing (NLP), ensemble models like XG Boost and deep learning models like LSTM, GRU to assess how market sentiment influences stock prices.

##Features
* News Scraping → Fetches financial news articles from Google News RSS.
* Stock Data Extraction → Retrieves historical stock prices from Yahoo Finance.
* Text Preprocessing → Cleans and tokenizes financial news using NLP techniques.
* Sentiment Analysis → Uses VADER and BERTopic for sentiment classification.
* Feature Engineering → Generates word embeddings using Word2Vec.
* Supervised Learning Models → Predicts stock movement using LSTM, GRU, BiLSTM, and XGBoost.
* Performance Evaluation → Compares models to determine the most effective approach.

##Model Comparisons
Model	                   Pros	                                      Cons
LSTM	         Captures long-term dependencies	            Slower, needs more data
GRU	        Faster than LSTM, similar performance	        Can lose long-term patterns
XGBoost     Fast and works well with tabular data	      Doesn't handle sequential data well


Run the notebook to:

Scrape financial news
Extract stock price data
Calculate sentiment scores
Train models (LSTM, GRU, BiLSTM, XGBoost)
Evaluate performance
