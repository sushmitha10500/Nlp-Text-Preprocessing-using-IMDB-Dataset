# Nlp-Text-Preprocessing

## 🎬 NLP Text Processing using IMDB Dataset

This project focuses on **Natural Language Processing (NLP)** techniques applied to the **IMDB movie reviews dataset**. It includes data preprocessing, vectorization, sentiment classification, and model evaluation using traditional machine learning models.

---

## 📌 Project Objectives

- Clean and preprocess raw IMDB review text.
- Convert text to numerical representations (TF-IDF, Count Vectorizer).
- Train sentiment classification models using scikit-learn.
- Evaluate model performance with accuracy, confusion matrix, and other metrics.
- Explore the use of pipelines and parameter tuning.

---

## 🛠️ Tech Stack

| Task              | Tools & Libraries                     |
|-------------------|----------------------------------------|
| Text Processing   | `nltk`, `re`, `string`, `sklearn`     |
| Vectorization     | `CountVectorizer`, `TfidfVectorizer`  |
| Modeling          | `LogisticRegression`, `NaiveBayes`    |
| Evaluation        | `classification_report`, `confusion_matrix` |
| Data Handling     | `pandas`, `numpy`                     |
| Visualization     | `matplotlib`, `seaborn`               |
| Notebook          | `Jupyter Notebook`                    |

---

## 📂 Project Structure

├── data/
│ └── imdb.csv
├── notebooks/
│ └── NLP_IMDB_Processing.ipynb
├── models/
│ └── saved_models.pkl
├── requirements.txt
├── README.md
└── .gitignore


---

## 🧪 Features Implemented

- Text preprocessing (lowercasing, stopword removal, stemming)
- Vectorization: Bag of Words and TF-IDF
- Model training: Naive Bayes, Logistic Regression
- Evaluation: Accuracy, precision, recall, F1-score
- ML Pipeline integration using `Pipeline()` from scikit-learn

---

- **Best Accuracy:** ~90% (using **TF-IDF + Logistic Regression**)
- **Key Insight:** Proper text cleaning and feature extraction greatly enhance model performance.

---

