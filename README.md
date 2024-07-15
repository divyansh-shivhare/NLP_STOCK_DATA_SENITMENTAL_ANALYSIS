# NLP_STOCK_DATA_SENITMENTAL_ANALYSIS

This project demonstrates various Natural Language Processing (NLP) use cases, including sentiment analysis, the impact of sentiment on stock market prices, time series prediction of stock values, and Named Entity Recognition (NER) on news data.

Prerequisites
To run this project, you need to install the required Python packages. Use the following command to install all necessary packages:
1. pip install finnhub-python yfinance textblob keras tensorflow spacy pandas scikit-learn matplotlib
2. python -m spacy download en_core_web_sm


Project Overview
1. Setup Finnhub Client
We initialize the Finnhub client using an API key to fetch news data.

2. Fetch and Process Company News
We fetch news articles for Apple Inc. for January 2024. Sentiment analysis is performed on the headlines and summaries of the news articles using the TextBlob library.

3. Fetch Historical Stock Prices
We retrieve historical stock prices for Apple Inc. for January 2024 using the yfinance library.

4. Merge Sentiment Data with Stock Prices
We merge the sentiment data with the stock price data to create a combined dataset for further analysis.

5. Predict Stock Prices Based on Sentiment
We use linear regression to predict stock prices based on average sentiment. The actual and predicted prices are plotted for comparison.

6. Time Series Prediction of Stock Values
We preprocess the data for time series prediction using an LSTM model. The actual and predicted prices are plotted for comparison.

7. Named Entity Recognition (NER)
We use spaCy to perform NER on the headlines and summaries of the news articles. The entities extracted from the text are displayed.

Running the Code
Initialize Finnhub Client: Replace 'ADD YOUR API KEY HERE' with your actual Finnhub API key.

Run the Script: Execute the Python script provided to perform sentiment analysis, stock price prediction, and NER.
