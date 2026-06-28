# Titanic Dataset - Univariate Exploratory Data Analysis (EDA)

This repository contains a structured approach to performing **Univariate Exploratory Data Analysis (EDA)** on the classic Titanic dataset. The goal is to analyze individual features (variables) independently to understand their distributions, identify patterns, and spot missing data before diving into predictive modeling.

##  Overview

Univariate analysis is the simplest form of analyzing data where we examine one variable at a time. This project breaks down the Titanic variables into two primary categories:
1. **Categorical Data:** Analyzing distributions using Frequency Tables and Count Plots (e.g., `Survived`, `Pclass`, `Sex`, `Embarked`).
2. **Numerical Data:** Analyzing distributions, skewness, and central tendencies using Histograms, Distplots, and Box plots (e.g., `Age`, `Fare`).

##  Tech Stack & Libraries

- **Language:** Python 3
- **Environment:** Jupyter Notebook / JupyterLab
- **Libraries:** 
  - `pandas` (Data manipulation)
  - `seaborn` (Data visualization)
  - `matplotlib` (Plot customizations)

##  Repository Structure

```text
├── EDA_univariate.ipynb   # Main Jupyter Notebook containing the analysis
├── train.csv              # Titanic training dataset
└── README.md              # Project documentation

## Key Insights Addressed
- What is the overall survival rate of the passengers?
- What was the distribution of passengers across different ticket classes (`Pclass`)?
- How does the missing data look for features like `Age` and `Cabin`?

This project is open-source and available under the MIT License.
