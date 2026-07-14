# PCOS Health Analytics Platform

An end-to-end Machine Learning and Data Analytics project for predicting **Polycystic Ovary Syndrome (PCOS)** using clinical, hormonal, lifestyle, and ultrasound data.

---

## Project Overview

Polycystic Ovary Syndrome (PCOS) is one of the most common endocrine disorders affecting women of reproductive age. Early diagnosis is often challenging due to the wide range of symptoms and clinical presentations.

This project demonstrates a complete data analytics and machine learning workflow to identify key factors associated with PCOS and build predictive models capable of classifying patients based on clinical data.

---

## Objectives

- Perform data cleaning and preprocessing
- Explore demographic, clinical, hormonal, and lifestyle characteristics
- Identify statistically significant factors associated with PCOS
- Engineer features suitable for machine learning
- Train and evaluate predictive models
- Identify the most important predictors of PCOS

---

## Dataset

**Source:** Kaggle – PCOS Dataset

- **541 patient records**
- Clinical measurements
- Hormonal profile
- Lifestyle factors
- Ultrasound findings
- PCOS diagnosis (Target Variable)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Git & GitHub

---

# Project Workflow

```
Data Understanding
        ↓
Data Cleaning
        ↓
Exploratory Data Analysis
        ↓
Statistical Analysis
        ↓
Feature Engineering
        ↓
Machine Learning
        ↓
Model Evaluation
```

---

# Repository Structure

```
pcos-health-analytics-platform/

│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_data_understanding.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_exploratory_data_analysis.ipynb
│   ├── 04_feature_engineering.ipynb
│   └── 05_machine_learning.ipynb
│
├── dashboard/
│
├── reports/
│
├── requirements.txt
└── README.md
```

---

# Exploratory Data Analysis

The exploratory analysis examined:

- Patient demographics
- BMI distribution
- Lifestyle factors
- Hormonal profile
- Clinical symptoms
- Correlation analysis
- Statistical significance testing

Major findings included:

- Higher BMI was associated with PCOS.
- Elevated AMH levels were more common among PCOS patients.
- Weight gain, skin darkening, and excess hair growth showed strong associations with PCOS.
- Follicle count was one of the strongest predictors.

---

# Machine Learning Models

Two supervised learning models were developed:

### Logistic Regression

- Accuracy: **89.0%**
- ROC-AUC: **0.951**

Strengths:

- Highly interpretable
- Better recall for identifying PCOS patients

---

### Random Forest

- Accuracy: **89.9%**
- ROC-AUC: **0.948**

Strengths:

- Higher precision
- Better overall classification performance
- Feature importance analysis

---

# Top Predictive Features

The Random Forest model identified the following as the most important predictors:

1. Follicle Number (Right Ovary)
2. Follicle Number (Left Ovary)
3. Weight Gain
4. Skin Darkening
5. Hair Growth
6. AMH
7. Cycle Length
8. Menstrual Regularity
9. FSH/LH Ratio
10. BMI

---

# Key Results

- Successfully built an end-to-end machine learning pipeline.
- Achieved approximately **90% prediction accuracy**.
- Identified clinically meaningful predictors associated with PCOS.
- Demonstrated both interpretable and ensemble machine learning approaches.

---

# Future Improvements

- XGBoost and LightGBM models
- Hyperparameter tuning
- Cross-validation
- SHAP Explainability
- Power BI Dashboard
- Deployment using Streamlit

---

# Author

**Dhanya Ravi**

Biomedical Engineer | Medical Device Innovation | Healthcare Data Analytics | Product Management
