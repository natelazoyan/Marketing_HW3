# Survival Analysis Simulation

## Overview

This Python code conducts a comprehensive Survival Analysis on Telco customer data, aiming to understand and model churn risk. The analysis involves building Accelerated Failure Time (AFT) models with various distributions, comparing their performance, visualizing survival curves, calculating Customer Lifetime Value (CLV), and exploring different customer segments.

## Dataset

The dataset (telco.csv) includes subscriber information such as region, tenure, age, marital status, income, education level, and churn status.

## Libraries Used

- `pandas`: Data manipulation and analysis.
- `numpy`: Used for numerical operations.
- `matplotlib.pyplot` and `seaborn`:  Data visualization.
- `lifelines`: Survival analysis library.


## Usage

1. Ensure the required libraries are installed in your Python environment.
2. Load the Telco dataset using pd.read_csv('telco.csv').
3. Explore and preprocess the data, including handling categorical variables and ensuring proper data types.
3. Build Accelerated Failure Time (AFT) models with available distributions using lifelines.
4. Compare the models and visualize survival curves using matplotlib and seaborn.
5. Interpret coefficients, identify valuable customer segments, and calculate Customer Lifetime Value (CLV).
6. Explore CLV within different segments to understand the factors affecting churn risk.
7. Write a short report summarizing findings and proposing retention strategies.

## Contribuors

Natela Azoyan
