# Lab8-K-Nearest-Neighbors-KNN- Classification Project


## Overview
This project demonstrates the implementation of the K-Nearest Neighbors (KNN) algorithm using Python and Scikit-learn to classify artificial data into target classes.

The project includes:
- Exploratory Data Analysis (EDA)
- Data Standardization
- Train/Test Split
- KNN Model Training
- Model Evaluation
- K Value Optimization

---

## Problem Type
Supervised Machine Learning – Classification

---

## Objective
The objective of this project is to build a KNN classification model that predicts the target class of data observations based on feature similarity.

---

## Dataset Information
The dataset used in this project is an artificial classification dataset containing multiple numerical features and one target column:

- **Target Variable:** TARGET CLASS  
- **Features:** Numerical artificial variables  

---

## Libraries Used
The following Python libraries were used:

```python
pandas
numpy
matplotlib
seaborn
scikit-learn

## Project Workflow

### 1. Data Exploration
Conducted exploratory data analysis (EDA) using Seaborn Pairplot to visualize feature distributions and examine relationships between variables.

### 2. Data Preprocessing
Applied feature scaling using StandardScaler to normalize the dataset and ensure all variables contribute equally to distance calculations.

### 3. Data Splitting
Divided the dataset into:
- 70% Training Set
- 30% Testing Set

### 4. Model Development
Built and trained a K-Nearest Neighbors (KNN) classification model using Scikit-learn.

### 5. Model Evaluation
Evaluated model performance using:
- Confusion Matrix
- Classification Report

### 6. Hyperparameter Optimization
Applied the Elbow Method to identify the most suitable K value for improving model performance.

## Results

The model was initially evaluated using **K = 1**.

To improve performance, hyperparameter tuning was conducted using the **Elbow Method** to determine the most suitable number of neighbors.

### Optimal K Value
```python
K = 30

### Final Accuracy Achieved:
83%

## Key Learning Outcomes

This project provided practical experience in the following areas:

- Implementing the K-Nearest Neighbors (KNN) classification algorithm
- Applying feature scaling techniques for data preprocessing
- Performing hyperparameter optimization for model improvement
- Evaluating machine learning models using classification metrics
- Conducting error rate analysis for performance assessment
