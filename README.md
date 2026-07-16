# 🎓 Student Performance Classification Using Machine Learning

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python)
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

> **An end-to-end machine learning project that predicts student academic success using demographic, behavioral, and academic data while demonstrating a complete predictive analytics workflow from data preparation to business recommendations.**

---

# 📖 Project Overview

Educational institutions increasingly rely on predictive analytics to identify students who may benefit from additional academic support. Early identification allows advisors and instructors to intervene before academic performance declines.

This project develops and compares multiple supervised machine learning models to classify whether a student is likely to pass or fail based on academic performance, study habits, attendance, lifestyle, and demographic characteristics.

The project emphasizes not only predictive performance but also model interpretability, ethical AI practices, and practical business recommendations for educational decision-makers.

---

# 🎯 Business Objective

The objective of this project is to develop a predictive classification model capable of identifying students who may be at academic risk while maintaining transparency, fairness, and responsible use of educational data.

Potential applications include:

- Early intervention programs
- Academic advising
- Student retention initiatives
- Resource allocation
- Institutional decision support

---

# 📂 Repository Structure

```text
student-exam-performance-classification/

├── data/
│   ├── raw/
│   ├── processed/
│   └── model/
│
├── images/
│   ├── correlation_heatmap.png
│   ├── feature_importance.png
│   ├── model_comparison.png
│   ├── pass_fail_distribution.png
│   └── study_hours_vs_gpa.png
│
├── models/
│   ├── gradient_boosting.pkl
│   ├── random_forest.pkl
│   ├── decision_tree.pkl
│   ├── logistic_regression.pkl
│   └── scaler.pkl
│
├── notebooks/
│   ├── 01_Data_Understanding.ipynb
│   ├── 02_Data_Preparation.ipynb
│   ├── 03_Exploratory_Data_Analysis.ipynb
│   ├── 04_Feature_Engineering.ipynb
│   ├── 05_Model_Development.ipynb
│   ├── 06_Model_Evaluation.ipynb
│   └── 07_Project_Summary.ipynb
│
├── reports/
├── README.md
└── LICENSE
```

---

# 🔄 Project Workflow

```text
Data Understanding
        ↓
Data Preparation
        ↓
Exploratory Data Analysis
        ↓
Feature Engineering
        ↓
Machine Learning Models
        ↓
Model Evaluation
        ↓
Business Recommendations
        ↓
Project Summary
```

---

# 🛠 Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- Jupyter Notebook

---

# 🤖 Machine Learning Models

The following supervised learning algorithms were developed and evaluated:

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting

Performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

---

# 🏆 Model Performance

| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|-------|---------:|----------:|--------:|---------:|--------:|
| **Gradient Boosting** | **0.9650** | **0.9667** | **0.9979** | **0.9821** | **0.9373** |
| Random Forest | 0.9610 | 0.9610 | 1.0000 | 0.9801 | 0.9296 |
| Logistic Regression | 0.9610 | 0.9610 | 1.0000 | 0.9801 | 0.9127 |
| Decision Tree | 0.8765 | 0.9878 | 0.8824 | 0.9321 | 0.8750 |

---

# 📊 Visualizations

## Machine Learning Model Comparison

![Machine Learning Model Comparison](images/model_comparison.png)

---

## Random Forest Feature Importance

![Feature Importance](images/feature_importance.png)

---

## Correlation Heatmap

![Correlation Heatmap](images/correlation_heatmap.png)

---

## Study Hours vs Overall GPA

![Study Hours vs GPA](images/study_hours_vs_gpa.png)

---

## Student Pass vs Fail Distribution

![Pass Fail Distribution](images/pass_fail_distribution.png)

---

# 🔍 Key Findings

- Study hours per week were the strongest predictor of academic success.
- Sleep duration, stress level, attendance rate, and motivation score were among the most influential variables.
- Behavioral and academic factors contributed more to predictive performance than demographic characteristics.
- Gradient Boosting achieved the highest ROC-AUC score while maintaining excellent overall classification performance.
- Feature importance analysis provides actionable insights that educational institutions can use to support student success initiatives.

---

# ⚖️ Ethics & Responsible AI

This project considers responsible use of predictive analytics by addressing:

- Student privacy and confidentiality
- Ethical use of educational data
- Transparency and model interpretability
- Human oversight in academic decision-making
- Awareness of algorithmic bias
- Responsible AI practices
- Data governance principles

Predictive models should be used to support educators and advisors—not to replace human judgment or make automated decisions affecting students.

---

# 🚀 Future Improvements

Potential future enhancements include:

- Hyperparameter optimization
- K-Fold Cross Validation
- XGBoost and LightGBM models
- SHAP Explainability
- Fairness and bias evaluation metrics
- Streamlit dashboard deployment
- Automated model retraining pipeline
- Real-time prediction API

---

# 👩‍💻 Author

**Tessa Becker**

**Founder, Kronos Intelligence**

Specializing in:

- Data Analytics
- Predictive Analytics
- Machine Learning
- Data Governance
- Business Intelligence

---

## ⭐ If you found this project interesting, consider starring the repository!

Data Analytics | Data Governance | Machine Learning

Building data-driven solutions through **Kronos Intelligence**.
