# 🩺 Liver Cirrhosis Survival Prediction

A machine learning project that predicts the survival status of liver cirrhosis patients using clinical and laboratory data. The project explores multiple supervised learning algorithms, data preprocessing techniques, hyperparameter optimisation, and ensemble learning methods to improve predictive performance.

---

## Overview

Liver cirrhosis is a chronic liver disease where early prediction of patient outcomes can assist clinicians in making informed treatment decisions.

This project develops and evaluates multiple machine learning models for predicting patient survival status using demographic, clinical, and biochemical attributes.

The workflow includes:

- Data preprocessing
- Missing value handling
- Feature encoding
- Class imbalance handling
- Model training
- Hyperparameter tuning
- Ensemble learning
- Model evaluation

---

## Dataset

The dataset contains clinical information collected from liver cirrhosis patients.

Features include:

- Age
- Sex
- Drug Type
- Bilirubin
- Cholesterol
- Albumin
- Copper
- Platelets
- Prothrombin
- Stage
- Ascites
- Hepatomegaly
- Spiders
- Edema
- SGOT
- Triglycerides

Target Variable:

- Patient Survival Status

---

## Project Pipeline

### 1. Data Preprocessing

- Train/Test split
- Missing value detection
- Median imputation for skewed numerical features
- Label Encoding for categorical variables

---

### 2. Exploratory Data Analysis

- Distribution analysis
- Feature correlation
- Class distribution analysis
- Missing value analysis

---

### 3. Handling Class Imbalance

The dataset exhibited significant class imbalance.

To address this issue:

- SMOTE (Synthetic Minority Over-sampling Technique) was applied to generate synthetic samples for minority classes.

---

### 4. Machine Learning Models

The following classifiers were implemented:

- Logistic Regression
- Random Forest
- Gradient Boosting

---

### 5. Hyperparameter Optimisation

GridSearchCV was used to identify the optimal hyperparameters for each model.

Examples include:

- Logistic Regression (Regularisation Strength)
- Random Forest (Tree Depth, Number of Estimators)
- Gradient Boosting (Learning Rate, Depth, Number of Estimators)

---

### 6. Ensemble Learning

To further improve model performance, two ensemble techniques were explored:

- AdaBoost
- Bagging

---

### 7. Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Cross Validation

The Random Forest model produced the strongest overall performance across the majority of evaluation metrics.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Matplotlib
- Seaborn

---

## Repository Structure

```
├── dataset/
├── notebooks/
├── models/
├── reports/
├── images/
├── requirements.txt
└── README.md
```

---

## Future Improvements

Potential enhancements include:

- XGBoost and LightGBM implementation
- SHAP explainability analysis
- Feature selection techniques
- Automated ML pipelines
- Model deployment using FastAPI
- Interactive prediction dashboard using Streamlit

---

## Learning Outcomes

This project demonstrates practical experience with:

- Data preprocessing
- Missing value treatment
- Feature engineering
- Handling imbalanced datasets
- Supervised machine learning
- Hyperparameter tuning
- Ensemble learning
- Model evaluation and comparison

---

## Author

**Mustafa Tariq**

GitHub: https://github.com/mustafaT96
