# HOUSE-SALES-PRISE-PREDICTION-ML-MODEL-NEW
Improved a House Price Prediction model from **R² = 0.37 to 0.57** using the same dataset through data cleaning, feature engineering, outlier handling, feature scaling, and preprocessing optimization. Demonstrates the power of strong data pipelines in Machine Learning.
# House Price Prediction - Model Optimization Project

## Overview

This project focuses on improving the performance of a House Price Prediction model using the same dataset as an existing baseline project.

The original model achieved an **R² Score of 0.37**. By applying a data-centric Machine Learning workflow including preprocessing, feature engineering, and optimization techniques, the improved model achieved an **R² Score of 0.57**.

This project demonstrates how better data preparation can significantly improve model performance without relying solely on more complex algorithms.

---

## Objective

To enhance prediction performance by optimizing the complete Machine Learning pipeline:

* Data Cleaning
* Missing Value Handling
* Outlier Treatment
* Feature Engineering
* Feature Scaling / Standardization
* Target Variable Transformation
* Model Training & Evaluation

---

## Results

| Model Version   | R² Score |
| --------------- | -------- |
| Baseline Model  | 0.37     |
| Optimized Model | 0.57     |

**Performance Improvement:** +20 percentage points

---

## Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Workflow

### 1. Data Cleaning

* Removed duplicate records
* Handled null values systematically
* Detected inconsistent entries

### 2. Outlier Treatment

* Identified extreme values using statistical methods
* Reduced noise affecting model learning

### 3. Feature Engineering

* Created meaningful derived features
* Improved signal quality for regression

### 4. Feature Scaling

* Applied StandardScaler (Z-score normalization)

### 5. Target Variable Optimization

* Reduced skewness using transformations where needed

### 6. Model Training

* Trained regression models
* Compared performance using evaluation metrics

---

## Evaluation Metric

Used **R² Score** to measure how well the model explains variance in house prices.

```python
from sklearn.metrics import r2_score
```

---

## Key Learning

In many Machine Learning projects, improving the **data pipeline** creates more impact than switching algorithms repeatedly.

A clean dataset + meaningful features often outperform a complex model trained on noisy data.

---

## Future Improvements

* Hyperparameter Tuning
* XGBoost / LightGBM / CatBoost
* Cross Validation
* Better Location-Based Features
* Deployment with Flask / Streamlit

---

## Project Structure

```bash
House-Price-Prediction/
│── data/
│── notebooks/
│── src/
│── models/
│── README.md
│── requirements.txt
```

---

## Author

Developed as part of hands-on Machine Learning practice focused on real-world model optimization.

---
