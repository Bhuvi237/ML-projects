# Titanic dataset - Exploratory data analysis(EDA)
This file contains the Exploratory Data Analysis (EDA) performed on the Titanic Dataset. The objective of this project is to explore, clean, visualize, and understand the dataset to identify patterns and relationships that could help in predicting passenger survival.

# Dataset Description
Source: Kaggle - Titanic Dataset

# Features
Survived: 0 = No, 1 = Yes
Pclass: Passenger class (1, 2, 3)
Name, Sex, Age, SibSp, Parch, Fare, Embarked, etc.

# Techniques Used
Summary Statistics (.describe())
Null value handling (.isnull().sum())
Outlier detection (IQR method, Boxplots)
Countplots, Histograms, KDE plots
Correlation matrix and Heatmaps
Pairplots to compare numerical features with Survived

# Sample Visualizations
Countplot: Distribution of survivors
Boxplot: Age distribution by survival status
Heatmap: Feature correlations
Pairplot: Pairwise relationships in dataset
