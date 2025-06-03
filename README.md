#  Types of Regression in Machine Learning

This project demonstrates **eight major types of regression algorithms** used in machine learning. Each section includes a concise explanation, synthetic data generation, model training, prediction, and visualization using Python and popular libraries like `scikit-learn` and `matplotlib`.

---

##  Table of Contents

* [Overview](#overview)
* [Types of Regression](#types-of-regression)

  * [1. Linear Regression](#1-linear-regression)
  * [2. Polynomial Regression](#2-polynomial-regression)
  * [3. Stepwise Regression](#3-stepwise-regression)
  * [4. Decision Tree Regression](#4-decision-tree-regression)
  * [5. Random Forest Regression](#5-random-forest-regression)
  * [6. Support Vector Regression (SVR)](#6-support-vector-regression-svr)
  * [7. Ridge Regression](#7-ridge-regression)
  * [8. ElasticNet Regression](#8-elasticnet-regression)
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)

---

##  Overview

Regression analysis is a key statistical technique in machine learning used to model the relationship between a dependent variable and one or more independent variables. This project illustrates:

* Model training on synthetic non-linear data (`y = sin(x) + noise`)
* Visualization of how different regression techniques fit the same dataset
* Insights into model strengths and weaknesses

---

##  Types of Regression

### 1. Linear Regression

Fits a straight line to model the linear relationship between input and output.

### 2. Polynomial Regression

Adds polynomial features to model non-linear relationships.

### 3. Stepwise Regression

Selects the most significant features using statistical tests (`SelectKBest`).

### 4. Decision Tree Regression

Splits the data into regions with decision rules and predicts region-wise averages.

### 5. Random Forest Regression

Ensemble of decision trees to reduce overfitting and improve accuracy.

### 6. Support Vector Regression (SVR)

Uses the support vector machine framework with an epsilon-insensitive tube.

### 7. Ridge Regression

Linear regression with L2 regularization to reduce coefficient variance.

### 8. ElasticNet Regression

Combines L1 (Lasso) and L2 (Ridge) regularization for a balanced model.

---

##  Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/regression-algorithms.git
cd regression-algorithms
```

2. Install dependencies:

```bash
pip install numpy matplotlib scikit-learn
```

---

##  Usage

Run the Python file or open the notebook:

```bash
python regression_examples.py
```

Or open in Jupyter Notebook:

```bash
jupyter notebook
```

Each section will:

* Generate synthetic data
* Train the respective regression model
* Plot the results

---

## ACKNOWLEDGEMENT 
Dr. Agughasi Victor I.

