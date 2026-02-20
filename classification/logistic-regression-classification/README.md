
# Logistic Regression for Binary Classification with Hyperparameter Tuning

## 📌 Project Overview

This project demonstrates **Binary Classification** using Logistic Regression.  
It covers the complete machine learning workflow including dataset creation, model training, evaluation, and hyperparameter tuning using cross-validation techniques.

---

## 🚀 What This Project Covers

- Creating a synthetic classification dataset using `sklearn.datasets`
- Splitting data into training and test sets
- Training a Logistic Regression model
- Evaluating model performance using classification metrics
- Hyperparameter tuning using:
  - GridSearchCV
  - RandomizedSearchCV
- Applying Cross-Validation to improve model generalization

---

## 🛠 Technologies Used

- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib  

---

## 📂 Project Workflow

### 1️⃣ Dataset Creation
Generated a binary classification dataset using:
- `make_classification` from `sklearn.datasets`

### 2️⃣ Train-Test Split
Used:
- `train_test_split` to divide the dataset into training and testing sets.

### 3️⃣ Model Training
Trained:
- Logistic Regression model from `sklearn.linear_model`

### 4️⃣ Model Evaluation
Evaluated the model using:
- Accuracy Score  
- Confusion Matrix  
- Precision  
- Recall  
- F1-Score  
- Classification Report  

### 5️⃣ Hyperparameter Tuning

#### 🔹 GridSearchCV
- Tested all parameter combinations  
- Used cross-validation  
- Selected best parameters using `best_params_`

#### 🔹 RandomizedSearchCV
- Tested random parameter combinations  
- Faster than GridSearch  
- Efficient for large parameter spaces  

---

## 📊 Results

- Improved model performance after hyperparameter tuning  
- Identified optimal values for:
  - `C`
  - `penalty`
  - `solver`
- Achieved better cross-validation score  


