AI & ML Internship - Task 2: Exploratory Data Analysis (EDA)
Objective
Perform Exploratory Data Analysis (EDA) on the Titanic dataset to understand data patterns, detect anomalies, and visualize relationships between features.
Dataset
- Dataset used: `Titanic-Dataset.csv`
- Source: Kaggle Titanic Survival Dataset
Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
Steps Performed

1. Data Loading and Inspection
   - Loaded dataset using `pandas.read_csv()`
   - Checked dataset shape, data types, and missing values
   - Used `.info()` and `.describe()` for summary statistics
2.Handling Missing Values
   - Observed missing values in columns like `Age`, `Cabin`, and `Embarked`
   - No imputation done as this task focused on EDA, not preprocessing
3.Visualizations
   - **Histograms** for `Age`, `Fare`, etc., to understand distributions
   - **Boxplots** to detect outliers in numerical features
   - **Pairplots** to observe feature interactions
   - **Correlation Heatmap** to see feature correlations (after encoding categorical features)
4. Categorical Encoding for Correlation
   - Mapped `Sex` and `Embarked` columns to numeric values
   - Dropped non-numeric columns (`Name`, `Cabin`, `Ticket`) for correlation analysis
5. Key Inferences
   - Survival rate is higher for females
   - Passengers in higher classes (Pclass=1) had higher survival
   - Fare is positively correlated with Pclass
   - Age and Fare distributions are right-skewed
   - Outliers present in the `Fare` column
Optional Visualizations
- Interactive scatter plots using Plotly (if supported by system)
Files Included
- `Task2_EDA_Titanic.ipynb` – Jupyter notebook with full analysis
- `Titanic-Dataset.csv` – Dataset used
- `README.md` – Task explanation and steps
Outcome
This task helped in understanding the importance of EDA in identifying data quality issues, patterns, correlations, and initial insights — which are crucial for building effective ML models.