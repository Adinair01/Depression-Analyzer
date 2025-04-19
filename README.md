# 🧠 Depression Analyzer using Machine Learning

A machine learning-powered web application that predicts the likelihood of depression in students based on a dataset of behavioral, emotional, and academic indicators.

## 📁 Project Structure

- `app.py` – Web application interface (Streamlit or Flask).
- `train.py` – Model training script.
- `depression_model.pkl` – Trained machine learning model.
- `scaler.pkl` – Preprocessing scaler object (used for consistent input transformation).
- `student_depression_dataset.csv` – Dataset used for training the model.

## 📊 Dataset

The model is trained on `student_depression_dataset.csv`, which contains anonymized data on student behavior, academic performance, and mental health indicators.  
The dataset is preprocessed and scaled before training to ensure consistency and performance.

> ⚠️ **Disclaimer**: This dataset is used for educational purposes only and does not replace professional psychological evaluation.

## 🧠 Model Overview

- **Model Type**: (Specify model used here e.g., Logistic Regression / Random Forest / SVM)
- **Features Used**: (List a few important features like Sleep Quality, Study Hours, Social Activity, etc.)
- **Target**: Depression status (binary classification)

