\# Heart Disease Prediction using Machine Learning



\## Overview



This project predicts the presence of heart disease using patient medical data. Multiple machine learning algorithms were implemented and compared to evaluate their performance on the same dataset.



The goal is to understand the complete machine learning workflow, from data preprocessing and model training to evaluation and prediction.



\---



\## Dataset



The project uses the Heart Disease Dataset containing patient health information and a target variable indicating whether heart disease is present.



\### Target Variable



\* \*\*0\*\* → No Heart Disease

\* \*\*1\*\* → Heart Disease Present



\---



\## Features Used



\* Age

\* Sex

\* Chest Pain Type (cp)

\* Resting Blood Pressure (trestbps)

\* Cholesterol (chol)

\* Maximum Heart Rate Achieved (thalach)

\* ST Depression Induced by Exercise (oldpeak)



\---



\## Machine Learning Models Implemented



\### Logistic Regression



A supervised classification algorithm used as the baseline model.



\*\*Accuracy:\*\* 75.12%



\---



\### K-Nearest Neighbors (KNN)



A distance-based classification algorithm that predicts the class based on the nearest neighbors.



\*\*Configuration:\*\*



\* K = 3

\* StandardScaler used for feature scaling



\*\*Accuracy:\*\* 87.80%



\---



\## Project Workflow



1\. Load Dataset

2\. Select Features and Target Variable

3\. Split Data into Training and Testing Sets

4\. Scale Features using StandardScaler

5\. Train Machine Learning Model

6\. Make Predictions

7\. Evaluate Performance

8\. Predict on New Patient Data



\---



\## Evaluation Metrics



The following metrics were used to evaluate model performance:



\* Accuracy Score

\* Confusion Matrix



\---



\## Technologies Used



\* Python

\* Pandas

\* Scikit-Learn

\* Jupyter Notebook



\---



\## Results



| Model                     | Accuracy |

| ------------------------- | -------- |

| Logistic Regression       | 75.12%   |

| K-Nearest Neighbors (KNN) | 87.80%   |



KNN achieved better performance than Logistic Regression on this dataset.



\---



\## Repository Structure



```text

Heart-Disease-Prediction/

│

├── heart.csv

├── heart disease prediction logistic.ipynb

├── heart disease prediction KNN.ipynb

└── README.md

```



\---



\## Author



Vignesh Kotrica



Machine Learning Learning Project



