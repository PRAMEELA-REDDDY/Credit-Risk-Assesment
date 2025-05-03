# Credit Risk Assessment Model

This repository contains a machine learning-based model to assess the credit risk of individuals or organizations. The model uses **Logistic Regression** for classification and **Optuna** for hyperparameter tuning to improve performance.

**Live Application**: [Credit Risk Assessment App](https://creditriskassessment.streamlit.app/)

## Table of Contents

- [Introduction](#introduction)
- [Objective](#objective)
- [Data](#data)
- [Technologies Used](#technologies-used)
- [Model](#model)
- [Installation](#installation)
- [Usage](#usage)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Credit risk assessment is essential for financial institutions to evaluate the risk associated with lending money to borrowers. This project leverages machine learning techniques, specifically **Logistic Regression** and **Optuna**, to predict the likelihood of credit default based on various financial and personal attributes of the borrower.

## Objective

The primary objective of this project is to build a robust credit risk assessment model that can help predict whether a borrower will default on their loan or not. The model uses the features provided in the dataset to make this prediction. 

## Data

The dataset used for this project contains financial information of individuals, such as income, loan history, age, and credit score. It includes the following features:

- **Age**: Age of the borrower
- **Income**: Monthly or yearly income of the borrower
- **Loan Amount**: The amount of the loan applied for
- **Credit Score**: Borrower's credit score
- **Loan History**: Borrower's past loan repayment status
- **Employment Status**: Borrower's current employment status

The target variable is the **Default** column, which indicates whether the borrower defaulted on the loan.

## Technologies Used

- **Python**: Programming language used for model development.
- **pandas**: Data manipulation and analysis.
- **numpy**: Numerical computations.
- **scikit-learn**: Machine learning library for model training and evaluation.
- **logistic regression**: Used for binary classification in credit risk prediction.
- **optuna**: Hyperparameter optimization framework used to tune Logistic Regression.
- **matplotlib** / **seaborn**: Data visualization tools for understanding patterns in the data.
- **Jupyter Notebook**: For running code and visualizations.

## Model

The credit risk model uses the following steps:

1. **Data Preprocessing**:
   - Data cleaning and handling missing values.
   - Feature encoding (for categorical data).
   - Feature scaling to normalize numeric values.

2. **Model Selection**:
   - **Logistic Regression** is used to classify the borrowers as "High Risk" or "Low Risk."

3. **Hyperparameter Tuning with Optuna**:
   - **Optuna** is used for hyperparameter optimization of the Logistic Regression model to enhance performance. Key hyperparameters like `C`, `solver`, and `max_iter` are tuned.

4. **Model Evaluation**:
   - The model is evaluated using common metrics such as accuracy, precision, recall, and F1-score.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/PRAMEELA-REDDDY/Credit-Risk-Assesment.git
   cd Credit-Risk-Assesment
   
2. Install the required dependencies:

   pip install -r requirements.txt

