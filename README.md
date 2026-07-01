# Machine Learning Algorithms

A collection of Machine Learning algorithms implemented using **Python**, **Scikit-learn**, and **TensorFlow/Keras**. This repository is organized into **Supervised** and **Unsupervised** learning algorithms with practical implementations on real-world datasets.

---

# Repository Structure

```text
Machine-Learning-Algorithms/
│
├── Supervised/
│   ├── linear_regression.ipynb
│   ├── logistic_regression.ipynb
│   ├── knn.ipynb
│   ├── decision_tree.ipynb
│   ├── random_forest.ipynb
│   ├── ann.ipynb
│   ├── svm.ipynb
│   └── naive_bayes.ipynb
│
├── Unsupervised/
│   └── kmeans.ipynb
│
├── datasets/
│   ├── heart.csv
│   └── students.csv
│
└── README.md
```

---

# Algorithms Implemented

## Supervised Learning

- Linear Regression
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Artificial Neural Network (ANN)
- Support Vector Machine (SVM)
- Naive Bayes

## Unsupervised Learning

- K-Means Clustering

---

# Datasets Used

### Heart Disease Dataset

Used for:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Artificial Neural Network (ANN)
- Support Vector Machine (SVM)
- Naive Bayes

### Students Dataset

Used for:

- K-Means Clustering

---

# Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Jupyter Notebook

---

# Machine Learning Workflow

Most supervised learning algorithms follow this workflow:

1. Import Libraries
2. Load Dataset
3. Select Features (X) and Target (y)
4. Train-Test Split
5. Feature Scaling (when required)
6. Create Model
7. Train Model
8. Make Predictions
9. Evaluate Performance

---

# Algorithm Comparison

| Algorithm | Type | Main Idea |
|----------|------|-----------|
| Linear Regression | Supervised | Predict continuous values using the best-fit line |
| Logistic Regression | Supervised | Binary classification using the Sigmoid function |
| KNN | Supervised | Predict using nearest neighbors |
| Decision Tree | Supervised | Learn decision rules by splitting data |
| Random Forest | Supervised | Ensemble of Decision Trees using voting |
| ANN | Supervised | Learn complex patterns using artificial neurons |
| SVM | Supervised | Find the optimal hyperplane with maximum margin |
| Naive Bayes | Supervised | Predict the class with the highest probability |
| K-Means | Unsupervised | Group similar data into clusters |

---

# Model Performance (Heart Disease Dataset)

| Algorithm | Accuracy |
|-----------|---------:|
| Logistic Regression | *(Update with your result)* |
| KNN | *(Update with your result)* |
| Decision Tree | **78.54%** |
| Random Forest | **100.00%*** |
| ANN | **78.05%** |
| SVM | **81.46%** |
| Naive Bayes | **75.12%** |

> **Note:** The Random Forest result of **100%** should be interpreted carefully. Such a perfect score may indicate that the dataset, selected features, or evaluation setup makes the task unusually easy, or there may be data leakage. In real-world machine learning, it is important to verify unexpectedly perfect performance.

---

# Evaluation Metrics

Models are evaluated using:

- Accuracy Score
- Confusion Matrix
- Training Accuracy (ANN)
- Testing Accuracy (ANN)
- Loss Function (ANN)

---

# Learning Objectives

This repository documents my Machine Learning learning journey. The goal is to understand both the **theory** and **implementation** of classical Machine Learning algorithms through practical coding, experimentation, and evaluation.

---

# Future Additions

- Principal Component Analysis (PCA)
- XGBoost
- AdaBoost
- Gradient Boosting
- Cross Validation
- Hyperparameter Tuning
- Feature Engineering
- Model Deployment using Flask / Streamlit

---

# Author

**Vignesh Kotrica**