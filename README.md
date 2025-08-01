# 🏠 Airbnb Superhost Classification

A machine learning project that predicts whether a host on Airbnb is a **Superhost**, using features from real NYC listing data.

## 📌 Overview
This project was developed as part of Break Through Tech AI's program to explore classification problems using real-world tabular data. The goal was to predict Airbnb Superhost status based on various listing attributes such as location, room type, review scores, and availability.

## 🎯 Objectives
- Understand and apply classification algorithms to real-world data
- Perform data cleaning and feature selection
- Compare model performance using appropriate metrics
- Gain experience with both scikit-learn pipelines and custom model implementations

## 📊 Dataset
- **Source:** Inside Airbnb open dataset (NYC)
- **Target variable:** `host_is_superhost` (Yes/No)
- **Features used:** review scores, location, price, number of listings, room type, etc.

## 🧪 Methodology
- Data cleaning and preprocessing (handling missing values, encoding categoricals)
- EDA to understand class balance and feature distributions
- Trained and evaluated the following models:
  - Decision Tree Classifier
  - K-Nearest Neighbors (KNN)
  - Logistic Regression (including a manual implementation from scratch)
- Evaluation metrics: accuracy, precision, recall, F1-score, confusion matrix

## 📈 Results
- Best model: **Logistic Regression**
- Accuracy: ~80%
- F1-score: ~0.78
- Manual logistic regression implementation produced results close to `sklearn`, validating understanding of the underlying math

## 📁 Files
