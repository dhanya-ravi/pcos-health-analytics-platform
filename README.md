# 🩺 PCOS Health Analytics Platform

<p align="center">

![Python](https://img.shields.io/badge/Python-3.13-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?logo=numpy)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue)
![Seaborn](https://img.shields.io/badge/Seaborn-EDA-76B900)
![Git](https://img.shields.io/badge/Git-Version%20Control-F05032?logo=git)
![License](https://img.shields.io/badge/Status-Portfolio-success)

</p>

---

## 📌 Project Overview

Polycystic Ovary Syndrome (PCOS) is one of the most common endocrine disorders affecting women of reproductive age. Early diagnosis is often challenging because symptoms vary widely between individuals.

This project demonstrates an **end-to-end data analytics and machine learning workflow** for predicting PCOS using demographic, hormonal, lifestyle, and ultrasound features.

The project covers:

- Data Understanding
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Statistical Testing
- Feature Engineering
- Machine Learning
- Model Evaluation

---

# 📑 Table of Contents

- Project Overview
- Objectives
- Dataset
- Repository Structure
- Workflow
- Exploratory Data Analysis
- Statistical Analysis
- Machine Learning
- Results
- Future Improvements
- Technologies Used
- Author

---

# 🎯 Objectives

- Understand the clinical characteristics of PCOS patients.
- Perform exploratory data analysis.
- Identify statistically significant clinical features.
- Build predictive machine learning models.
- Interpret feature importance.
- Generate actionable healthcare insights.

---

# 📊 Dataset

**Source:** Kaggle – PCOS Dataset

| Attribute | Value |
|------------|-------|
| Patients | 541 |
| Target Variable | PCOS (Yes/No) |
| Features | Clinical, Hormonal, Lifestyle, Ultrasound |

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

The analysis explored:

- Patient demographics
- BMI
- Lifestyle habits
- Clinical symptoms
- Hormonal profile
- Ultrasound measurements

### Key Findings

- Higher BMI observed among PCOS patients.
- Elevated AMH levels were associated with PCOS.
- Weight gain, skin darkening and excess hair growth showed strong associations.
- Follicle count emerged as one of the strongest predictors.

---

# 🔥 Correlation Analysis

> *(Add correlation heatmap screenshot here later)*

```markdown
![Correlation Heatmap](images/correlation_heatmap.png)
```

---

# 📊 Statistical Analysis

The Mann–Whitney U Test identified several statistically significant variables including:

- BMI
- FSH
- FSH/LH Ratio
- AMH

---

# 🤖 Machine Learning

Two supervised learning algorithms were evaluated.

| Model | Accuracy | Precision | Recall | ROC-AUC |
|--------|----------|-----------|---------|----------|
| Logistic Regression | 89.0% | 81.6% | 86.1% | 0.951 |
| Random Forest | **89.9%** | **90.3%** | 77.8% | 0.948 |

---

# 🌟 Feature Importance

Top predictors identified by Random Forest:

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

# 📷 Visualizations

Later we'll add screenshots like:

```markdown
![EDA](images/eda.png)

![Feature Importance](images/feature_importance.png)

![Model Comparison](images/model_comparison.png)

![Power BI Dashboard](images/dashboard.png)
```

---

# 🏆 Results

- End-to-end machine learning pipeline developed.
- Approximately **90% classification accuracy** achieved.
- Random Forest identified clinically meaningful predictors.
- Logistic Regression demonstrated strong screening capability due to higher recall.

---

# 🚀 Future Improvements

- Hyperparameter tuning
- XGBoost
- LightGBM
- SHAP Explainability
- Streamlit deployment
- Power BI Dashboard
- Real-world clinical validation

---

# 🛠 Technologies Used

| Category | Tools |
|------------|-----------------------------|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Development | Jupyter Notebook |
| Version Control | Git, GitHub |

---

# 👩‍💻 Author

**Dhanya Ravi**

Biomedical Engineer • M.Tech Medical Device Innovation

Interested in:

- Healthcare Data Analytics
- Product Management
- Machine Learning
- Digital Health

Connect on **LinkedIn** *(add your profile link here later)*

---

⭐ If you found this project interesting, feel free to explore the notebooks and reach out with feedback!
