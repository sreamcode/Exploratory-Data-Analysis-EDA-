Titanic Dataset EDA
This repository contains an Exploratory Data Analysis (EDA) of the Titanic dataset using Python.
Dataset
File: Titanic-Dataset.csv
Columns: PassengerId, Survived, Pclass, Name, Sex, Age, Fare, and more.
Analysis Steps
Load Dataset
Used pandas to read the CSV file.
Summary Statistics
Used .describe() to get basic stats (mean, median, std, etc.).
Visualizations
Created histograms and boxplots for numeric features.
Generated pairplots and a correlation matrix for feature relationships.
Patterns and Anomalies
Explored survival rates by passenger class and sex.
Analyzed Fare and Age distributions to identify outliers.
Key Findings
Higher survival rates in first class and among females.
Survivors often paid higher fares.
Detected some extreme values in Fare and Age.
Libraries
pandas
numpy
matplotlib
seaborn
How to Run
Clone the repository.
Open titanic_eda.ipynb in Jupyter Notebook.
Run the cells step-by-step to follow the analysis.
