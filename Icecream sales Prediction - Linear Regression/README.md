Ice Cream Sales Prediction
This repository contains a Jupyter Notebook that demonstrates how to build a linear regression model to predict ice cream sales revenue based on temperature. The notebook includes data preprocessing, exploratory analysis, model training, evaluation, and visualization.

Features
Predicts sales revenue based on temperature using a linear regression model.
Interactive and easy-to-follow Jupyter Notebook.
Visualizations to understand model performance and data trends.
Model evaluation using:
Mean Squared Error (MSE)
Mean Absolute Error (MAE)
R-squared (R²)
Model persistence with joblib.

Dataset
The dataset, IceCreamData.csv, includes the following columns:

Temperature: The temperature recorded (independent variable).
Revenue: Ice cream sales revenue (dependent variable).

Notebook Contents
Data Exploration:
Check for missing values and generate summary statistics.
Model Training:
Train a linear regression model using scikit-learn.
Model Evaluation:
Calculate metrics such as R², MSE, and MAE.
Cross-Validation:
Perform cross-validation to ensure model consistency.
Visualization:
Generate scatter plots and residual plots for diagnostics.
Model Persistence:
Save the trained model using joblib.

Dependencies
Python 3.7+
pandas
numpy
matplotlib
seaborn
scikit-learn
joblib
Jupyter Notebook
