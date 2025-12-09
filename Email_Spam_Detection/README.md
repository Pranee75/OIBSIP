# Spam Detection Project

Classify SMS messages as **Spam** or **Ham** (not spam) using **Machine Learning (Naive Bayes)** and NLP techniques.

---

## Project Overview / Description
This project implements a spam detection system that automatically identifies unwanted messages.  
It demonstrates a full machine learning pipeline including **data preprocessing**, **feature extraction**, **model training**, **evaluation**, and **prediction of new messages**.

---

## Project Objective / Aim
The main goal is to build an accurate and efficient model to detect spam messages.  
It helps in filtering unwanted SMS and demonstrates practical applications of **Natural Language Processing** and **Machine Learning**.

---

## Dataset / Data Description
- Dataset: `spam.csv` (SMS Spam Collection)  
- Columns:
  - `label` → spam or ham  
  - `message` → SMS text  

**Example messages:**
"Free entry in 2 a wkly comp to win FA Cup final tickets" → spam
"Hey, are we meeting today?" → ham


---

## Preprocessing / Data Cleaning
Steps applied to prepare text data:
1. Convert text to lowercase  
2. Remove punctuation & non-alphabetic characters  
3. Tokenize words  
4. Remove stopwords  
5. Lemmatize words to their base form (e.g., "running" → "run")  

Cleaned text is stored in `clean_text_new` for training.

---

## Feature Extraction / Engineering
- Use **TF-IDF Vectorization** to convert text into numerical features  
- Include **unigrams (single words) and bigrams (word pairs)**  
- Limit features to **top 5000** to reduce noise and improve efficiency

---

## Model / Algorithm Used
- **Classifier:** Multinomial Naive Bayes  
- Handles **text classification** well and is efficient with high-dimensional sparse data  
- **Train/Test Split:** 80% train, 20% test

---

## Evaluation / Results
- **Accuracy:** ~98%  
- Confusion matrix and classification report included  

**Insights:**  
- Model performs very well for clearly defined spam messages  
- Some short or ambiguous messages may be misclassified

---

## Prediction / Usage
Predict new messages using the function:

```python
predict_message_improved("Congratulations! You won a $5000 gift card. Reply NOW!")

