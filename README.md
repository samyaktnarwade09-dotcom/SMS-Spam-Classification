#  SMS Spam Classification using Naive Bayes

An end-to-end **text classification** project that detects whether an SMS message is **Spam** or **Ham** (legitimate) using Multinomial Naive Bayes.

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0+-orange)
![NLP](https://img.shields.io/badge/NLP-Text%20Classification-green)

---

##  Project Overview

Mobile users receive dozens of SMS messages daily, many of which are spam (promotional or fraudulent).  
This project builds a machine learning model that automatically classifies SMS messages as **Spam** or **Ham**.

**Algorithm used:** Multinomial Naive Bayes  
**Vectorization technique:** Bag of Words (CountVectorizer)

---

##  Pipeline

1. Data Loading & Cleaning
2. Exploratory Data Analysis (Ham vs Spam distribution + message length analysis)
3. Label Encoding
4. Train-Test Split (stratified)
5. Text Vectorization using `CountVectorizer`
6. Model Training – MultinomialNB
7. Evaluation (Accuracy, Classification Report, Confusion Matrix)
8. Testing on custom real-world messages

---

##  Key Insights

- Spam messages are generally **longer** than legitimate messages
- Naive Bayes works exceptionally well on high-dimensional sparse text data
- The model correctly identifies promotional and urgent-looking spam messages with high confidence

---

##  How to Run

1. Clone the repository
2. Place the dataset `sms_spam.csv` in the same folder
3. Open `SMS_Spam_Classification_Solution.ipynb` in Jupyter or Google Colab
4. Run all cells

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
