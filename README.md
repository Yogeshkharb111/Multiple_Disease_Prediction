# 🧠 Multi-Disease Prediction System with Streamlit

An interactive web-based application built with **Streamlit** to predict the likelihood of multiple health conditions using machine learning models. This project demonstrates how to integrate trained models into a user-friendly interface to support preventive healthcare.

## 💡 Overview

This system enables users to input medical information and receive real-time predictions for:
- 🫀 Heart Disease
- 🍬 Diabetes
- 🧫 Chronic Kidney Disease

It uses individual machine learning models trained on disease-specific datasets and packages them into a single Streamlit app.

## 🎯 Objectives

- Build and train predictive models for multiple diseases
- Design interactive, responsive UI using Streamlit
- Enable real-time disease prediction through simple inputs
- Provide a lightweight deployable healthcare analytics tool

## 🧪 Datasets Used

- **Heart Disease**: UCI Heart Disease dataset  
- **Diabetes**: Pima Indians Diabetes dataset  
- **Kidney Disease**: UCI Chronic Kidney Disease dataset

All datasets were preprocessed to handle missing values, encode categorical features, and normalize numerical attributes as needed.

## 🛠️ Tech Stack

- **Python**
- **Jupyter Notebooks**
- **Streamlit**
- **Scikit-learn**
- **Pandas**
- **NumPy**
- **Matplotlib / Seaborn** (for EDA)

## 📈 Machine Learning Models

Each disease has its own trained model using appropriate algorithms:

- Logistic Regression
- Random Forest
- Support Vector Machine
- K-Nearest Neighbors (KNN)

Models were evaluated using:
- Accuracy
- Precision, Recall
- Confusion Matrix
- ROC-AUC Score

## 💻 How to Run

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/multi-disease-predictor.git
   cd multi-disease-predictor
