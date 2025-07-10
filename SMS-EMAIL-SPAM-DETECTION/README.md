# 📧 SMS/Email Spam Detection using NLP and Naive Bayes

A machine learning project that classifies SMS messages as **spam** or **ham (not spam)** using **Natural Language Processing (NLP)** and a **Naive Bayes classifier**. This project demonstrates an end-to-end pipeline including data cleaning, feature engineering with TF-IDF, model training, evaluation, and prediction.

---

## 🚀 Project Overview

- **Goal**: Build a spam classifier that detects unwanted messages.
- **Dataset**: [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset) (UCI)
- **Model**: Multinomial Naive Bayes
- **Tech Stack**: Python, Pandas, NLTK, Scikit-learn, TF-IDF, Matplotlib, Seaborn

---

## 📂 Dataset Details

- **Total Records**: 5572 messages
- **Columns**:
  - `v1`: Label (`ham` or `spam`)
  - `v2`: The message text
- Only two columns are used and renamed to `label` and `message`.

---

## 🧠 Concepts Covered

- Text Cleaning (lowercase, punctuation, numbers removal)
- Tokenization using NLTK
- Stopwords removal
- Stemming using PorterStemmer
- TF-IDF Vectorization
- Model Training with Multinomial Naive Bayes
- Evaluation using Accuracy, Precision, Recall, F1-Score
- Confusion Matrix Visualization
- Predicting on custom messages

---

## 🛠️ Tools & Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `nltk`
- `sklearn`

---

## 📊 Model Performance

- **Accuracy**: ~97%
- **Evaluation Metrics**: Precision, Recall, F1-score for both spam and ham
- **Confusion Matrix**:
  Visualized using `seaborn.heatmap`

---

## 🔍 Example Prediction

```python
Message: "Congratulations! You've won a free iPhone. Click here to claim."
Prediction: Spam

Message: "Hey, are we still on for dinner tonight?"
Prediction: Ham
