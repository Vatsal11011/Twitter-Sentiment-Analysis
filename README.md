# Twitter Sentiment Analysis

This project performs sentiment analysis on Twitter data to detect hate speech and violent content using Natural Language Processing (NLP) and Machine Learning techniques. The task is formulated as a **binary classification problem**, categorizing tweets into **Positive** and **Negative** classes.

---

## 📌 Problem Statement

With the rapid growth of social media platforms like Twitter, identifying harmful content such as hate speech and violence has become crucial. This project aims to build an automated system that analyzes tweet text and classifies sentiment to support content moderation efforts.

---

## 🧠 Approach

The project follows an end-to-end NLP workflow:
1. Text preprocessing and cleaning  
2. Feature extraction from tweets  
3. Training and evaluating machine learning models  
4. Exploratory Data Analysis (EDA) for insights  

---

## ⚙️ Tech Stack

- **Programming Language:** Python  
- **Libraries & Tools:**  
  - Pandas, NumPy  
  - NLTK  
  - Scikit-learn  
  - Matplotlib, Seaborn  

---

## 🔍 Data Preprocessing

The following preprocessing steps were applied to Twitter text:
- Lowercasing  
- Removing punctuation and special characters  
- Stopword removal  
- Tokenization  
- Vectorization using Bag of Words / TF-IDF  

---

## 🤖 Machine Learning Models Used

The following classifiers were implemented and compared:
- Logistic Regression  
- Naïve Bayes  
- Support Vector Machine (SVM)  
- Random Forest  

The sentiment labels used were:
- **Positive**
- **Negative**

---

## 📊 Exploratory Data Analysis (EDA)

EDA was performed to:
- Analyze sentiment distribution  
- Identify frequent words and patterns  
- Visualize trends using plots and charts  

---

## 📈 Evaluation

Model performance was evaluated using standard metrics:
- Accuracy  
- Precision  
- Recall  
- F1-score  

This comparison helped determine the most effective model for sentiment classification.
