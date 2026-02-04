# Lab 2: Machine Learning Workflow & Data Exploration

## Dataset Description
For this lab, I am working with a two-part dataset focused on smartphone battery performance:

smartphone_battery_features.csv: Contains the independent variables (technical specifications) of various smartphone batteries.

smartphone_battery_targets.csv: Contains the dependent variables or "labels" we want to predict.

## Machine Learning Problem
The goal of this project is to perform a Regression analysis. Specifically, I want to determine if a machine learning model can accurately predict battery capacity or longevity (the targets) based on the hardware specifications (the features) provided in the dataset.

## Data Exploration Results
Using the Pandas library I performed the following initial steps:

Shape: Verified the number of rows and columns to ensure the features and targets align correctly.

Preview: Used .head() to inspect the first few rows for any obvious data entry errors.

Data Types: Used .dtypes() to confirm that the numerical data is stored correctly as integers or floats, and categorical data is identified.

