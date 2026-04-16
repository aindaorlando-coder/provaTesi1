# GSD Specification - Air Quality ML Pipeline

## Goal
Generate a modular Python project that implements a machine learning pipeline for predicting Air Quality Index (AQI) using real environmental data. This pipeline is currently designed for the datasetDelhi.csv dataset only.

---

## Input
- Dataset: datasetDelhi.csv 
- Features:
  - PM2.5
  - PM10
  - NO2
  - SO2
  - CO
  - Ozone

- Target:
  - AQI (continuous variable)

---

## Expected Pipeline

### 1. Data Loading Module
- Load CSV dataset
- Validate schema

### 2. EDA Module
- Summary statistics
- Missing values analysis
- Correlation matrix

### 3. Preprocessing Module
- Feature selection
- Train/test split (80/20)
- StandardScaler applied only on training set
- Return: X_train_scaled, X_test_scaled, y_train, y_test

### 4. Model Module
- Linear Regression model
- Random Forest Regressor
- Training on processed data

### 5. Evaluation Module
- MAE
- MSE
- R²
- Comparison plots between models

---

## Output
- Clean modular Python project
- Functions separated by file:
  - data.py
  - preprocess.py
  - train.py
  - evaluate.py

---

## Constraints
- No data leakage
- Reproducible results (random_state=42)
- Code must be modular and reusable
