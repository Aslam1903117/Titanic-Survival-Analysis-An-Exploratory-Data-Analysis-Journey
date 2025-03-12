# Titanic Survival Analysis: An Exploratory Data Analysis Journey

This project conducts an Exploratory Data Analysis (EDA) on the Titanic dataset to understand the factors influencing passenger survival. The analysis includes data cleaning, feature engineering, parameter estimation, and hypothesis testing.

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Exploratory Data Analysis](#exploratory-data-analysis)
4. [Feature Engineering](#feature-engineering)
5. [Parameter Estimation](#parameter-estimation)
6. [Inference and Hypothesis Testing](#inference-and-hypothesis-testing)
7. [Conclusions](#conclusions)
8. [Next Steps](#next-steps)
9. [Repository Structure](#repository-structure)
10. [How to Run](#how-to-run)
11. [Acknowledgments](#acknowledgments)

## Introduction

The Titanic dataset is a classic dataset used in data science to predict passenger survival based on various features. This project aims to explore the dataset thoroughly, identify patterns, and test hypotheses about the factors that influenced survival on the Titanic.

## Dataset

The dataset used in this project is the Titanic dataset from Kaggle. It contains information about passengers, including their age, sex, class, fare, and whether they survived the disaster.

- **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
- **Number of Rows**: 891
- **Number of Columns**: 12

## Exploratory Data Analysis

### Data Cleaning
- Handled missing values in 'Age', 'Cabin', and 'Embarked'.
- Converted relevant columns to appropriate data types.
- Identified and handled outliers in the 'Fare' variable.

### Descriptive Statistics
- Calculated basic statistics for each feature.
- Analyzed the overall survival rate.

### Visualizations
- Created histograms, bar plots, box plots, and correlation matrices to understand the distribution of variables and their relationships.

## Feature Engineering

- Created new features such as 'FamilySize', 'IsAlone', 'Title', 'AgeGroup', and 'FarePerPerson'.
- Applied log transformations to 'Fare' and 'FarePerPerson' to handle skewness.
- Encoded categorical variables using one-hot encoding.

## Parameter Estimation

- Used logistic regression to estimate the impact of features on survival.
- Examined the coefficients to understand the influence of each feature.

## Inference and Hypothesis Testing

- Formulated and tested several hypotheses about factors affecting survival:
  - Passengers in first class had a higher survival rate than those in third class.
  - Women had a higher survival rate than men.
  - Passengers who embarked at Cherbourg had a higher survival rate than those who embarked at other ports.
  - Passengers with larger families had a lower survival rate than those traveling alone.
- Conducted chi-square tests and calculated confidence intervals for the logistic regression coefficients.

## Conclusions

- Identified key factors influencing survival on the Titanic, including passenger class, sex, and family size.
- Found significant differences in survival rates based on the hypotheses tested.
- Gained insights into the relationships between various features and survival.

## Next Steps

- Further refine the model by exploring additional features or more advanced modeling techniques.
- Conduct more detailed analyses on specific subgroups of passengers.
- Explore the impact of interactions between features on survival.

## Repository Structure
