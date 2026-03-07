# Support Vector Machine (SVM) Classifier

This project demonstrates how to build a **Support Vector Machine (SVM) Classifier** using Scikit-learn for classification tasks.

---

## 📌 What is SVM?

Support Vector Machine (SVM) is a supervised machine learning algorithm used for **classification and regression problems**.  
It works by finding the **optimal hyperplane** that best separates different classes in the dataset.

---

## 📚 Topics Covered

- Creating dataset using `make_classification`
- Train Test Split
- Training SVM classifier
- Understanding kernel functions
- Model evaluation using performance metrics
- Hyperparameter tuning using GridSearchCV

---

## ⚙️ Technologies Used

- Python
- Scikit-learn
- NumPy
- Pandas
- Matplotlib / Seaborn

---

## 📊 Model Workflow

1. Create dataset using `make_classification`
2. Split dataset into training and testing sets
3. Train model using `SVC`
4. Evaluate performance using metrics
5. Using different kernel value `linear`, `rbf`, `poly`, `sigmoid`
6. Tune hyperparameters using `GridSearchCV`

---

## 📈 Evaluation Metrics

The following metrics were used to evaluate model performance:

- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1 Score

---

## 📦 Libraries Used

```python
from sklearn.datasets import make_classification
from sklearn.svm import SVC
from sklearn.model_selection import train_test_split
from sklearn.model_selection import GridSearchCV
from sklearn.metrics import accuracy_score, classification_report, confusion_matrix
