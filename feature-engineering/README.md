# Feature Engineering

This folder contains practical implementations of feature engineering
techniques commonly used in real-world Machine Learning workflows to
prepare clean and balanced datasets before model training.

---

## 📌 Topics Covered

### 🔹 Handling Missing Values
- Identifying missing data
- Techniques applied:
  - Mean imputation
  - Median imputation
  - Mode imputation
  - Dropping rows with missing values
  - Dropping columns with excessive missing data
 
---

### 🔹 Handling Imbalanced Datasets
- Upsampling minority class using:
  - `resample` (sklearn)
- Downsampling majority class using:
  - `resample`
- Synthetic data generation using:
  - SMOTE (Synthetic Minority Over-sampling Technique)

---

### 🔹 Handling Outliers
- Visualizing outliers using:
  - Box plots
- Detecting outliers using:
  - Z-score method
  - Interquartile Range (IQR)
- Treating outliers by:
  - Removing extreme values

---

### 🔹 Encoding Categorical Data
- Nominal Encoding:
  - One-Hot Encoding (OHE)
- Label Encoding
- Ordinal Encoding
- Target Guided Ordinal Encoding

---

## 🛠 Tools & Libraries Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib / Seaborn

---

## 🎯 Goal
To transform raw, unstructured data into clean, balanced,
and model-ready datasets by applying practical feature
engineering techniques before training Machine Learning models.
