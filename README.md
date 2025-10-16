# Diabetes Analysis & Prediction Project Summary (Code R)
This project focuses on analyzing influencing factors and building a predictive model for diabetes risk based on health and demographic data.

## 1. Impact Analysis
**Objective:** Analyze the effects of health conditions, diseases, quality of life, and demographic factors on diabetes prevalence.

**Methodology:**

Applied A/B Testing using:
- Permutation method for binary variables
- Chi-square method for qualitative variables

## 2. Predictive Modeling
**Data Preprocessing:**

The dataset was cleaned, outliers were handled, data imbalance was addressed using **under-sampling**, **over-sampling**, and **SMOTE**, and highly correlated variables were treated.

**Tested Models:**

Built diabetes risk prediction models using the following algorithms:
- Naive Bayes
- Linear Discriminant Analysis (LDA)
- Quadratic Discriminant Analysis (QDA)
- Logistic Regression

## 3. Key Result
**Best Model:**

The **Logistic Regression model** combined with **SMOTE** achieved the highest predictive performance.

**Accuracy:**

The best model reached an accuracy of **52.1%** in correctly predicting diabetes risk.
