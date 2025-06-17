# 📰 Fake News Detector

This project uses Natural Language Processing (NLP) and Machine Learning to classify news articles as **Fake** or **Real**. It uses TF-IDF vectorization and Logistic Regression to analyze article content and predict its authenticity.

---

## 📊 Overview

- 🧠 **Model**: Logistic Regression
- 🔠 **Vectorizer**: TF-IDF
- 📈 **Accuracy**: ~98.63%
- 🧪 **Tested** on real and fake news samples

---

## 📁 Dataset

Dataset used:  
🔗 [Fake and Real News Dataset (Kaggle)](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)

Files used:
- `Fake.csv` → labeled as 1 (Fake News)
- `True.csv` → labeled as 0 (Real News)

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- TF-IDF Vectorizer
- Matplotlib, Seaborn
- Google Colab / Jupyter

---

## 🔍 Sample Results

✅ Accuracy: 98.63%

Classification Report:
precision recall f1-score support
0 0.98 0.99 0.99 4284
1 0.99 0.98 0.99 4693

Confusion Matrix:
[[4234 50]
[ 60 4633]]
