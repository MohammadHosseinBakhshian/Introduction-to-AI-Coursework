# 🧠 Introduction to Artificial Intelligence (Coursework & Final Project)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)

This repository contains the complete set of assignments and the final project for the **Introduction to Artificial Intelligence** course. All implementations are provided as Jupyter Notebooks.

---

## 📌 Table of Contents

- [Assignment 1: Regression, Perceptron, and Optimization](#-assignment-1-regression-perceptron-and-optimization)
- [Assignment 2: Deep Neural Networks](#-assignment-2-neural-networks)
- [Assignment 3: Fuzzy Logic Systems](#-assignment-3-fuzzy-logic-systems)
- [Final Project: Bank Customer Churn Prediction](#-final-project-bank-customer-churn-prediction)

---

## 📘 Assignment 1: Regression, Perceptron, and Optimization
📁 `HW1_Regression_Perceptron/`

This section focuses on the fundamental concepts of machine learning and optimization mathematics:
* **Linear Regression and Least Squares:** Implementation and evaluation of regression models.
* **Perceptron Algorithm:** Analysis of linear separability of data and training of single-layer models.
* **Model Evaluation:** Calculation and analysis of the **Confusion Matrix**, Accuracy, Precision, and Recall.
* **Optimization:** Implementation of basic optimization algorithms (Gradient Descent).

---

## 📙 Assignment 2: Deep Neural Networks
📁 `HW2_Neural_Networks/`

In this assignment, more advanced models based on neural networks and deep learning were implemented:
* **MLP Architecture Design:** Construction of multilayer neural networks.
* **Data Preprocessing:** Preparation, normalization, and reshaping of data (including MNIST).
* **Weight Initialization and Optimizers:** Investigation of the impact of different initializers (e.g., Glorot/Random) and loss functions.
* **Prediction Analysis:** Plotting training curves and evaluating results on test data.

---

## 📗 Assignment 3: Fuzzy Logic Systems
📁 `HW3_Fuzzy_Logic/`

Investigation and implementation of decision-making systems based on fuzzy logic:
* **Membership Functions:** Design of fuzzy functions for input and output variables.
* **Fuzzy Rule Base:** Definition of fuzzy inference (Mamdani / Sugeno).
* **Fuzzification and Defuzzification:** Extraction of crisp outputs from the fuzzy system.

---

## 🎓 Final Project: Bank Customer Churn Prediction
📁 `Project_Final/`

The core capstone project focuses on predicting customer churn in the banking sector using machine learning and deep learning models. Customer churn prediction enables financial institutions to identify high-risk customers, understand retention drivers, and execute targeted business strategies to minimize revenue loss.

### 🔑 Key Methodologies & Workflow:
* **Exploratory Data Analysis (EDA):** In-depth statistical analysis and data visualization to uncover patterns between churn rate and parameters such as credit score, balance, geography, age, and product usage.
* **Data Preprocessing & Feature Engineering:** Handling missing values, one-hot encoding categorical variables, standard scaling numerical features, and addressing potential class imbalance issues.
* **Model Building & Evaluation:** Implementation, tuning, and comparison of classification algorithms (e.g., Artificial Neural Networks / Scikit-Learn Classifiers) evaluated across key performance metrics including Accuracy, Precision, Recall, F1-Score, and ROC-AUC.
* **Business Insights:** Interpretation of feature importances and confusion matrices to convert technical predictions into actionable customer retention strategies for business analysts.

### 📄 Deliverables:
* **Project Code (`Project_Notebook.ipynb`):** Complete, fully annotated Jupyter Notebook tracking the end-to-end Machine Learning pipeline.
* **Comprehensive Report (`Report.pdf`):** Formal theoretical write-up detailing problem formulation, experimental setup, model architectures, comparative results, and final conclusions.
* **Presentation Slides (`Presentation.pptx`):** Structured slide deck prepared for oral defense and project demonstration.

---

## 🛠 Requirements and How to Run

To execute the code in this project, the following dependencies are required:

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow scikit-fuzzy
