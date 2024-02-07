# loan-prediction
An experimental defined full scaled project on loan prediction using SVM and RandomForest using GridSearch
# Loan Prediction Approval Model

This repository contains the code and resources for building a loan prediction approval model using Support Vector Machine (SVM) and Random Forest (RF) algorithms. The aim of this project is to predict whether a loan application will be approved or not based on various features associated with the applicant.

## Introduction

Loan approval prediction is a critical task in the banking industry, as it helps banks minimize the risk of default and make informed lending decisions. This project explores the use of machine learning algorithms to automate the loan approval process.

## Features

- Thorough data visualization using seaborn library, including count plots, swarm plots, and strip plots, to understand the relationships between dependent and independent variables.
- Data reduction techniques to handle redundant or irrelevant features.
- Feature engineering tailored for SVM and RF models to enhance predictive performance.
- Min-max scaling of features for better convergence and interpretability.
- Train-test split ratio of 8:2 to ensure sufficient data for model training and testing while avoiding data leakage.
- Implementation of Grid Search CV for hyperparameter tuning to optimize model performance.
- Cross-validation to prevent overfitting and improve generalization.
- Evaluation metrics include ROC-AUC score, confusion matrix, and classification report.
- Achieved 94% and 98% accuracy for SVM and RF models, respectively.



## Usage

1. Clone the repository:

```bash
git clone https://github.com/udit-rawat/loan-prediction-model.git
