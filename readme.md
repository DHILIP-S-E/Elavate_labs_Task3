  Car Price Prediction
Project Overview
This project builds a Linear Regression model to predict car prices based on different features.

Dataset
Dataset: Car details (e.g., car name, model, engine size, horsepower, etc.)

Format: .csv

Steps Followed
Import Libraries (pandas, numpy, sklearn, matplotlib)

Load the Dataset using pd.read_csv()

Explore the Data: head(), info(), describe()

Handle Missing Values: Checked using isnull().sum()

Data Cleaning:

Dropped missing rows.

Categorical data (like car names) were either encoded or dropped for simplicity.

Feature Selection:

Selected numeric columns like engine size, horsepower, etc.

Train-Test Split:

Used train_test_split (80% train, 20% test).

Model Training:

Used LinearRegression() model from sklearn.

Prediction and Evaluation:

Calculated MAE, MSE, R2 Score.

Visualization:

Plotted Actual vs Predicted prices using a scatter plot.

Libraries Used
pandas

numpy

matplotlib

seaborn

sklearn