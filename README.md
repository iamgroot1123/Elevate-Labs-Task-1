# Task 1: Data Cleaning & Preprocessing

This repository contains the first task of my internship at **Elevate Labs**, focused on cleaning and preprocessing the Titanic dataset for machine learning.

## 📌 Objective

Prepare raw Titanic passenger data for modeling by performing essential preprocessing steps including:

- Handling missing values
- Encoding categorical features
- Feature scaling
- Outlier detection and removal

## 🛠️ Tools Used

- Python
- Pandas
- NumPy
- Seaborn / Matplotlib

## 🔍 Steps Performed

1. **Data Exploration**  
   Loaded dataset and explored column data types, missing values, and distributions.

2. **Missing Values Handling**  
   - Filled `Age` with median age  
   - Imputed `Embarked` with mode  
   - Dropped `Cabin` due to excessive missing values

3. **Categorical Encoding**  
   - Label encoded `Sex`  
   - One-hot encoded `Embarked`

4. **Feature Scaling**  
   - Applied Standardization to `Age` and `Fare` columns

5. **Outlier Detection & Removal**  
   - Used boxplots and IQR method to detect outliers in `Age` and `Fare`  
   - Removed extreme outliers

## 📁 Files

- `task1.ipynb` - Notebook containing all preprocessing code
- `README.md` - This documentation

## 📊 Dataset

Dataset: [Kaggle Titanic: Machine Learning from Disaster]([https://www.kaggle.com/c/titanic/data](https://www.kaggle.com/datasets/yasserh/titanic-dataset/data))
