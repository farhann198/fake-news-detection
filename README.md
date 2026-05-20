# 📰 Fake News Detection using Machine Learning

A Machine Learning project that detects whether a news article is **Real** or **Fake** using Natural Language Processing (NLP) techniques and multiple classification algorithms.

## 🚀 Project Overview

This project uses:
- Text preprocessing & cleaning
- TF-IDF Vectorization
- Machine Learning classification models

to classify news articles as **Fake News** or **Real News**.

---

## 📂 Dataset

Dataset used:
- Fake and Real News Dataset

Contains:
- Fake news articles
- Real news articles

Dataset Source:  
https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLP
- TF-IDF Vectorizer
- Jupyter Notebook

---

## ⚙️ Machine Learning Models Used

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier

---

## 🔍 Text Preprocessing

The following preprocessing techniques were applied:
- Lowercasing
- Removing punctuation
- Removing URLs
- Removing special characters
- Removing numbers
- Removing extra spaces

---

## 📊 Feature Extraction

TF-IDF Vectorization with N-Grams was used for converting text into numerical features.

```python
TfidfVectorizer(ngram_range=(1,2))
```

---

## 📈 Model Performance

The models were trained and evaluated on the processed dataset to compare their accuracy in fake news classification.

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/farhann198/fake-news-detection.git
```

2. Install dependencies

```bash
pip install pandas numpy scikit-learn notebook
```

3. Run Jupyter Notebook

```bash
jupyter notebook
```

4. Open:

```bash
fake-news-detection.ipynb
```

---


## 👨‍💻 Author

**Farhan Ansari**

- LinkedIn: https://www.linkedin.com/in/farhan0105g/ 

---

## ⭐ Future Improvements

- Deep Learning Models
- LSTM / RNN implementation
- Transformer-based models
- Real-time fake news prediction web app
- Streamlit deployment
