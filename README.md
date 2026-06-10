# 🩺 PCOD Prediction using Machine Learning (Random Forest)

## Overview

This project applies Machine Learning techniques to predict **Polycystic Ovarian Disease (PCOD/PCOS)** using clinical and healthcare variables.

The analysis includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation using multiple machine learning algorithms with **Random Forest achieving the strongest performance**.

---

## Problem Statement

Polycystic Ovarian Disease (PCOD) is a hormonal condition affecting women's reproductive health.

Early identification may support preventive care and improve clinical decision making.

This project builds predictive models to classify PCOD status based on patient healthcare indicators.

---

## Dataset Summary

| Metric | Value |
|---|---:|
| Records | 2,000 |
| Original Features | 44 |
| Final Features | 42 |
| Target Variable | PCOS (Y/N) |

---

## Project Workflow

```text
Data Collection
      ↓
Data Cleaning
      ↓
Missing Value Handling
      ↓
Feature Engineering
      ↓
EDA & Visualization
      ↓
Model Building
      ↓
Performance Evaluation
```

---

## Exploratory Data Analysis

Performed:

- Missing value analysis
- Distribution analysis
- Skewness evaluation
- Outlier inspection
- Feature cleaning
- Correlation exploration

Examples of variables analyzed:

- Age
- BMI
- AMH Levels
- Follicle Count
- Hormonal Indicators
- Pregnancy History
- Weight Gain
- Hair Growth

---

## Machine Learning Models Implemented

| Model | Accuracy |
|---|---:|
| Logistic Regression | 81% |
| Gaussian Naive Bayes | 83.25% |
| SVM (Linear) | 83.15% |
| SVM (RBF) | 85.40% |
| ⭐ Random Forest | **93.50%** |

---

## Best Model — Random Forest

Random Forest delivered the strongest predictive performance.

### Evaluation Results

```text
Confusion Matrix

[[276   2]
 [ 24  98]]
```

### Classification Report

```text
Precision (PCOD): 0.98
Recall (PCOD): 0.80
F1 Score: 0.88

Overall Accuracy: 93.5%
```

---

## Key Insights

- Random Forest achieved highest prediction performance
- Hormonal indicators contributed strongly to classification
- Follicle-related variables showed predictive importance
- Data preprocessing significantly improved model stability
- Nonlinear models outperformed traditional linear approaches

---

## Technologies Used

### Programming
- Python

### Libraries
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib

### Environment
- Jupyter Notebook

---

## Repository Structure

```text
📁 PCOD-Prediction
│
├── PCOD_random_forest_Analysis.ipynb
├── README.md
└── Dataset
```

---

## Future Improvements

- Hyperparameter tuning
- Feature importance dashboard
- Explainable AI (SHAP)
- Deployment using Streamlit
- Clinical decision support integration

---

## About Me

Developed by **Mohd Adnaan Khan**  
MS Health Data Science | Saint Louis University  

### Connect With Me

🔗 LinkedIn:  
https://www.linkedin.com/in/mohd-adnaan-khan-147b681a9/

💻 GitHub:  
https://github.com/Adnaan-khan

### Project Outcome

This project demonstrates practical application of machine learning in healthcare and highlights skills in data preprocessing, exploratory analysis, predictive modeling, and healthcare analytics.
---
