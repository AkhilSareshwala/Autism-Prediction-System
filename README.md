# 🧠 Autism Spectrum Disorder (ASD) Prediction System

A **Machine Learning** based end-to-end pipeline to predict **Autism Spectrum Disorder (ASD)** using questionnaire scores, demographic details, and medical history.  
This project leverages **EDA, data preprocessing, feature engineering, class balancing (SMOTE)**, multiple model training, hyperparameter tuning, and **deployment-ready serialization**.

---

## 📜 Project Overview

The ASD Prediction System is designed to detect potential autism cases by learning from a Kaggle dataset.  
It implements **best practices in ML workflows**, from **data cleaning to deployment**, using industry-standard Python libraries.

---

## ✨ Features

- 📂 **Data Loading & Cleaning**  
  - Handles missing values represented as `?`  
  - Drops irrelevant columns  
  - Fixes inconsistent categorical entries  

- 📊 **Exploratory Data Analysis (EDA)**  
  - Univariate & bivariate analysis  
  - Distribution plots, heatmaps, and outlier detection  

- 🛠 **Data Preprocessing**  
  - Outlier handling using median replacement  
  - Label encoding for categorical variables (with saved encoders)  
  - Class imbalance handling with **SMOTE**  

- 🤖 **Model Training & Selection**  
  - Models: **Decision Tree**, **Random Forest**, **XGBoost**  
  - Cross-validation for performance comparison  

- ⚙️ **Hyperparameter Tuning**  
  - **RandomizedSearchCV** for optimal parameters  
  - Performance boost without overfitting  

- 📈 **Model Evaluation**  
  - Accuracy score, confusion matrix, classification report  

- 💾 **Deployment Ready**  
  - Pickle serialization of best model & encoders for reuse  

---

## 🗂 Dataset

**Source:** Kaggle Autism Screening Dataset  
**Size:** 800 samples × 22 features  
**Target Variable:** `Class/ASD` (1 = ASD, 0 = Not ASD)

---

## 🛠 Tech Stack

| Category                | Tools/Tech |
|-------------------------|------------|
| Language                | Python 🐍 |
| Data Processing         | Pandas, NumPy |
| Visualization           | Matplotlib, Seaborn 📊 |
| Machine Learning        | Scikit-learn 🤖, XGBoost ⚡ |
| Imbalanced Data Handling| imbalanced-learn (SMOTE) ⚖️ |
| Hyperparameter Tuning   | RandomizedSearchCV |
| Model Persistence       | Pickle 💾 |


---

## 📊 Model Performance

**Best Model:** Random Forest Classifier 🌳  
**Accuracy (Test Set):** ~ **85-90%** (varies with seed)  
