[README.md](https://github.com/user-attachments/files/27443911/README.md)
# 🧠 Stroke Risk Data Analysis & Visualization

> Exploring the correlation between lifestyle factors and stroke incidents using real-world healthcare data.

---

## 📌 Project Overview

This project analyzes a healthcare dataset to identify which lifestyle and clinical factors are most associated with stroke risk. The pipeline covers end-to-end data preprocessing, exploratory data analysis (EDA), feature engineering, and data normalization — resulting in a clean, ML-ready dataset.

---

## 🗂️ Dataset

- **Source:** [Healthcare Stroke Dataset — Kaggle](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)
- **File:** `healthcare-dataset-stroke-data.csv`
- **Features:** Age, Gender, BMI, Average Glucose Level, Smoking Status, Hypertension, Heart Disease, and more
- **Target:** `stroke` (1 = had stroke, 0 = no stroke)

---

## 🔧 Project Pipeline

| Step | Description |
|------|-------------|
| 🧹 Data Cleaning | Handled missing values in BMI (median) and smoking_status (mode) |
| 📊 EDA | Visualized distributions, correlations, and stroke patterns across groups |
| 🚫 Outlier Treatment | Applied IQR method to BMI and Average Glucose Level |
| ⚙️ Feature Engineering | Created `bmi_category`, `age_category`, and `risk_factors_sum` |
| 🔄 Transformation | Binary encoding for `ever_married`, cast numerics to float |
| 📐 Normalization | Min-Max scaling applied to `age`, `bmi`, `avg_glucose_level` |
| 💾 Export | Cleaned dataset saved as `Cleaned Data.csv` |

---

## 📈 Key Findings

- **Age** is the strongest predictor — stroke cases concentrate heavily after age 40
- **Smokers** (current & former) show higher stroke rates than non-smokers
- **Higher glucose levels** strongly correlate with stroke occurrence
- **Overweight/Obese** patients have more stroke cases than healthy-weight individuals
- **Males** show a slightly higher stroke rate than females

---

## 🛠️ Tools & Libraries

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-white?style=flat&logo=matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)

---

## 📁 Repository Structure

```
├── final_project1.ipynb      # Main analysis notebook
├── FINAL_project.pbix        # Power BI dashboard
├── Cleaned Data.csv          # Processed & normalized dataset
└── README.md
```

---

## 🎥 Project Walkthrough

- 📹 [Part 1 — YouTube](https://youtu.be/3w9o1zYrSUI)
- 📹 [Part 2 — YouTube](https://youtu.be/QPygekgTNoE)

---

## 🤝 Contributors

| Name | LinkedIn |
|------|----------|
| [Donia Algharabli](https://www.linkedin.com/in/donia-algharabli-a2b736362/) | Collaborator & Teammate |

---

> 📌 *This project is part of a data science learning journey. The cleaned dataset is ready for downstream machine learning tasks such as stroke prediction classification.*

