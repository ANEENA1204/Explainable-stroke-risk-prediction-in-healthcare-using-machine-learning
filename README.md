# Explainable Stroke Risk Prediction Using Machine Learning and XAI

## Overview

This project presents an explainable machine learning framework for predicting stroke risk using healthcare data. Multiple machine learning models were implemented and evaluated to identify the most suitable approach for stroke risk prediction. The framework incorporates SHAP (SHapley Additive exPlanations) to improve the interpretability of model predictions.

The primary objective of this project is to provide accurate and transparent stroke risk prediction that can support healthcare decision-making.

---

## Features

- Stroke risk prediction using machine learning techniques.
- Data preprocessing and class balancing using SMOTE.
- Comparative analysis of six machine learning models.
- SHAP-based explainability for prediction interpretation.
- Performance evaluation using standard classification metrics.
- Proposed deployment framework for future web application development.

---

## Machine Learning Models Implemented

- Logistic Regression
- Random Forest
- XGBoost
- CatBoost
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

---

## Dataset

The project uses the Healthcare Stroke Prediction Dataset obtained from Kaggle.

Dataset Link:
https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

---

## Data Preprocessing Techniques

The dataset was preprocessed using:

- Missing value handling
- Label Encoding
- Standard Scaling
- SMOTE (Synthetic Minority Over-sampling Technique)

---

## Performance Evaluation Metrics

The implemented models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix Analysis

---

## Explainability Analysis

SHAP (SHapley Additive exPlanations) was used to:

- Identify the most influential features affecting stroke risk predictions.
- Improve model transparency.
- Provide interpretable prediction outcomes.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- CatBoost
- SHAP
- Matplotlib
- Jupyter Notebook

---

## Future Scope

The deployment phase of the project is currently under development. Future enhancements include:

- Streamlit-based web application.
- Real-time stroke risk prediction.
- Interactive SHAP visualizations.
- Deployment on cloud platforms.
- Clinical validation using larger healthcare datasets.

---

## Author

Aneena Sabu
