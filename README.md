# AI-Based Phishing Website Detection

## Overview
This project implements a machine learning-based system to detect phishing websites using a dataset of 11,000+ samples.

## Problem Statement
Phishing websites are a major cybersecurity threat. Traditional blacklist methods fail to detect new (zero-day) phishing attacks. This project uses machine learning to classify websites as phishing or legitimate.

## Models Used
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- XGBoost
- Multi-Layer Perceptron (MLP)

## Results
- Best Model: Random Forest
- Accuracy: 97.42%
- F1 Score: 97.70%
- Validation: 10-fold cross-validation

## Key Highlights
- SHAP Explainability for feature importance
- Statistical validation using McNemar’s Test
- Feature engineering on URL, SSL, and web traffic data

## Tech Stack
- Python
- Scikit-learn
- XGBoost
- SHAP
- Pandas, NumPy, Matplotlib

## Future Scope
- Real-time phishing detection system
- Browser extension integration
- Deployment using lightweight ML models

## Author
Karthik Chowdhary
