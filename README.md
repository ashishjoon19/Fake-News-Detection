# 📰 Fake News Detection Using Machine Learning

This project aims to classify news articles as *Real* or *Fake* using Natural Language Processing (NLP) and Machine Learning. It uses a labeled dataset of news articles and implements models such as Logistic Regression and Passive-Aggressive Classifier to detect misinformation.

---

## 🔍 Problem Statement

Fake news has become a significant concern in the digital age. This project tackles the challenge of identifying and classifying misleading or false news articles using machine learning algorithms and text analysis techniques.

---

## 📁 Dataset

- **Source:** [Kaggle - Fake and Real News Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)
- Contains labeled news articles with attributes like `title`, `text`, and `label` (Fake or Real).

---

## 🛠️ Tech Stack & Tools

- **Language:** Python
- **Libraries:** 
  - `pandas`, `numpy` for data handling
  - `sklearn` for machine learning
  - `nltk` for NLP (stopwords, stemming)
  - `matplotlib`, `seaborn` for visualization
- **Models Used:** 
  - Logistic Regression
  - Passive-Aggressive Classifier
- **Optional Deployment:** Flask for web-based interface

---

## ⚙️ How It Works

1. **Data Preprocessing:**
   - Remove punctuation and stopwords
   - Convert text to lowercase
   - Apply stemming
   - Transform text into numerical form using TF-IDF

2. **Model Training:**
   - Train-test split (80-20)
   - Fit models on training data
   - Evaluate using accuracy and confusion matrix

3. **Prediction:**
   - Accepts user input news text
   - Outputs prediction: `Not True` or `True`

---

## 🚀 Running the Project

### Clone the Repository
```bash
git clone https://github.com/ashishjoon19/Fake-News-Detection.git
cd Fake-News-Detection
