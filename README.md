1. The dataset is imported using `pd.read_csv()` and stored in a DataFrame called `df`.

2. Basic structure and summary statistics are viewed using `.info()`, `.describe()`, and `.value_counts()` to understand the data.

3. Irrelevant or constant columns like `EmployeeCount`, `Over18`, and `StandardHours` are dropped.

4.  Categorical variables are converted into numeric format using `LabelEncoder` to prepare them for machine learning models.

5.  Numerical features are scaled using `StandardScaler` to normalize the feature distribution.

6.  The dataset is imbalanced (more 'No' attrition than 'Yes'), so SMOTE is used to oversample the minority class.

7. Countplots and heatmaps are used to visualize attrition patterns by job role and feature correlations.

8. Three classification models are built — Logistic Regression, Random Forest, and XGBoost.

9.  Each model is evaluated using accuracy, precision, recall, F1-score, and confusion matrix to assess performance.

10.  Random Forest feature importance is visualized to identify which factors most influence employee attrition.

