# Heart Disease Prediction using Machine Learning

## Overview

This project predicts the presence of heart disease using patient medical data. Multiple machine learning classification algorithms were implemented and compared to evaluate their performance.

The project demonstrates the complete machine learning workflow including data loading, feature selection, model training, prediction, and evaluation.

---

## Dataset

Heart Disease Dataset

The dataset contains medical information of patients and a target variable indicating the presence or absence of heart disease.

### Target Variable

- 0 → No Heart Disease
- 1 → Heart Disease Present

---

## Features Used

The following features were used for training the models:

- Age
- Sex
- Chest Pain Type (cp)
- Resting Blood Pressure (trestbps)
- Cholesterol (chol)
- Maximum Heart Rate Achieved (thalach)
- ST Depression Induced by Exercise (oldpeak)

---

## Machine Learning Models Implemented

### 1. Logistic Regression

A supervised classification algorithm that predicts the probability of heart disease using the sigmoid function.

**Accuracy:** 75.12%

---

### 2. K-Nearest Neighbors (KNN)

A distance-based classification algorithm that classifies a patient based on the majority class among its nearest neighbors.

**Configuration:**
- K = 3
- StandardScaler used for feature scaling

**Accuracy:** 87.80%

---

### 3. Decision Tree

A tree-based classification algorithm that learns decision rules from the training data.

**Configuration:**
- max_depth = 3

**Accuracy:** 78.54%

---

## Model Comparison

| Model | Accuracy |
|---------|----------|
| Logistic Regression | 75.12% |
| Decision Tree | 78.54% |
| K-Nearest Neighbors (KNN) | 87.80% |

### Best Performing Model

K-Nearest Neighbors (KNN) achieved the highest accuracy on this dataset.

---

## Project Workflow

1. Load Dataset
2. Select Features and Target Variable
3. Split Data into Training and Testing Sets
4. Scale Features (for KNN)
5. Train Model
6. Make Predictions
7. Evaluate Performance
8. Predict on New Patient Data

---

## Evaluation Metrics

The following metrics were used:

- Accuracy Score
- Confusion Matrix

---

## Technologies Used

- Python
- Pandas
- Scikit-Learn
- Jupyter Notebook

---

## Repository Structure

```text
Heart-Disease-Prediction/
│
├── heart.csv
├── heart disease prediction logistic.ipynb
├── heart disease prediction KNN.ipynb
├── decision_tree.ipynb
└── README.md
```

---

## Future Improvements

- Random Forest Classifier
- Hyperparameter Tuning
- Cross Validation
- Feature Importance Analysis
- Model Deployment using Flask or Streamlit

---

## Author

Vignesh Kotrica

Machine Learning Learning Project