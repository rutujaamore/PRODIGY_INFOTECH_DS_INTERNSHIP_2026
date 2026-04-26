Task-02: Titanic Dataset - Data Cleaning & EDA
Objective: Perform Exploratory Data Analysis (EDA) and data cleaning on the famous Titanic dataset to identify factors that influenced passenger survival.

Project Overview
The Titanic dataset is a classic "messy" data science problem. This task involved preparing the raw data for analysis by handling missing values and then exploring the relationships between passenger demographics (Age, Sex, Class) and their survival outcomes.

Data Cleaning Process
Imputation: Identified missing values in the Age column and filled them with the Median, as the distribution was skewed.

Categorical Fixes: Handled missing Embarked values by using the Mode (most frequent port).

Dimensionality Reduction: Dropped the Cabin column due to an 80% null-rate, ensuring the model remains accurate and unbiased.

Data Type Management: Converted categorical variables into a format suitable for correlation analysis.

Insights Discovered
Gender Bias: Visual analysis confirmed that female passengers had a significantly higher survival rate than males, consistent with "women and children first" protocols.

Socio-Economic Impact: Passengers in 1st Class had a much higher survival probability compared to those in 3rd Class, highlighting a strong correlation between ticket fare and safety.

Feature Correlation: A heatmap revealed strong negative correlations between Pclass and Fare, and identified the key features that most directly impacted survival.

Visualizations Included

Count Plots: Survival rates categorized by Gender and Passenger Class.

Heatmap: Correlation matrix of all numerical features.

Distribution Plots: Age distribution of survivors vs. non-survivors.
