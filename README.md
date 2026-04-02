# Machine Learning & Data Analysis Projects

This repository contains a collection of data science projects focusing on statistical hypothesis testing and fundamental machine learning implementations from scratch.

## 📂 Projects Overview

### 1. Wine Quality Analysis using Statistical Inference
**File:** `Project02.ipynb`

An in-depth study of the UCI Machine Learning Repository's Red Wine dataset to determine the relationship between physicochemical properties and wine quality.

* **Objective:** Analyze if alcohol content significantly influences wine quality scores.
* **Methodology:** * Exploratory Data Analysis (EDA) and data visualization.
    * **Hypothesis Testing:** Conducted T-Tests to compare high vs. low alcohol groups.
    * **ANOVA:** Performed Analysis of Variance to check for significant differences across multiple quality categories.
* **Key Results:** Successfully rejected the null hypothesis ($p < 0.05$), proving a statistically significant correlation between alcohol levels and quality ratings.

### 2. Regularized Logistic Regression from Scratch
**File:** `Project01.ipynb`

A "from-scratch" implementation of a Logistic Regression classifier, focusing on the underlying mathematics and optimization techniques.

* **Objective:** Classify data using a custom-built model with L2 Regularization (Ridge) to prevent overfitting.
* **Technical Highlights:**
    * **Mathematical Formulation:** Implementation of the Sigmoid function and Log-Loss cost function.
    * **Optimization:** Used Gradient Descent for weight updates.
    * **Regularization:** Integrated L2 penalty to improve model generalization.
* **Performance:** Achieved an accuracy of ~90% on the test set, with balanced precision and recall.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** NumPy, Pandas, Matplotlib, Seaborn, SciPy (for statistical tests)
* **Environment:** Jupyter Notebook / Google Colab

