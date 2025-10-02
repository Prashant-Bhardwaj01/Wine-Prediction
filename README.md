# 🍷 Wine Quality Classification using Logistic Regression

This repository contains a **machine learning project** that predicts the quality of red wine based on its physicochemical properties.  
The dataset used is the **Red Wine Quality dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality).

---

## 📌 Project Overview
The project demonstrates a **binary classification** approach using **Logistic Regression**:

- **Input**: 11 physicochemical properties of wine (e.g., acidity, sugar, pH, alcohol).  
- **Output**: Binary label →  
  - **0** = Bad quality (wine quality ≤ 5)  
  - **1** = Good quality (wine quality ≥ 6)  

---

## 🛠️ Tech Stack
- **Python 3.8+**
- **Pandas** → Data loading & preprocessing  
- **Scikit-learn** → Data splitting, scaling, logistic regression, evaluation  
- **NumPy** → Numerical computations  

---

## ⚙️ Steps Implemented
1. **Load Dataset** – Reads `winequality-red.csv`.  
2. **Preprocessing** – Converts multi-class quality scores into binary labels.  
3. **Split Data** – Train (80%) / Test (20%).  
4. **Feature Scaling** – Standardizes features using `StandardScaler`.  
5. **Model Training** – Logistic Regression classifier.  
6. **Evaluation** – Accuracy score & confusion matrix.  
7. **Prediction** – Supports predicting the quality of a **new wine sample**.

---

## 📂 Repository Structure
-├── winequality-red.csv # Dataset file (UCI Wine Quality - Red)


-├── wine_quality.py # Main Python script


-├── README.md # Project documentation

