# Exploring Language Identification through Machine Learning

**Authors:**  
- Syed Jawwad Mehdi Rizvi – jawwadmehdi86@gmail.com 

**Degree:** MS Computer Engineering for Robotics and Smart Industry @UNIVR
**Course:** Machine Learning & Artificial Intelligence (2022–2023)  

---

## 📌 Project Overview
This project explores **language identification** — a Natural Language Processing (NLP) task that classifies text into its respective language.  
I evaluated multiple **Machine Learning** models using a dataset containing **22 languages** (1,000 sentences each), applying feature extraction and selection techniques to improve accuracy, efficiency, and scalability.

---

## 🎯 Motivation
With the growth of multilingual content across social media, communication platforms, and online resources, automated **language detection** is critical for:
- Multilingual search & retrieval
- Content filtering
- Language-based recommendations
- Cross-lingual communication

---

## 🔍 Research Theme
- **Domain:** Natural Language Processing (NLP)  
- **Focus:** Language Classification  
- **Goal:** Build a robust and accurate language classification system using machine learning.

---

## 📊 Dataset
- **Source:** (https://www.kaggle.com/datasets/zarajamshaid/language-identification-datasst)
<img width="1269" height="81" alt="image" src="https://github.com/user-attachments/assets/bbf72b71-dec5-40a1-8cbd-b80f13140447" />
- **Languages:** 22  
- **Samples per language:** 1,000 sentences  
- **Preprocessing:** Already cleaned and normalized.

---

## 🛠 Methodology

### 1. **Feature Extraction**
- **CountVectorizer** – Converts text into a numerical representation (bag-of-words / n-grams).

### 2. **Feature Selection**
- **SelectKBest** (Chi-Squared test) – Retains most informative features for classification.

### 3. **Models Implemented**
- **Multinomial Naive Bayes**
- **Support Vector Machine (SVM)**
- **Linear SVC Classifier**
- **Logistic Regression**
- **Random Forest**

### 4. **Evaluation Metrics**
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## 📈 Results

| Model                     | Accuracy (%) |
|---------------------------|--------------|
| Multinomial Naive Bayes   | **95.20**    |
| Linear SVC Classifier     | 94.02        |
| Logistic Regression       | 94.14        |
| Random Forest             | 91.91        |
| Support Vector Machine    | 89.44        |

**Key Insight:**  
Multinomial Naive Bayes outperformed other models in both accuracy and execution time.

---
