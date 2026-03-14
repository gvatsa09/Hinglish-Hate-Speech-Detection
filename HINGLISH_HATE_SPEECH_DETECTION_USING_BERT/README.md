# 🛡️ Hinglish Hate Speech Detection using Naive Bayes

A lightweight and effective machine learning model for detecting hate speech in **code-mixed Hindi-English (Hinglish)** text using the **Naive Bayes classifier**. Designed for real-time moderation of toxic content on social media and messaging platforms.

## 📋 Features
- Supports Hinglish (code-mixed Hindi-English) inputs
- Uses TF-IDF vectorization + Multinomial Naive Bayes
- Custom preprocessing pipeline: tokenization, normalization, stopword removal
- Evaluated with Accuracy, Precision, Recall, and F1-score

## 🧪 Dataset
- Format: CSV with `text` and `label` columns
- Labels: `0` - Non-Hate, `1` - Hate Speech
- Source: [Insert dataset name or link]

## ⚙️ Pipeline
1. Text normalization and lowercasing
2. Removal of noise, punctuation
3. Hindi and English stopword removal
4. Tokenization
5. TF-IDF Vectorization

## 🧠 Model
- Classifier: Multinomial Naive Bayes
- Vectorizer: TfidfVectorizer
- Libraries: scikit-learn, nltk, pandas
