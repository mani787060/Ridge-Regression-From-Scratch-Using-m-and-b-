# Ridge Regression From Scratch Using m and b

## 📌 Project Overview

This project demonstrates the implementation of **Ridge Regression (L2 Regularization)** completely from scratch by manually optimizing the **slope (m)** and **intercept (b)** using **Gradient Descent**.

Using the **Diabetes Dataset (`load_diabetes`)**, the notebook explains how the Ridge penalty modifies the learning process by discouraging large coefficient values. The project focuses on understanding the mathematical intuition behind regularization and how it helps improve model generalization.

---

## 🎯 Objectives

* Understand the fundamentals of Ridge Regression
* Implement Ridge Regression from scratch using m and b
* Learn how L2 Regularization affects parameter updates
* Study the role of the regularization parameter (λ)
* Compare Ridge Regression with standard Linear Regression

---

## 📂 Dataset

**Dataset Used:** `load_diabetes`

A built-in regression dataset from Scikit-Learn used to predict disease progression from multiple medical features.

---

## 📖 Concepts Covered

* Linear Regression
* Ridge Regression
* L2 Regularization
* Gradient Descent
* Cost Function
* Parameter Optimization
* Coefficient Shrinkage
* Overfitting Prevention

---

## 🛠️ Libraries Used

* Python
* NumPy
* Pandas
* Matplotlib

---

## ⚙️ Implementation Steps

### Data Preparation

* Load the Diabetes dataset
* Select features and target variables
* Visualize the dataset

### Ridge Loss Function

* Define the Mean Squared Error (MSE)
* Add the L2 Regularization term

### Gradient Calculation

* Compute gradients for slope (m)
* Compute gradients for intercept (b)
* Include regularization penalty in updates

### Parameter Updates

* Update m and b iteratively
* Minimize the Ridge loss function using Gradient Descent

### Visualization

* Plot regression line
* Track loss reduction over iterations
* Analyze coefficient shrinkage

---

## 🔍 Key Observations

* Ridge Regularization reduces the magnitude of model coefficients.
* Large values of λ increase coefficient shrinkage.
* Regularization helps reduce overfitting.
* Gradient Descent successfully learns optimal values of m and b.

---

## ✅ Advantages

* Improves model generalization
* Reduces overfitting
* Provides stable coefficient estimates
* Helps understand regularization mathematically
* Builds strong intuition for optimization techniques

---

## 💻 Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
  
---

## 🏁 Conclusion

Ridge Regression extends Linear Regression by adding an L2 penalty term that discourages large coefficient values. By implementing the algorithm from scratch using m and b, this project provides a clear understanding of how regularization improves model performance and prevents overfitting.


