# 🏠 House Price Prediction Model

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)](https://www.python.org/downloads/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0%2B-orange.svg)](https://scikit-learn.org/stable/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This is a machine learning project that predicts house prices using a regression model. The goal is to create a model that can accurately estimate the price of a house based on its features using the classic Boston Housing Dataset.

---

## 🚀 Features

* **Data Preprocessing:** Cleans and scales the dataset for optimal model performance.
* **Model Training:** Implements a regression model to learn from the data.
* **Performance Evaluation:** Uses **R-squared ($R^2$)** and **Mean Absolute Error (MAE)** to measure model accuracy.
* **Data Visualization:** Includes (or could include) plots from Matplotlib to visualize data distributions and results.

---

## 🛠️ Technologies Used

This project is built using the following technologies:

* **Python:** The core programming language.
* **Scikit-learn:** For machine learning models and metrics.
* **Pandas:** For data manipulation and analysis.
* **NumPy:** For numerical operations.
* **Matplotlib:** For data visualization.
* **Jupyter Notebook / Google Colab:** For model development and experimentation.

---

## 📊 Dataset: Boston Housing

This model was trained on the **Boston Housing Dataset**. This dataset contains 506 instances and 13 input features, with the target variable being the median value of homes.

### Features
* `CRIM`: Per capita crime rate by town
* `ZN`: Proportion of residential land zoned for lots over 25,000 sq.ft.
* `INDUS`: Proportion of non-retail business acres per town
* `CHAS`: Charles River dummy variable (1 if tract bounds river; 0 otherwise)
* `NOX`: Nitric oxides concentration (parts per 10 million)
* `RM`: Average number of rooms per dwelling
* `AGE`: Proportion of owner-occupied units built prior to 1940
* `DIS`: Weighted distances to five Boston employment centres
* `RAD`: Index of accessibility to radial highways
* `TAX`: Full-value property-tax rate per $10,000
* `PTRATIO`: Pupil-teacher ratio by town
* `B`: $1000(B_k - 0.63)^2$ where $B_k$ is the proportion of Black residents by town
* `LSTAT`: % lower status of the population

### Target Variable
* `MEDV`: Median value of owner-occupied homes in $1000s

---

## 🤖 Model Performance

A **[INSERT YOUR MODEL NAME, e.g., XGBoost Regressor, Linear Regression]** was trained to build the prediction model. The model's performance was evaluated using R-squared ($R^2$) and Mean Absolute Error (MAE).

### Results

| Data Split | R-squared ($R^2$) | Mean Absolute Error (MAE) |
| :--- | :---: | :---: |
| **Training Data** | 0.999 (99.9%) | 0.009 |
| **Test Data** | 0.905 (90.5%) | 2.07 |

### 📈 Analysis

* The model achieves a **strong $R^2$ score of 90.5%** on the unseen test data, indicating it generalizes well and can make accurate predictions.
* The near-perfect $R^2$ score (0.999) on the training data, compared to the 90.5% on the test data, strongly suggests that the model is **overfitting**. This means it has learned the training data's noise rather than just the underlying patterns.
* **Future Improvements:** To combat this, one could apply regularization (like L1/L2), use a simpler model, or gather more data.

---
