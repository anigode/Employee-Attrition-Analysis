# Employee Attrition Prediction Project

This project focuses on predicting employee attrition using a logistic regression model. The dataset used contains various employee-related information such as age, job role, department, years at the company, monthly income, and more. By training machine learning models, we can predict whether an employee is likely to leave the company (Attrition = Yes) or stay (Attrition = No).

## Table of Contents
- Introduction
- Installation
- Usage
- Data
- Models
- Evaluation
- Libraries
- License

## Introduction
The goal of this project is to help organizations predict employee attrition using machine learning techniques. The dataset includes features such as age, job satisfaction, and monthly income, which are important in understanding why employees leave the company. The project uses logistic regression as the main model to predict employee attrition, and additional data preprocessing is applied to ensure accurate results.

## Installation
To set up the project, clone the repository and install the required libraries. Ensure you have Python installed (preferably version 3.6 or above).

## Usage
Place your dataset CSV file (e.g., greendestination.csv) in the project directory.
Run the employee_attrition_model.py script to execute the analysis.
The cleaned data will be saved as Employee_attrition_dataset.csv in the project directory.

## Data
The project uses a dataset containing information on employee demographics, job roles, and performance. The key features include:
 - Age: Age of the employee
 - BusinessTravel: Frequency of business travel
 - Department: Employee’s department (e.g., Sales, Research)
 - JobRole: The role the employee performs
 - MonthlyIncome: The employee's monthly salary
 - Attrition: The target variable indicating whether the employee left (Yes) or stayed (No)
- The script performs the following data preprocessing steps:
 - Checks for missing values and zero values
 - Converts categorical variables using one-hot encoding
 - Normalizes numerical data

## Models
The following machine learning models are implemented in this project:

- Logistic Regression: A statistical model that uses a logistic function to model a binary dependent variable (Attrition).
Each model is evaluated using accuracy scores and classification reports.

## Evaluation
The performance of the logistic regression model is evaluated based on:
- Accuracy: The ratio of correctly predicted instances to the total instances.
- Classification Report: A detailed report including precision, recall, and F1-score for each class (Attrition = Yes or No).

## Libraries
The project depends on the following Python libraries:
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
