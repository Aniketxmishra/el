# Titanic Dataset - AI & ML Internship Projects

---

## Overview

This repository contains solutions for Task 1 and Task 2 of the AI & ML Internship at Elevate Labs, focused on the Titanic dataset.

- **Task 1:** Data Cleaning and Preparation for Machine Learning  
- **Task 2:** Exploratory Data Analysis (EDA) and Pattern Recognition

---

## Task 1: Data Cleaning & Preparation

### Objective

Learn how to clean and prepare raw data for machine learning using Python and standard data science libraries.

### Dataset

- **Dataset Used:** Titanic Dataset  
- **Source:** [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

### Tools & Libraries

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- scikit-learn  

### Steps Performed

1. Import & explore data (data types, missing values, statistics)  
2. Handle missing values (imputation for `Age`, `Fare`, `Embarked`, drop `Cabin`)  
3. Remove duplicates  
4. Encode categorical variables (`Sex`, `Embarked`) using one-hot encoding  
5. Feature scaling using `StandardScaler`  
6. Outlier detection and removal (IQR method on `Fare`)  
7. Visualization of survival counts, distributions, and correlations  
8. Save cleaned dataset as `titanic_cleaned.csv`  

### Files Included

- `AI_ML_Task1.ipynb` — Notebook with code and visualizations  
- `titanic_cleaned.csv` — Cleaned dataset  

### What I Learned

- Handling missing data and categorical encoding  
- Difference between normalization and standardization  
- Outlier detection and removal techniques  
- Importance of data preprocessing in ML pipelines  

### Interview Preparation Questions

1. What are the different types of missing data?  
2. How do you handle categorical variables?  
3. What is the difference between normalization and standardization?  
4. How do you detect outliers?  
5. Why is preprocessing important in ML?  
6. What is one-hot encoding vs label encoding?  
7. How do you handle data imbalance?  
8. Can preprocessing affect model accuracy?  

### How to Run

1. Clone this repository or download the files.  
2. Open `AI_ML_Task1.ipynb` in Jupyter Notebook or Google Colab.  
3. Run all cells to reproduce the results.  

---

## Task 2: Exploratory Data Analysis (EDA)

### Objective

Perform comprehensive exploratory data analysis to uncover patterns, trends, and relationships in the Titanic dataset using statistical methods and visualizations.

### Tools & Libraries

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Plotly  
- Google Colab  

### Analysis Highlights

- Summary statistics and missing value analysis  
- Histograms and box plots for numerical features  
- Correlation matrix and pairplots  
- Survival analysis by gender, class, and age groups  
- Detection of skewness and outliers  
- Interactive visualizations with Plotly  
- Insights and recommendations for machine learning modeling  

### Files Included

- `notebooks/Titanic_EDA_Analysis.ipynb` — Complete EDA notebook with code and visualizations  
- `reports/eda_summary_report.txt` — Summary of key findings and recommendations  
- `visualizations/` — Folder containing saved plots and charts  

### Key Findings

- Women and first-class passengers had significantly higher survival rates  
- Age and fare distributions influence survival chances  
- Fare is highly right-skewed with notable outliers  
- Missing data primarily in `Age`, `Cabin`, and `Embarked` columns  

### How to Run

1. Open the `notebooks/Titanic_EDA_Analysis.ipynb` notebook in Google Colab or Jupyter Notebook.  
2. Run all cells sequentially to reproduce the analysis and visualizations.  

---

## Repository Structure

