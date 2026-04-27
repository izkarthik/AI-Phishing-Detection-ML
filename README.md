# AI-Based Phishing Website Detection

## Overview
This project implements a machine learning-based system to detect phishing websites using the UCI Phishing Websites Dataset (11,000+ samples). It focuses on identifying malicious websites based on URL, domain, and behavioral features.

## Problem Statement
Phishing attacks are a major cybersecurity threat where attackers create fake websites to steal sensitive information. Traditional blacklist-based systems fail to detect new (zero-day) phishing websites. This project uses machine learning to provide a scalable and intelligent detection solution.

## Models Used
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- XGBoost
- Multi-Layer Perceptron (MLP)

## Results
- Best Model: Random Forest
- Accuracy: **97.42%**
- F1 Score: **97.70%**
- Validation: **10-fold cross-validation**

## Key Highlights
- Applied **SHAP Explainability** for feature importance analysis
- Performed **statistical validation (McNemar’s Test)**
- Compared multiple ML models for performance evaluation
- Feature engineering on **URL, SSL, and web traffic data**

## Dataset
- Source: UCI Machine Learning Repository  
- Name: Phishing Websites Dataset  
- Size: 11,055 samples, 30 features  

## Tech Stack
- Python
- Scikit-learn
- XGBoost
- SHAP
- Pandas, NumPy, Matplotlib

## Future Scope
- Real-time phishing detection system
- Browser extension integration
- API-based phishing detection service
- Deployment using lightweight ML models

## Author
Karthik Chowdhary
