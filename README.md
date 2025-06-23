# Task-1
# Titanic Dataset - Data Cleaning & Preprocessing 

##  Objective
This task is a first step on learning the essential preprocessing steps before applying machine learning algorithms.

##  Dataset
https://www.kaggle.com/datasets/yasserh/titanic-dataset

##  Steps

1. Loaded the dataset
2. Explored null values and datatypes
3. Filled missing values:
   - `Age` with median
   - `Embarked` with mode
   - Dropped `Cabin` due to too many nulls
4. **Converted categorical variables**:
   - `Sex` using Label Encoding
   - `Embarked` using One-Hot Encoding
5. **Standardized numerical features** (`Age`, `Fare`)
6. **Visualized and removed outliers** using Boxplot and IQR method

##  Files Included
- `titanic_preprocessing.py` – Full code
- `titanic_cleaned.csv` – Cleaned dataset output
- `boxplot.png` – Optional saved visualization (if you save it manually)
- `README.md` – Project explanation


