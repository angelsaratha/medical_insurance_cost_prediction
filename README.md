# medical_insurance_cost_prediction
Machine learning project to predict medical insurance costs using Scikit-learn.

## Project Overview

This project uses machine learning to predict medical insurance charges based on customer information.

## Objective

The objective is to build a regression model that can predict insurance charges for a new customer.

## Dataset

The dataset contains information about:
- Age
- Sex
- BMI
- Number of children
- Smoking status
- Region
- Insurance charges

The dataset used in this project is not included in this repository.

The dataset can be accessed from the original Kaggle source:

https://www.kaggle.com/datasets/rahulvyasm/medical-insurance-cost-prediction

## Data Preprocessing

The following preprocessing steps were performed:

- Checked missing values
- Checked duplicate records
- Analyzed numerical variables
- Detected outliers using boxplots
- Investigated valid outliers
- Applied log transformation where appropriate
- Converted categorical variables using One-Hot Encoding
- Split the data into training and testing sets

## Machine Learning Models

The following regression models were tested:

- Linear Regression
- Polynomial Regression
- Ridge Regression
- Lasso Regression
- Decision Tree Regression
- Random Forest Regression

## Model Evaluation

Models were compared using:

- MAE
- RMSE
- R² Score

## Final Model

The best-performing model was 'Polynomial Regression' based on its performance on unseen data and cross-validation results.

## Prediction

The final model can predict insurance charges for new customer information.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Seaborn
- Joblib
- Google Colab

## Project Structure

Insurance_Charges_Prediction/
│
├── notebooks/
│   └── Medical_Insurance_Cost_Prediction.ipynb
├── models/
│   └── medical_insurance_model.pkl
├── plots/
│   |── boxplot.png
    |── distplot.png
    |── distplot_charges.png
    |── boxplot_charges_log.png
    └── actual_vs_predicted.png
└── README.md
