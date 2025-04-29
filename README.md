# TASK-4-Logistic-Regression
Binary Classifier using Logistic Regression-Breast Cancer Wisconsin Dataset
📄 Dataset Overview
This dataset consists of 569 samples with 32 features (plus 1 target column: diagnosis). Each sample describes characteristics of a cell nucleus present in a digitized image of a breast mass. The goal is to classify tumors as malignant (M) or benign (B).

Source file:

bash
Copy
Edit
/kaggle/input/data.csv
📊 What This Notebook Does
Imports libraries: pandas, numpy, matplotlib, sklearn, and others.

Loads and previews the data.

Performs basic data cleaning:

Drops irrelevant columns like id and Unnamed: 32.

Encodes categorical diagnosis labels.

Visualizes the data:

Column distributions

Correlation heatmap

Scatter and density plots

Prepares data for modeling:

Standardizes features using StandardScaler.

Trains a baseline machine learning model:

Uses RandomForestClassifier for classification.

Evaluates performance with classification report.

# Data Cleaning
Removed unused columns (id, Unnamed: 32)

Encoded diagnosis: 'M' → 1, 'B' → 0

# ML Modeling
A basic RandomForestClassifier is trained on the standardized dataset to predict cancer diagnosis.

# How to Use
To reproduce this notebook or extend the analysis:

Fork or edit this notebook on Kaggle.

Run all cells to see data exploration and model results.

Modify the modeling section to try other algorithms or tune hyperparameters.

# Future Improvements
Hyperparameter tuning (e.g., GridSearchCV)

Try other models like SVM, Logistic Regression, XGBoost

Add cross-validation and ROC/AUC plots

Feature importance visualization
