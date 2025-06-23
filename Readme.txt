# AI & ML Internship - Task 1: Data Cleaning & Preprocessing

## Objective
To clean and prepare raw data for machine learning using Python.

## Dataset Used
Titanic dataset (CSV format) from Kaggle.

## Steps Performed
1. Loaded the dataset using Pandas
2. Explored data: `.info()`, `.describe()`, `.isnull().sum()`
3. Handled missing values:
   - Filled `Age` with median
   - Filled `Embarked` with mode
   - Dropped `Cabin` due to too many nulls
4. Encoded categorical variables (`Sex`, `Embarked`) using one-hot encoding
5. Standardized numerical columns (`Age`, `Fare`) using `StandardScaler`
6. Visualized outliers in `Age` using a boxplot and removed them using IQR method
7. Saved the cleaned dataset as `titanic_cleaned.csv`

## Tools Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## Output
Cleaned dataset: `titanic_cleaned.csv`  
Notebook: `Task1_DataCleaning.ipynb`
