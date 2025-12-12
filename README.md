🐦 Twitter Sentiment Analysis (Hate Speech Detection)

This project classifies tweets as hate speech (racist/sexist) or not hate speech using NLP and machine learning. It includes text preprocessing, exploratory analysis, feature engineering, and model training.

🧹 Text Preprocessing

Removed Twitter handles, special characters, numbers, and punctuation

Removed short words and applied tokenization

Used Porter Stemming to normalize words

Created a cleaned version of each tweet for modeling

📊 Exploratory Analysis

WordClouds for all tweets, hate speech tweets, and normal tweets

Extracted & visualized top hashtags for both classes

Frequency analysis using NLTK

🧰 Feature Engineering

CountVectorizer (BoW)

1000 max features

English stopword removal

Applied min_df and max_df for noise cleanup

🤖 Model

Logistic Regression trained on Bag-of-Words features.
Evaluated using F1 Score and Accuracy.

Threshold tuning (0.3) improved F1 score for detecting hate speech.

📌 Key Insights

Hate speech tweets show strong recurring vocabulary and hashtags

Threshold tuning boosts minority class prediction

Logistic Regression serves as a strong baseline model

📁 Files

Twitter Sentiment Analysis - NLP.ipynb

Twitter Sentiments.csv
