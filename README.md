# 🩺 PCOS Health Analytics Platform

<p align="center">

![Python](https://img.shields.io/badge/Python-3.13-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?logo=numpy)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?logo=scikitlearn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue)
![Seaborn](https://img.shields.io/badge/Seaborn-EDA-76B900)
![Git](https://img.shields.io/badge/Git-Version%20Control-F05032?logo=git)
![Status](https://img.shields.io/badge/Project-Portfolio-success)

</p>

---

# 📌 Project Overview

Polycystic Ovary Syndrome (PCOS) is one of the most common endocrine disorders affecting women of reproductive age. Early diagnosis is often challenging because symptoms vary widely between individuals.

This project demonstrates an **end-to-end data analytics and machine learning workflow** for predicting PCOS using demographic, clinical, hormonal, lifestyle, and ultrasound features.

The project covers:

- Data Understanding
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Feature Engineering
- Machine Learning
- Model Evaluation

---

# 📑 Table of Contents

- [Project Overview](#-project-overview)
- [Objectives](#-objectives)
- [Dataset](#-dataset)
- [Repository Structure](#-repository-structure)
- [Project Workflow](#-project-workflow)
- [Exploratory Data Analysis](#-exploratory-data-analysis)
- [Correlation Analysis](#-correlation-analysis)
- [Statistical Analysis](#-statistical-analysis)
- [Machine Learning](#-machine-learning)
- [Feature Importance](#-feature-importance)
- [Results](#-results)
- [Future Improvements](#-future-improvements)
- [Technologies Used](#-technologies-used)
- [Author](#-author)

---

# 🎯 Objectives

- Understand the demographic, clinical, and hormonal characteristics of PCOS patients.
- Perform exploratory data analysis to identify trends and patterns.
- Identify statistically significant variables associated with PCOS.
- Prepare the dataset for machine learning.
- Build predictive machine learning models.
- Evaluate model performance using standard classification metrics.
- Identify the most important predictors of PCOS.

---

# 📊 Dataset

**Source:** Kaggle – PCOS Dataset

| Attribute | Value |
|------------|-------|
| Number of Patients | 541 |
| Target Variable | PCOS (Yes/No) |
| Features | Clinical, Hormonal, Lifestyle & Ultrasound |

---

# 🗂 Repository Structure

```text
pcos-health-analytics-platform

├── data
│   ├── raw
│   └── processed
│
├── notebooks
│   ├── 01_data_understanding.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_exploratory_data_analysis.ipynb
│   ├── 04_feature_engineering.ipynb
│   └── 05_machine_learning.ipynb
│
├── dashboard
├── images
├── reports
├── requirements.txt
└── README.md
```

---

# 🔄 Project Workflow

```text
Raw Dataset
      │
      ▼
Data Understanding
      │
      ▼
Data Cleaning
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Statistical Analysis
      │
      ▼
Feature Engineering
      │
      ▼
Machine Learning
      │
      ▼
Model Evaluation
```

---

# 📈 Exploratory Data Analysis

The exploratory analysis focused on understanding patient demographics, lifestyle factors, clinical characteristics, hormonal profile, and ultrasound measurements.

### Key Findings

- Patients diagnosed with PCOS generally exhibited a higher BMI.
- Elevated Anti-Müllerian Hormone (AMH) levels were strongly associated with PCOS.
- Weight gain, skin darkening, and excess hair growth showed clear associations with PCOS.
- Follicle count emerged as one of the strongest distinguishing clinical features.

---

# 🔥 Correlation Analysis

<p align="center">
<img width="900" alt="Correlation Heatmap" src="https://github.com/user-attachments/assets/52048e66-6ae2-4d2f-9cec-df4f59c3c6b7">
</p>

The correlation heatmap was used to examine relationships among numerical variables and identify potential multicollinearity prior to model development.

---

# 📊 Statistical Analysis

The Mann–Whitney U Test was used to compare feature distributions between patients with and without PCOS.

Statistically significant variables included:

- BMI
- FSH
- FSH/LH Ratio
- AMH

These findings supported the exploratory analysis and highlighted clinically relevant predictors for machine learning.

---

# 🤖 Machine Learning

Two supervised classification models were developed and evaluated.

| Model | Accuracy | Precision | Recall | ROC-AUC |
|--------|----------|-----------|---------|----------|
| Logistic Regression | 89.0% | 81.6% | **86.1%** | **0.951** |
| Random Forest | **89.9%** | **90.3%** | 77.8% | 0.948 |

### Key Observations

- Random Forest achieved the highest overall accuracy and precision.
- Logistic Regression achieved higher recall, making it more effective at identifying positive PCOS cases.
- Both models demonstrated excellent discrimination with ROC-AUC values close to 0.95.

---

# 🌟 Feature Importance

The Random Forest model identified the following variables as the strongest predictors of PCOS:

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

These findings are consistent with established clinical indicators reported in the literature.

---

# 🏆 Results

- Developed a complete end-to-end machine learning pipeline for PCOS prediction.
- Achieved approximately **90% classification accuracy**.
- Identified clinically meaningful predictors using feature importance analysis.
- Demonstrated strong predictive performance using both interpretable and ensemble machine learning models.

---

# 🚀 Future Improvements

- Hyperparameter tuning using GridSearchCV or RandomizedSearchCV
- Evaluate additional models such as XGBoost and LightGBM
- Perform cross-validation for more robust evaluation
- Incorporate SHAP for model explainability
- Develop an interactive Power BI dashboard
- Deploy the solution using Streamlit

---

# 🛠 Technologies Used

| Category | Tools |
|------------|-----------------------------|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Development Environment | Jupyter Notebook |
| Version Control | Git, GitHub |

---

# 👩‍💻 Author

**Dhanya Ravi**

Biomedical Engineer | M.Tech in Medical Device Innovation

**Areas of Interest**

- Healthcare Data Analytics
- Product Management
- Machine Learning
- Digital Health
- Clinical Data Science

---

⭐ If you found this project interesting, consider giving it a star or exploring the notebooks to learn more about the complete analytics and machine learning workflow.
