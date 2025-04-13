# SpamShield

# 📬 Spam Detector - Email Classification with Machine Learning

This project is a machine learning-based solution to detect **spam emails** and distinguish them from legitimate (ham) ones. It demonstrates how natural language processing (NLP) and classification algorithms can be applied to real-world text data for spam detection.

---

## 🧠 Project Overview

The main goal is to classify messages as **"spam"** or **"ham"** using supervised learning techniques. The pipeline includes:
- Data preprocessing and text cleaning
- Feature extraction using Bag of Words / TF-IDF
- Training classification models
- Evaluating model performance
- Making predictions on unseen data

---

## 📂 Dataset

The dataset contains labeled SMS/email messages in the following format:

| Label | Message |
|-------|---------|
| ham   | "Hey, are we still meeting today?" |
| spam  | "WINNER! Click here to claim your $1000 prize." |

> The dataset must be in the same directory as the notebook (e.g. `spam.csv`).

---

## 🔧 Features & Workflow

1. **Data Loading**
   - Importing dataset and exploring message distribution.

2. **Text Preprocessing**
   - Lowercasing, punctuation removal, stopword removal, tokenization.

3. **Feature Engineering**
   - Count Vectorizer (Bag of Words)
   - TF-IDF Vectorizer

4. **Model Training**
   - Algorithms used:
     - Naive Bayes (MultinomialNB)
     - Support Vector Machines (SVM)
     - Logistic Regression

5. **Model Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Precision / Recall / F1-score

6. **Prediction Interface**
   - Option to input custom messages for prediction (Jupyter cell)

---

## 🧪 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/spam-detector.git
   cd spam-detector
