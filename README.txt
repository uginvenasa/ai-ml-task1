# Titanic Fare Prediction Using Linear Regression

This project explores the Titanic dataset to predict passenger fare using a linear regression model. The goal is to understand how different passenger attributes influence the ticket price.

---

## Objective

- Predict the fare paid by a passenger based on available features.
- Learn to clean data, apply linear regression, evaluate the model, and interpret the results.

---

## Dataset

- Source: Titanic dataset (Kaggle)
- Records: 891 rows × 12 columns
- Target variable: `Fare`

---

## Tools and Libraries Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## Data Preprocessing

- Removed irrelevant columns: `Name`, `Ticket`, `Cabin`
- Dropped rows with missing values
- Encoded categorical features:
  - `Sex`: male = 0, female = 1
  - `Embarked`: One-hot encoded (`Embarked_Q`, `Embarked_S`)

---

## Features Used

- Pclass
- Sex
- Age
- SibSp (number of siblings/spouses aboard)
- Parch (number of parents/children aboard)
- Embarked_Q
- Embarked_S

---

## Model Training

A linear regression model was trained using the Scikit-learn library.

```python
from sklearn.linear_model import LinearRegression
model = LinearRegression()
model.fit(X_train, y_train)
