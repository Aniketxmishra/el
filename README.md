
## Objective

Learn how to clean and prepare raw data for machine learning using Python and standard data science libraries.

---

## Dataset

- **Dataset Used:** Titanic Dataset  
- **Source:** [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

---

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

---

## Steps Performed

1. **Import & Explore Data**
    - Loaded the Titanic dataset into a pandas DataFrame.
    - Explored data types, missing values, and basic statistics.

2. **Handle Missing Values**
    - Imputed missing values in numerical columns (`Age`, `Fare`) with the mean.
    - Imputed missing values in categorical columns (`Embarked`) with the mode.
    - Dropped columns with excessive missing values (e.g., `Cabin`).

3. **Remove Duplicates**
    - Checked for and removed duplicate rows.

4. **Encode Categorical Variables**
    - Converted categorical features (`Sex`, `Embarked`) into numerical format using one-hot encoding.

5. **Feature Scaling**
    - Standardized numerical features (`Age`, `Fare`) using `StandardScaler`.

6. **Outlier Detection & Removal**
    - Visualized outliers using boxplots.
    - Removed outliers from `Fare` using the Interquartile Range (IQR) method.

7. **Visualization**
    - Plotted survival counts by sex, age distribution by survival, fare distribution by class, feature correlation heatmap, and embarkation port counts.

8. **Save Cleaned Data**
    - Saved the cleaned dataset as `titanic_cleaned.csv`.

---

## Files Included

- `AI_ML_Task1.ipynb` — Jupyter/Colab notebook with all code and visualizations
- `titanic_cleaned.csv` — Cleaned Titanic dataset
- `README.md` — This file

---

## What I Learned

- How to handle missing data using imputation
- Encoding categorical variables for ML
- Normalization vs. standardization
- Outlier detection and removal
- The importance of data preprocessing in machine learning pipelines

---

## Interview Questions (Preparation)

1. What are the different types of missing data?
2. How do you handle categorical variables?
3. What is the difference between normalization and standardization?
4. How do you detect outliers?
5. Why is preprocessing important in ML?
6. What is one-hot encoding vs label encoding?
7. How do you handle data imbalance?
8. Can preprocessing affect model accuracy?

---

## How to Run

1. Clone this repository or download the files.
2. Open `Task_1.ipynb` in Jupyter Notebook or Google Colab.
3. Run all cells to reproduce the results.

---

## Submission

- [GitHub Repository Link](https://github.com/Aniketxmishra/el/)




