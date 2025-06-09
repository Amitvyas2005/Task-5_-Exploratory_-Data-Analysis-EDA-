Task 5_Exploratory Data Analysis (EDA)

Overview
Exploratory Data Analysis (EDA) on the Titanic dataset (train.csv) for Data Analyst Internship Task 5, using Pandas, Matplotlib, Seaborn, and NumPy to identify patterns and trends.

Dataset
Titanic dataset with 891 passengers, 12 columns: PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked.
Analysis

Setup: Loaded data, set Seaborn style.

Exploration: Used .info(), .describe(), .value_counts() for data overview.
Missing Values: Filled Age (median ~28), Embarked (mode 'S'), dropped Cabin (77% missing).
Univariate: Age histogram (right-skewed), Fare boxplot (highly skewed).
Bivariate: Countplots showed higher survival for 1st-class (62.9%) and females (74.2%).
Multivariate: Heatmap showed Pclass-Fare correlation (-0.55); scatterplot linked high fares to survival.
Skewness: Log-transformed Fare for symmetry.
Findings
Survival: 38.4% survived.
Pclass: 55% 3rd-class, survival: 62.9% (1st), 47.3% (2nd), 24.2% (3rd).
Sex: 65% male, survival: 74.2% (female), 18.9% (male).
Age: Median ~28, no survival correlation.
Fare: Median $14.45, log transformation reduced skewness.
Trends: 1st-class and females had higher survival.
Anomalies: High fare outliers; Cabin missingness.

Files
train.csv: Dataset
Task 5_ Exploratory_ Data Analysis (EDA).ipynb: EDA code and visualizations
Task 5_ Exploratory_ Data Analysis (EDA).pdf
Tools
Python: Pandas, Matplotlib, Seaborn, NumPy
Jupyter Notebook
