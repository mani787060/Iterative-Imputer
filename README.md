# Iterative Imputer in Machine Learning

## 📌 Project Overview

This project demonstrates how to handle missing values using **Iterative Imputation**, an advanced imputation technique that estimates missing values by modeling each feature as a function of the remaining features.

Unlike Mean, Median, or Mode Imputation, Iterative Imputer uses relationships between variables to generate more realistic and consistent values.

---

## 🎯 Objectives

* Understand the concept of Iterative Imputation
* Learn how regression-based imputation works
* Handle missing values using Scikit-Learn's `IterativeImputer`
* Compare Iterative Imputation with traditional imputation methods
* Analyze the impact of imputation on data distribution

---

## 📂 Dataset

**Dataset Used:** `50_Startups.csv`

The dataset contains startup-related features and is used to demonstrate how Iterative Imputer can recover missing numerical values while preserving feature relationships.

---

## 📖 Concepts Covered

* Missing Value Handling
* Iterative Imputation
* Model-Based Imputation
* Feature Correlation
* Data Preprocessing
* Distribution Analysis

---

## 🛠️ Libraries Used

* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn

---

## ⚙️ Implementation Steps

### Data Exploration

* Load and inspect the dataset
* Identify missing values
* Analyze feature distributions

### Applying Iterative Imputer

* Import `IterativeImputer`
* Fit the imputer on the dataset
* Transform missing values using regression-based predictions

### Result Analysis

* Compare data before and after imputation
* Visualize distribution changes
* Observe preservation of feature relationships

---

## 🔍 Key Observations

* Iterative Imputer utilizes information from other features to estimate missing values.
* It generally preserves feature relationships better than Mean or Median Imputation.
* The method produces more realistic imputations when variables are correlated.

---

## ✅ Advantages

* Preserves relationships between features
* Produces more accurate imputations
* Reduces information loss
* Suitable for numerical datasets with correlated features

---

## 🏁 Conclusion

Iterative Imputation is a powerful missing-value handling technique that uses predictive modeling to estimate missing data. It often performs better than traditional statistical methods and helps maintain the overall structure of the dataset, making it valuable for machine learning preprocessing workflows.

---

## 💻 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
