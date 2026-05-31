# Genetic Disease Prediction using Machine Learning

## Overview

This project focuses on predicting genetic diseases using Machine Learning techniques. The objective is to analyze genetic and medical data, identify patterns associated with various diseases, and develop predictive models capable of assisting in disease classification.

The project implements a complete machine learning pipeline, including data preprocessing, exploratory data analysis, dimensionality reduction, model training, hyperparameter optimization, and performance evaluation. Multiple machine learning algorithms were trained and compared to identify the most effective model for disease prediction.

Among all the algorithms tested, XGBoost achieved the highest predictive performance and was selected as the final model.

---

## Dataset

**Dataset Source:**

https://www.kaggle.com/datasets/syeddanish5/genetic-disease-prediction-dataset

The dataset contains genetic and medical attributes used to predict disease outcomes.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost
* Imbalanced-Learn
* Jupyter Notebook

---

## Project Workflow

1. Data Collection
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Selection and Transformation
5. Principal Component Analysis (PCA)
6. Train-Test Data Splitting
7. Model Training
8. Hyperparameter Optimization
9. Model Evaluation
10. Model Comparison and Selection

---

## Machine Learning Algorithms Implemented

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Decision Tree
* Random Forest
* Support Vector Machine (Linear Kernel)
* Support Vector Machine (Polynomial Kernel)
* AdaBoost
* Gradient Boosting
* XGBoost

---

## Advanced Techniques Implemented

### Principal Component Analysis (PCA)

Applied PCA for dimensionality reduction to reduce feature redundancy, improve computational efficiency, and preserve important information from the dataset.

### K-Fold Cross Validation

Used K-Fold Cross Validation to assess model stability and ensure consistent performance across different data splits.

### Hyperparameter Tuning

#### GridSearchCV

Performed exhaustive hyperparameter tuning to identify the optimal parameter combinations for machine learning models.

#### RandomizedSearchCV

Implemented Randomized Search for efficient exploration of the hyperparameter space and performance improvement.

### SMOTE (Synthetic Minority Oversampling Technique)

SMOTE was applied as part of experimentation and model evaluation to study the impact of oversampling techniques on predictive performance.

---

## Model Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Classification Report

---

## Results

Multiple machine learning models were trained and evaluated.

The performance comparison demonstrated that **XGBoost** achieved the highest predictive accuracy and overall performance among all tested algorithms.

The project highlights the effectiveness of ensemble learning techniques for genetic disease prediction tasks.

---

## Key Concepts Learned

* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Principal Component Analysis (PCA)
* K-Fold Cross Validation
* GridSearchCV
* RandomizedSearchCV
* Classification Algorithms
* Ensemble Learning
* XGBoost
* Model Evaluation Metrics
* Confusion Matrix Analysis
* Machine Learning Pipeline Development

---

## Project Structure

```text
Genetic-Disease-Prediction/
│
├── Genetic_Disease_Prediction.ipynb
├── README.md
├── requirements.txt
├── LICENSE
├── screenshots/
└── dataset_link.txt
```

---

## Future Enhancements

* Streamlit Web Application Deployment
* Hyperparameter Optimization Improvements
* Feature Importance Analysis
* Model Explainability using SHAP
* Real-Time Prediction Interface
* Cloud Deployment

---

## Author

Madishetti Swapna

B.Tech Computer Science Engineering

Machine Learning Enthusiast | Data Science Learner | Aspiring AI Engineer
