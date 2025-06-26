# Spam Mail Prediction using Machine Learning

This project focuses on predicting whether a message is **spam** or **not spam (ham)** using a Machine Learning model. The core of the project is implemented in Python using libraries such as **NumPy**, **Pandas**, and **Scikit-learn**. It includes complete steps from data preprocessing to model evaluation.

---

## Project Overview

Spam detection is a common problem in the domain of Natural Language Processing (NLP). This project solves it using traditional ML techniques and basic text vectorization methods.

---

## Files in this Repository

- `Spam_Mail_Prediction.ipynb` – Jupyter Notebook containing the full ML pipeline for spam detection
- `README.md` – Project documentation
- `requirements.txt` – Python dependencies list

---

## Dataset

The dataset used contains SMS messages labeled as **spam** or **ham**. It is typically structured as:

| Label | Message |
|-------|---------|
| spam  | Free entry in 2 a wkly comp to win FA Cup final tkts 21st May 2005... |
| ham   | Nah I don't think he goes to usf, he lives around here though |

The dataset is loaded into a pandas DataFrame, cleaned, and preprocessed for training.

---

## ML Pipeline Steps

1. **Importing Libraries**
   - NumPy, Pandas, Sklearn, etc.

2. **Data Preprocessing**
   - Removing null values
   - Label encoding: `spam → 0`, `ham → 1`
   - Splitting data into training and test sets

3. **Feature Extraction**
   - Using `TfidfVectorizer` to convert messages into numerical features

4. **Model Training**
   - Trained a **Logistic Regression** model

5. **Evaluation**
   - Calculated accuracy on training and test datasets
   - Output predictions for new messages

---

## Results

- **Accuracy on Training Data**: 96.77%
- **Accuracy on Test Data**: 96.68%

The model performs well in detecting spam messages with high precision and generalization capability.

---
