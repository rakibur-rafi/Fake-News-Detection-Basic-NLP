# Fake News Detection using Machine Learning

A machine learning project that detects whether a news article is **REAL (1)** or **FAKE (0)** using NLP techniques and multiple classification models.

---

##  Dataset

Fake News : https://www.kaggle.com/datasets/hassanamin/textdb3

### Label Encoding:
- REAL → 1  
- FAKE → 0  

---

## Libraries Used

- Pandas  
- NLTK  
- Scikit-learn  
- XGBoost  
- Regular Expressions (re)

---

## NLP Preprocessing Steps

- Lowercasing text  
- Removing special characters using `re`  
- Removing stopwords  
- Lemmatization  
- TF-IDF Vectorization  

---

## Train-Test Split

- 80% Training Data  
- 20% Testing Data  

---

## Machine Learning Models Used

- Decision Tree (DT)  
- Random Forest (RF)  
- Gradient Boosting (GB)  
- XGBoost (XGB)  
- Logistic Regression (LR)  

---

## Results

| Model | Performance |
|------|-------------|
| Logistic Regression | Highest Accuracy |
| XGBoost | Second Best |
| Random Forest | Good |
| Gradient Boosting | Good |
| Decision Tree | Lowest |

---

## Workflow

1. Load dataset using Pandas  
2. Clean and preprocess text data  
3. Apply stopwords removal and lemmatization
4. Split dataset (80/20)  
5. Vectorize using TF-IDF  
6. Train multiple ML models  
7. Evaluate accuracy  

---
