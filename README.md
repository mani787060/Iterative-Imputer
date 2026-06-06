# Iterative Imputer in Machine Learning

## Overview

This project demonstrates how to handle missing values using **Iterative Imputation**, a model-based imputation technique that predicts missing values by learning relationships between features.

Unlike Mean or Median Imputation, Iterative Imputer uses other available features to estimate missing values, helping preserve the underlying data patterns.

---

## Key Concepts Covered

* Missing Value Handling
* Iterative Imputation
* Regression-Based Imputation
* Feature Relationship Preservation
* Comparison with Traditional Imputation Methods
* Data Distribution Analysis

---

## Dataset

* **50_Startups.csv**
* Contains startup-related features used to demonstrate missing value treatment using Iterative Imputer.

---

## Libraries Used

* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn

---

## Implementation Steps

### 1. Data Loading

* Import the dataset
* Explore missing values

### 2. Data Analysis

* Identify features containing null values
* Study feature distributions

### 3. Iterative Imputation

* Apply `IterativeImputer`
* Predict missing values using other features

### 4. Evaluation

* Compare distributions before and after imputation
* Analyze feature relationships

---

## Key Observations

* Iterative Imputer preserves feature correlations better than simple statistical methods.
* Missing values are estimated using information from other variables.
* Often provides more realistic imputations than Mean or Median Imputation.

---

## Advantages

* Preserves data relationships
* Produces more accurate estimates
* Useful for numerical datasets
* Reduces information loss

---

## Conclusion

Iterative Imputation is an advanced missing value handling technique that uses predictive modeling to estimate missing values. It is particularly useful when features are correlated and can provide better results than traditional imputation methods.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
