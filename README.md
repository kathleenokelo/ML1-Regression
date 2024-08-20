# ML1-Regression

## WEEK TWO
### Blueberry yield project
This project aims to develop a regression model to predict based on Blueberry Prediction Dataset. Regression analysis is a statistical method for investigating relationships between a dependent variable (target) and one or more independent variables (features). The objective is to create a model that accurately predicts the target variable based on the given features.This project shows work with techniques like linear regression, polynomial regression, ridge regression, lasso regression, and elastic net regression.

## Project Overview
**Objective**: Fit a regression model to predict the target variable using the training data and make predictions on the test data.

## Dataset
The dataset has two components:
- **Training Dataset**: Contains both features and labels.
- **Test Dataset**: Contains features only (no labels).
Make sure that the data preparation steps you apply to the training data are also applied consistently to the test data.

## Data Preparation
Preparing the data is a key step before model fitting. Here are some things to focus on:
- Handle missing values appropriately.
- Encode categorical variables into numerical format if needed.
- Normalize or standardize features.
- Optionally split the training set into training and validation sets for model tuning.
- Engineer new features or transform existing ones to boost model performance.
Ensure these steps are applied to both training and test sets consistently.

## Model Training
Experiment with the different regression models covered this week:
- Tip: Use the Mean Absolute Error (MAE) as your evaluation metric during model training to fine-tune and select the most effective model.

## Submission
Submit a CSV file that includes the test IDs and your model's predictions.

## Evaluation
Your submission will be judged based on the Mean Absolute Error (MAE) between your predictions and the actual values.
