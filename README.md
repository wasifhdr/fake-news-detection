# 🕵️ Fake News Detection System

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)

## 📌 Project Overview
This project is a Machine Learning model designed to detect and classify news articles as either **Real** or **Fake**. With the rapid spread of misinformation on social media, automated systems like this help in verifying the authenticity of news sources effectively. I initially tested the performance of 7 models (PAC, Linear SVC, Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, Voting Classifier with Logistic Regression, Linear SVC, PAC) on the dataset. PAC performed the best so I used that to test on an external dataset. This gave me an accuracy of 96.97%.

## ⚙️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, NLTK, Matplotlib
* **Model:** Passive Aggressive Classifier

## 📂 Dataset
The model was trained on the WELFake dataset.
* **Source:** https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification
* **Size:** 70,000 fake and true news articles
* **Preprocessing:** Removed stopwords, performed stemming/lemmatization, and vectorized text using TF-IDF.
