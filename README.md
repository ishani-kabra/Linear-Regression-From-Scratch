# Linear Regression from Scratch: OLS vs Batch GD vs SGD vs Mini-Batch GD

A machine learning project that implements and compares OLS, Batch Gradient Descent, Stochastic Gradient Descent, and Mini-Batch Gradient Descent for linear regression on the Advertising dataset.

---

## Project Overview

This project explores different methods of training a Linear Regression model and compares their performance.

The following approaches are implemented:

- Scikit-Learn Linear Regression
- Ordinary Least Squares (OLS) from Scratch
- Batch Gradient Descent (BGD)
- Stochastic Gradient Descent (SGD)
- Mini-Batch Gradient Descent (MBGD)

The objective is to understand how each optimization technique learns model parameters and how their performance differs.

---

##  Dataset

**Advertising Dataset**

Features:
- TV Advertising Budget
- Radio Advertising Budget
- Newspaper Advertising Budget

Target:
- Sales

---

##  Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn

---

##  Algorithms Implemented

### 1. Ordinary Least Squares (OLS)

Implemented using the Normal Equation:

β = (XᵀX)⁻¹XᵀY

---

### 2. Batch Gradient Descent

Updates model parameters using the entire training dataset in each iteration.

---

### 3. Stochastic Gradient Descent (SGD)

Updates model parameters using one random training sample at a time.

---

### 4. Mini-Batch Gradient Descent

Updates model parameters using small batches of training samples.

---

##  Evaluation Metrics

Models are evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

---

##  Visualizations

- Actual vs Predicted Scatter Plot
- R² Score Comparison Bar Chart

---

##  Project Structure

Linear-Regression-From-Scratch/
│
├── Advertising.csv
├── linear_regression_comparison.ipynb
├── README.md

--


##  Results

The project compares the performance of:

- OLS
- Batch Gradient Descent
- Stochastic Gradient Descent
- Mini-Batch Gradient Descent

and analyzes their ability to learn model parameters and make predictions.






 Author

Ishani Kabra
