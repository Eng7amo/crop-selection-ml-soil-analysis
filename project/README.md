# Soil-Based Crop Prediction Project

## Objective
The objective of this project is to assist farmers in selecting the optimal crop for a given field by predicting crop type based on soil nutrient measurements.

The project also aims to determine which soil feature contributes most to predictive performance.

---

## Dataset
The dataset `soil_measures.csv` contains soil measurements and the optimal crop label.

Features:
- N: Nitrogen content ratio
- P: Phosphorous content ratio
- K: Potassium content ratio
- pH: Soil acidity/alkalinity level

Target:
- crop: categorical variable representing the optimal crop

Each row represents a specific field measurement.

---

## Methodology

### 1. Data Preparation
- Load soil measurement data using Pandas
- Select individual soil features for evaluation

### 2. Model Training
- Train a multi-class Logistic Regression model
- Use a train-test split for evaluation
- Train one model per feature to assess predictive power

### 3. Evaluation
- Measure performance using classification accuracy
- Compare results across individual features
- Identify the most predictive soil attribute

---

## Tools Used
- Pandas
- scikit-learn (Logistic Regression, train-test split, metrics)

---

## Outputs
- Best-performing soil feature for crop prediction
- Accuracy score associated with the selected feature
- Reproducible machine learning pipeline

---

## Notes
This project emphasizes interpretability and practicality, making it suitable for real-world agricultural decision support systems.
