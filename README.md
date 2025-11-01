Boston Housing Price Prediction

Michael Tamirat

Dataset
Boston Housing Dataset from UCI Machine Learning Repository

506 samples with 14 features
Target Variable: MEDV 
Primary Feature Used: RM

Data Cleaning & Feature Engineering

Data Loading: Loaded dataset from UCI repository with proper column names
Feature Engineering: Created HOUSE_CONDITION feature from AGE column:

New: AGE ≤ 50
Old: AGE > 50 and ≤ 80
Very Old: AGE > 80


Feature Selection: Used RM (number of rooms) as predictor
Data Split: 80% training, 20% testing 

Model Performance
Linear Regression Results:

R² Score: 0.3708
Mean Squared Error (MSE): 46.1448

Dependencies

pandas
scikit-learn
matplotlib
numpy
