# 🐦 Twitter Sentiment Analysis (Hate Speech Detection)

This project builds a machine learning model to classify tweets as **hate speech (racist/sexist)** or **not hate speech** using Natural Language Processing (NLP).

---

## 🧹 Text Preprocessing  
- Removed Twitter handles (`@user`)  
- Cleaned special characters, numbers, and punctuation  
- Removed short words (<3 chars)  
- Tokenized and applied **Porter Stemming**  
- Reconstructed normalized clean tweets  

---

## 📊 Exploratory Data Analysis  
- WordClouds for all, positive, and negative tweets  
- Extracted top hashtags using regex  
- Frequency plots for most common positive & negative hashtags  

---

## 🧰 Feature Engineering  
**Bag-of-Words (CountVectorizer)**  
- 1000 max features  
- English stopwords removed  
- Applied `min_df` and `max_df` thresholds  

---

## 🤖 Model  
Trained **Logistic Regression** on BoW features.  
Evaluated using **Accuracy** and **F1 Score**.  
Improved performance using a custom probability threshold (**0.3**).

---

## 📌 Key Insights  
- Hate speech tweets use highly repetitive vocabulary and hashtags  
- Threshold tuning increases recall for hate speech detection  
- Logistic Regression gives a strong baseline for text classification  

---

## 📁 Project Files  
- `Twitter Sentiment Analysis - NLP.ipynb`  
- `Twitter Sentiments.csv`  

