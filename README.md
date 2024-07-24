# Credit Risk Classification

## Overview

This notebook demonstrates the application of logistic regression to classify credit risk. The goal is to predict loan status as either healthy or high-risk based on historical lending data.

## File Structure
* credit_risk_classification.ipynb: The main notebook containing the implementation of logistic regression for credit risk classification.
* lending_data.csv: Dataset used for training and evaluating the model.
* report.md: A separate file providing detailed analysis and insights from the model results.

## Key Steps

### Data Preparation

1. Load the dataset from the Resources folder.
2. Separate the target variable (loan_status) from the feature set.
3. Split the data into training and testing sets.

### Model Training

1. Train a logistic regression model on the training data.
2. Make predictions on the test data.

### Model Evaluation

1. Evaluate the model using a confusion matrix and classification report.

## Usage
- Ensure the required libraries are installed. You may need numpy, pandas, scikit-learn, and other dependencies.
- Place the lending_data.csv file in the Resources folder.
- Run the notebook to perform data loading, model training, and evaluation.

## Results
The notebook provides insights into the performance of the logistic regression model, including precision, recall, and F1 scores for predicting healthy and high-risk loans.

### Additional Resources
For a detailed analysis and interpretation of the results, refer to the report.md file in this folder.
