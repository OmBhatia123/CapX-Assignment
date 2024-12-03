## Stock Prediction Model using Twitter Sentiment Analysis

This project aims to predict stock market movements based on social media sentiment analysis. Tweets are scraped using the Tweepy API, cleaned, and analyzed for sentiment. The sentiment data is used to train a machine learning model to predict stock movement.

## Features
- Scraping tweets related to stock market sentiment using Tweepy.
- Preprocessing text data for sentiment analysis.
- Sentiment analysis using TextBlob.
- Predicting stock market trends using a Random Forest model.

## Requirements
The project is built with the following Python libraries:
- `tweepy`
- `pandas`
- `nltk`
- `textblob`
- `scikit-learn`
- `imbalanced-learn`
- `matplotlib`

To install the dependencies, use:
```bash
pip install -r requirements.txt
