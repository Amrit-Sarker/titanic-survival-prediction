# 🚢 Titanic - Machine Learning from Disaster | Kaggle Best Score: 0.78229


## 🧠 Project Overview

This project implements a **supervised machine learning pipeline** to predict passenger survival in the Titanic disaster using the Kaggle Titanic dataset.

The objective is to build and compare different machine learning models and understand the factors influencing passenger survival.

This work follows a complete data science workflow:
**data preprocessing → feature engineering → model training → evaluation → model comparison → submission**

---

## 🎯 Problem Definition

The Titanic disaster provides a classic binary classification problem:

> Predict whether a passenger survived or not based on available features.

Formally:

* Target variable: `Survived ∈ {0, 1}`
* Task type: Binary classification

---

## 📊 Dataset

Source: Kaggle Titanic Competition

Key attributes:

* Passenger class (`Pclass`)
* Sex
* Age
* SibSp (siblings/spouses aboard)
* Parch (parents/children aboard)
* Fare
* Embarked (port of embarkation)

Missing values were carefully handled using statistically sound imputation strategies.

---

## ⚙️ Methodology

### 🔹 Data Preprocessing

* Missing value imputation (Age, Embarked)
* Encoding categorical variables
* Feature selection and preprocessing
* Preparation of training and test datasets

### 🔹 Models

Several machine learning models were trained and evaluated:

* **Logistic Regression**
* **Random Forest**
* **XGBoost**
* **LightGBM**

Logistic Regression was used as an interpretable baseline, while tree-based ensemble and gradient boosting models were tested to improve predictive performance.

### 🔹 Training Strategy

* Train-validation split
* Models trained on the processed feature matrix
* Evaluation using accuracy
* Final models submitted to the Kaggle Titanic competition

---

## 📈 Results

The original Logistic Regression baseline achieved a **Kaggle Public Score of 0.77033**.

After experimenting with additional machine learning models, the best-performing model so far is **LightGBM**, achieving a **Kaggle Public Score of 0.78229**.

| Model               | Kaggle Public Score |
| ------------------- | ------------------: |
| Logistic Regression |             0.77033 |
| **LightGBM**        |      **0.78229** 🏆 |

### 🏆 Best Model

**LightGBM — Kaggle Public Score: 0.78229**

This represents an improvement of **0.01196 points** over the original Logistic Regression baseline.

---

## 🔍 Key Insights

* Gender is one of the most influential predictors of survival.
* Proper preprocessing and feature representation have a significant impact on model performance.
* Tree-based ensemble and boosting models can improve upon the Logistic Regression baseline.
* Among the models submitted so far, **LightGBM achieved the highest Kaggle score**.

---

## 🛠️ Tech Stack

* Python 🐍
* Pandas
* NumPy
* Scikit-learn
* Random Forest
* XGBoost
* LightGBM
* Jupyter Notebook

---

## 🚀 Future Improvements

* Feature engineering (Title extraction, Family size, Age bins)
* Hyperparameter tuning
* Cross-validation for robustness
* Further optimization of LightGBM, XGBoost, and Random Forest
* Model ensemble / stacking
* Additional feature selection and interaction features

---

## 🏁 Conclusion

This project demonstrates how different machine learning approaches can be applied to a classic binary classification problem.

Starting with a **Logistic Regression baseline of 0.77033**, additional ensemble and boosting models were explored. The current best result is achieved by **LightGBM with a Kaggle Public Score of 0.78229**.

The project emphasizes the importance of data preprocessing, model selection, and systematic experimentation in improving machine learning performance.

---

## 👨‍💻 Author

**Amrit Sarker**
Applied Statistics and Data Science,
University of Dhaka
