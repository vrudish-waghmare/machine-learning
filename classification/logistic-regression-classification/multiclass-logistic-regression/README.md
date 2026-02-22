# Multiclass Classification using Logistic Regression (OvR)

## 📌 Project Overview

This project demonstrates **Multiclass Classification** using Logistic Regression with the One-vs-Rest (OvR) strategy.  
It includes dataset creation, model training, evaluation, and hyperparameter tuning using cross-validation.

---

## 🚀 Topics Covered

- Creating a multiclass dataset using `make_classification`
- Training Logistic Regression using One-vs-Rest (OvR)
- Evaluating performance using classification metrics
- Hyperparameter tuning using GridSearchCV
- Applying Cross-Validation for better generalization

---

## 🛠 Technologies Used

- Python  
- NumPy  
- Pandas  
- Scikit-learn  

---

## 📂 Project Workflow

### 1️⃣ Dataset Creation
- Generated a multiclass dataset using:
  - `make_classification` from `sklearn.datasets`
- Configured multiple classes for classification.

### 2️⃣ Model Training (OvR)
- Used Logistic Regression with:
  - `multi_class='ovr'`
- Trained the model on the training dataset.

### 3️⃣ Performance Evaluation
Evaluated model performance using:
- Accuracy Score  
- Confusion Matrix  
- Precision  
- Recall  
- F1-Score  
- Classification Report  

### 4️⃣ Hyperparameter Tuning
- Applied `GridSearchCV`
- Used cross-validation (cv=5)
- Optimized parameters such as:
  - `C`
  - `penalty`
  - `solver`
- Selected best parameters using `best_params_`
- Improved cross-validation score
