# Task 6 – K-Nearest Neighbors (KNN) Classification
## Objective
To implement and understand the working of KNN on a classification problem using the Iris dataset.
## Dataset
**Iris Dataset** – Contains 3 flower species with 4 features (sepal length, sepal width, petal length, petal width
## Tools Used
- Python
- Scikit-learn
- Pandas
- Matplotlib
## Process
1. Loaded the Iris dataset
2. Normalized features using StandardScaler
3. Split data into train and test sets (80/20)
4. Trained KNN with K values from 1 to 10
5. Selected the best K based on accuracy
6. Plotted confusion matrix and decision boundaries (2D)
## Results

| K | Accuracy |
|---|----------|
| 1 | 0.93     |
| 3 | 1.00  |
| 5 | 0.96     |
| ... | ...    |
- Best Accuracy: **100% with K=3**
# Interview Takeaways
- **How KNN Works:** Classifies based on majority vote of nearest neighbors.
- **Importance of Normalization:** KNN uses distance – unscaled features skew results.
- **Choosing K:** Try multiple values; use odd numbers to avoid tie.
- **Time Complexity:** Slow during prediction, fast during training.
- **Sensitivity to Noise:** High – outliers can mislead classification.

---
 Status: Task Completed
