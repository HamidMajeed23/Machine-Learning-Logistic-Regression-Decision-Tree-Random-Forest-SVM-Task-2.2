# 📊 Classification Models Evaluation & Benchmark

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?logo=scikit-learn&logoColor=white)
![uv](https://img.shields.io/badge/uv-Fast_Python_Packaging-purple)

This repository contains the full solution and analysis for **Question 2.2: Classification Models**. It provides a comprehensive comparative evaluation across four primary machine learning classification algorithms: **Logistic Regression**, **Decision Trees**, **Random Forests**, and **Support Vector Machines (SVM)** on a binary classification dataset.

---

## 📑 Table of Contents
1. [Project Overview](#-project-overview)
2. [Task Breakdown](#-task-breakdown)
3. [Model Comparison Matrix](#-model-comparison-matrix)
4. [Project Structure](#-project-structure)
5. [Installation & Setup](#-installation--setup)
6. [How to Run](#-how-to-run)
7. [Git Commit Commands](#-git-commit-commands)

---

## 🚀 Project Overview

The objective of this assignment is to train, hyperparameter-tune, evaluate, and compare multiple supervised classification algorithms on a binary dataset. The project evaluates performance using multi-metric scoring (Accuracy, Precision, Recall, F1-Score, ROC-AUC) along with training runtime performance.

---

## 🛠 Task Breakdown

### (a) Logistic Regression Classifier
* Built a baseline binary logistic regression classifier using `sklearn.linear_model.LogisticRegression`.
* Computed comprehensive evaluation metrics:
  * **Accuracy:** Overall proportion of correct predictions.
  * **Precision & Recall:** Trade-off analysis for positive class detection.
  * **F1-Score:** Harmonic mean of precision and recall.
  * **ROC-AUC Score:** Area under the Receiver Operating Characteristic curve measuring class separability.

### (b) Decision Tree Classifier & Visualization
* Trained a Decision Tree classifier and extracted the explicit decision rules.
* **Tree Visualization:** Rendered using `plot_tree` / `graphviz`.
* **Conceptual Analysis:**
  * **Maximum Depth (`max_depth`):** Controlled tree depth to prevent overfitting.
  * **Gini Index vs. Information Gain:** Evaluated split criteria and impurity reduction across nodes.

### (c) Random Forest Classifier & Hyperparameter Tuning
* Implemented an ensemble Random Forest classifier using `sklearn.ensemble.RandomForestClassifier`.
* **Experiments:**
  * Varied **Number of Trees (`n_estimators`)**: Tested sensitivity across `[10, 50, 100, 200]`.
  * Varied **Max Depth (`max_depth`)**: Evaluated generalization capacity vs. individual decision tree performance.
* **Comparison:** Demonstrated reduced variance and superior generalization over single Decision Trees.

### (d) Support Vector Machine (SVM) Kernels Comparison
* Built SVM models using `sklearn.svm.SVC` across two distinct kernels:
  * **Linear Kernel:** Evaluated linear boundary separation capability.
  * **RBF (Radial Basis Function) Kernel:** Analyzed non-linear feature space transformation.
* **Comparison:** Assessed performance differences in margin optimization and decision boundary flexibility.

### (e) Model Benchmarking & Final Discussion
* Compiled an empirical summary table comparing model metrics and training execution times.
* Analyzed trade-offs between linear simplicity, tree-based interpretability, ensemble robustness, and non-linear kernel transformations to identify the optimal model.

---

## 📈 Model Comparison Matrix

| Model | Accuracy | Precision | Recall | F1-Score | Training Time (s) |

| **Logistic Regression** | 
| **Decision Tree** | 
| **Random Forest** | 
| **SVM (Linear)** |
| **SVM (RBF)** | 


---

