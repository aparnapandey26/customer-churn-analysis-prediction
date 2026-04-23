# Customer Churn Analysis & Prediction

## 📌 Project Overview
This project focuses on predicting customer churn using Machine Learning techniques. Customer churn refers to customers who stop using a company's service. The main goal is to analyze customer data, find patterns, and build a model that can predict whether a customer will churn or not.

## 🎯 Problem Statement
Businesses want to reduce customer loss. By predicting churn in advance, companies can take actions like offers, discounts, or better services to retain customers.

## 🎯 Objective
- Perform Exploratory Data Analysis (EDA)
- Understand factors affecting customer churn
- Build machine learning models
- Compare model performance
- Select best model for prediction

## 📂 Dataset Information
The dataset contains customer information such as:
- Customer demographics
- Account information
- Service usage details
- Whether the customer churned or not (target variable)

## 🛠️ Technologies Used
- Python 🐍  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- XGBoost  

## 🤖 Machine Learning Models Used
- Logistic Regression (Baseline Model)
- Random Forest Classifier
- XGBoost Classifier (Best Performing Model)

## 📊 Project Workflow
1. Data Collection
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Prediction

## 📈 Evaluation Metrics
Since this is a classification problem, we used:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score ⭐ (Most Important for Churn)

## 🔥 Results
- Random Forest performed well on baseline evaluation  
- XGBoost gave the best performance overall  
- ROC-AUC score showed strong ability to distinguish churn vs non-churn customers  
- Final model selected: **XGBoost Classifier**

## 📊 Key Insights
- Certain customer behaviors strongly indicate churn  
- Contract type and usage patterns are important factors  
- High-risk customers can be identified early  

## 🚀 How to Run This Project
```bash
# Clone repository
git clone https://github.com/your-username/customer-churn-analysis-prediction.git

# Go to project folder
cd customer-churn-analysis-prediction

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook
