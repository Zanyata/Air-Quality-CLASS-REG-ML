# Air Quality Classification & Regression Project

This project aims to **predict air quality levels** using machine learning (ML) and deep learning (NN) models. It involves **data preprocessing, exploratory data analysis (EDA), model selection, hyperparameter tuning, and model evaluation** to determine the best-performing algorithm.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Methodology](#methodology)

## Overview
- Understand the impact of various pollutants on air quality.
- Compare different ML models (e.g., XGBoost, CatBoost, LightGBM).
- Experiment with **Neural Networks (NN)** to check deep learning performance.
- Evaluate model **overfitting** and generalization performance.
  
Key highlights include:
- Comprehensive exploratory data analysis (EDA)
- Hyperparameter tuning
- Machine Learning
- Deep Learning

## Dataset
- **Source:** [link](https://www.kaggle.com/datasets/rabieelkharoua/air-quality-and-health-impact-dataset/data).
  
### Features
The dataset includes the following attributes:
- Various pollutant concentrations (e.g., CO, NO2, PM2.5, PM10, O3).
- Meteorological data (e.g., temperature, humidity, wind speed).
- Hospital data (e.g. RespiratoryCases, CardiovascularCases, HospitalAdmissions)

### Target
The target variable is represented as:
- **Target Variable:** HealthImpactClass - classification; HealthImpactScore - regression.

## Project Structure
```
├── data/
│   └── air_quality_health_impact_data.csv # Original dataset
├── notebooks/
│   ├── air_quality_dataset_.ipynb
│   └── air_quality_dataset_.py
├── models/
│   ├── class_CatBoost.sav # Trained CatBoost Classification model
│   ├── class_CatBoost2.sav # Trained CatBoost Classification (lower overfitting) model
│   ├── class_Log.sav # Trained Logistic Classification model
│   ├── class_XGB.sav # Trained XGB Classification model
│   ├── reg_CatBoost.sav # Trained CatBoost Regression model
│   ├── reg_LGBM.sav # Trained LGBM Regression model 
│   ├── reg_Poly.sav # Trained Polynomial Regression model 
│   └── my_model.h5 # Trained Neural Network model
└──  README.md
```

## Methodology
1. **Data Preprocessing**:
   - Data scaling
   - Visualizations: Correlation heatmap, boxplots
2. **Exploratory Data Analysis (EDA)**:
   - Class distribution
   - Outlier detection
3. **Model Training & Hyperparameter Tuning**:
   - Classical ML models
   - Neural Network: Fully connected dense layer
4. **Model Evaluation**:
   - Accuracy, Precision, Recall, F1 Score, AUC-ROC - classification
   - RMSE, MAE, R²-score - regression
   - Confusion matrix visualization
   - Feature importance analysis
   - **Overfitting detection:** Train vs. test performance comparison.
     


