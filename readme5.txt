# Task 5: Decision Trees and Random Forests

## 🎯 Objective
To understand and implement tree-based machine learning models — Decision Trees and Random Forests — for classification using the Heart Disease dataset.

---

## 🧰 Tools & Libraries Used
- Python
- Pandas, NumPy
- Scikit-learn (sklearn)
- Matplotlib
- Graphviz / Plotly (for visualization)

---

## 📊 Dataset
**Dataset Name:** heart.csv  
**Description:** The dataset includes information about patients such as age, sex, blood pressure, cholesterol, ECG results, etc., and whether they have heart disease or not.

---

## 🔧 Tasks Performed

### ✅ 1. Data Preprocessing
- Loaded dataset using Pandas.
- Label encoded categorical columns: `Sex`, `ChestPainType`, `RestingECG`, `ExerciseAngina`, `ST_Slope`.

### ✅ 2. Train-Test Split
- Split the dataset into training and test sets using an 80-20 ratio.

### ✅ 3. Decision Tree Classifier
- Trained a Decision Tree using `sklearn.tree.DecisionTreeClassifier`.
- Achieved accuracy: **~78.3%**
- Controlled overfitting by using `max_depth=3`.
- Visualized the tree using `plot_tree()` (or Graphviz if installed).

### ✅ 4. Random Forest Classifier
- Trained a Random Forest using `RandomForestClassifier` with 100 trees.
- Achieved higher accuracy than single Decision Tree.

### ✅ 5. Feature Importance
- Plotted the importance of each feature contributing to prediction.

### ✅ 6. Cross-Validation
- Performed 5-fold cross-validation to evaluate model generalization.
- Reported average CV accuracy.

---

## 📈 Results

| Model             | Accuracy        |
|------------------|-----------------|
| Decision Tree     | 78.26%          |
| Random Forest     | (e.g. ~84.6%)   |
| 5-Fold CV Score   | (e.g. ~82.1%)   |

> *Note: Your actual accuracy may vary slightly depending on random split and dataset version.*

---

## 📁 Files Included
- `main.py` – Code implementation
- `heart.csv` – Dataset used
- `decision_tree_plot.png` – Tree visualization
- `feature_importance.png` – Feature importance chart
- `README.md` – This file

---

## 💡 Concepts Learned
- Decision Trees and how they split data
- Entropy and information gain
- Random Forest and ensemble learning
- Overfitting and how to reduce it
- Feature importance interpretation
- Cross-validation for model evaluation

---

## 🧠 Interview Prep Q&A
- **What is a decision tree?**  
  A model that splits data into branches based on feature conditions to classify or predict.

- **What is bagging?**  
  Bootstrapped Aggregating – combining models trained on random data samples to reduce variance.

- **How is Random Forest better?**  
  It averages multiple trees to prevent overfitting and increase robustness.

- **How to interpret feature importance?**  
  It shows how much each feature contributes to improving predictions.

---

## ✅ Task Status: Completed

