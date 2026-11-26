# Bicycle Rental Demand Prediction | Supervised Machine Learning

## Project Overview

This project focuses on predicting daily bicycle rental demand using supervised machine learning techniques. It involves analyzing 731 daily observations, identifying factors associated with rental demand, and developing regression models to evaluate their predictive performance.

## Objectives

- Explore and understand the factors associated with bicycle rental demand.
- Perform data preprocessing and exploratory data analysis.
- Conduct statistical testing and feature assessment.
- Develop and compare multiple regression models.
- Identify the best-performing model based on cross-validation and testing results.

## Methodology

### 1. Data Preprocessing
- Inspected and prepared the dataset for analysis.
- Performed data cleaning and preprocessing.
- Prepared relevant features for regression modeling.

### 2. Exploratory Data Analysis (EDA)
- Examined the distribution of bicycle rental demand.
- Explored relationships between demand and relevant factors.
- Identified patterns and trends within the dataset.

### 3. Statistical Testing
- Conducted statistical assessments to examine relationships between variables.
- Evaluated relevant features for regression modeling.

### 4. Data Partitioning
- Prepared chronological training and testing datasets.
- Preserved the temporal order of observations during partitioning.

### 5. Regression Model Development

Developed, tuned, and compared five supervised regression algorithms:

1. Lasso Regression
2. Ridge Regression
3. Elastic Net Regression
4. Decision Tree Regression
5. Random Forest Regression

### 6. Model Evaluation and Selection

Evaluated model performance using cross-validation RMSE and testing metrics.

**Selected Model: Lasso Regression**

Lasso Regression was selected as the final model based on its lowest cross-validation RMSE.

## Key Results

| Evaluation Metric | Result |
|---|---:|
| Daily Observations | 731 |
| Regression Models Compared | 5 |
| Best Model | Lasso Regression |
| Cross-Validation RMSE | 1,089.884 |
| Testing R² | 0.6495 |

The selected Lasso Regression model achieved a testing R² of 0.6495, indicating that it explained approximately 64.95% of the variation in bicycle rental demand within the testing dataset.

## Tools and Libraries

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

## Project Scope

This project covers data preprocessing, exploratory data analysis, statistical testing, regression model development, hyperparameter tuning, model comparison, and final model selection.

## Author

**Ralph Victor Ilarde**  
BS Information Systems – Business Analytics  
West Visayas State University
