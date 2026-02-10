# Credit Card Fraud Detection

A machine learning classification project designed to identify fraudulent credit card transactions using Scikit-Learn and a Random Forest Classifier.

## 🚀 Project Overview

This project tackles the challenge of class imbalance in financial transaction data.
With fraudulent transactions making up only ~0.2% of the dataset, the model is carefully optimized using class-weighting techniques to improve fraud detection while minimizing false positives and preserving customer experience.

## 🛠️ Tech Stack

**Language:** Python 3.13

**Libraries:**

Pandas – Data manipulation and preprocessing

Scikit-Learn – Model training, tuning, and evaluation

Matplotlib / Seaborn – Data visualization

**Model:** Random Forest Classifier

## 📊 Feature Engineering

To enhance model performance, the raw dataset was transformed into informative features:

**Time-Based Features:**
Extracted transaction hour and day of the week from timestamps to capture temporal spending patterns.

**Age Calculation:**
Derived customer age from date of birth (dob).

**Categorical Encoding:**
Applied label encoding to categorical variables such as merchant, transaction category, and job.

**Spatial Features:**
Leveraged latitude and longitude data to analyze merchant–customer proximity and detect anomalous behavior.

## 📁 Data Source

The dataset used in this project was sourced from the **Credit Card Fraud Data** dataset on **Kaggle**, created by **Chetan Mittal**.

Dataset link: https://www.kaggle.com/datasets/chetanmittal033/credit-card-fraud-data

All credit for data collection and original preparation belongs to the dataset’s author.  
