# Loan Approval Analysis 

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a loan approval dataset to understand the key factors that influence loan approval decisions. The analysis focuses on identifying patterns in applicant characteristics such as income, age, education, employment experience, loan intent, and previous loan defaults.
The goal of this project is to gain insights into what factors may impact loan approval outcomes.

## Dataset Description

The dataset contains information about loan applicants and their loan application details.
Main columns used in the analysis include:

- Gender

- Age

- Education

- Employment Experience

- Home Ownership

- Income

- Loan Amount

- Loan Intent

- Previous Loan Defaults

- Credit History Length

- Loan Status (Approved / Rejected)

## Tools and Libraries Used

- Python

- Pandas

- NumPy

- Matplotlib

- Seaborn

- Jupyter Notebook

## Project Workflow

1. Data Loading

The dataset was loaded using Pandas and the basic structure of the dataset was explored.

2. Data Cleaning

The following data cleaning steps were performed:

Renamed certain columns for clarity

Checked for missing values

Verified data types

Reviewed categorical variables

3. Exploratory Data Analysis (EDA)

EDA was conducted to understand the distribution and relationships between different variables.
This included:

Distribution analysis of numerical variables

Groupby analysis for categorical variables

Summary statistics and aggregations

4. Data Visualization

Several visualizations were created to better understand loan approval trends.
Charts included:

Overall Loan Approval vs Rejection

Loan Approval Distribution by Gender

Loan Approval Rate by Age Group

Loan Approval Rate by Income-to-Loan Ratio

Loan Approval Rate by Education Level

Loan Approval Rate by Employment Experience

Loan Approval Rate by Home Ownership

Loan Approval Rate by Previous Loan Defaults

Loan Approval Rate by Loan Intent

Average Loan Amount by Loan Intent

## Key Insights

- Applicants with previous loan defaults have significantly lower approval rates.

- Applicants with higher income relative to loan amount tend to have higher chances of approval.

- Loan intent categories show different approval trends.

- Employment experience and education level also influence approval outcomes.

## Project Files

- Loan_Approval_Analysis.ipynb – Jupyter Notebook containing the full analysis

- dataset.csv – Source dataset

- charts/ – Saved visualizations generated during the analysis

## Author

Avinash Reddy
This project was created as part of my Data Analyst learning journey focusing on Python-based data analysis and visualization.