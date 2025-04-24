# 📧 Spam Email Classifier

This is a Machine Learning project that classifies emails (or text messages) as **SPAM** or **HAM (not spam)** using natural language processing (NLP) techniques.

---

## 🔍 Project Overview

Spam detection is a common real-world application of NLP. In this project, we:
- Collected and preprocessed a dataset of SMS messages.
- Used NLP techniques to clean and vectorize the text.
- Built and evaluated classification models.
- Improved accuracy using TF-IDF and advanced models like Random Forest and Logistic Regression.

---

## 🛠️ Tools & Technologies

- **Python**
- **pandas**, **NumPy**
- **NLTK** (for text preprocessing)
- **scikit-learn** (for ML models and metrics)
- **TF-IDF Vectorizer**
- **Matplotlib** / **Seaborn** (for visualization, optional)

---

## 📂 Dataset

We used the **SMS Spam Collection** dataset:
- Downloaded from: [Kaggle Dataset Link](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

---

## 🔄 Workflow

1. **Load Dataset**
2. **Text Cleaning** (punctuation removal, lowercasing, stemming)
3. **Vectorization** using TF-IDF
4. **Model Training**
   - Logistic Regression
   - Random Forest
5. **Evaluation** using Accuracy, Precision, Recall, F1 Score
6. **Save & Predict New Messages**

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/spam-email-classifier.git
   cd spam-email-classifier
