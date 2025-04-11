Business Problem:

Develop a machine learning model that accurately predicts whether a customer is likely to leave the company (churn), enabling proactive retention strategies.

Project Workflow
	1. Importing Required Libraries
Set up environment with essential ML, visualization, and preprocessing libraries.
	2. Data Loading & Setup
Load the dataset and configure display settings for effective exploration.
	3. Exploratory Data Analysis (EDA)
		○ Detect numeric and categorical features
		○ Univariate and bivariate analysis
		○ Target-wise variable insights
		○ Log transformation for skewed target variable
		○ Correlation matrix & heatmap visualization
	4. Data Preprocessing
		○ Missing Value Analysis: Identify and impute or drop missing data
		○ Outlier Analysis: Treat extreme values
		○ Feature Engineering: Create meaningful new variables
		○ Encoding: Apply Label, One-Hot, or Rare Encoding
		○ Scaling: StandardScaler, MinMaxScaler, or RobustScaler
	5. Model Development
		○ Baseline Models: Train multiple models including Logistic Regression, Random Forest, XGBoost, LightGBM, CatBoost, KNN, Decision Tree
		○ Evaluation Metrics: Accuracy, Precision, Recall, F1, ROC-AUC
		○ Model Comparison Before and After Feature Engineering
		○ Feature Importance Analysis
	6. Model Tuning
		○ Hyperparameter tuning using GridSearchCV and RandomizedSearchCV
		○ Cross-validation for generalization performance

🧠 Models Used:
Logistic Regression
Random Forest
XGBoost
LightGBM
CatBoost
KNN
Decision Tree

📊 Tools & Libraries:
scikit-learn, xgboost, lightgbm, catboost, pandas, numpy, seaborn, matplotlib, plotly
