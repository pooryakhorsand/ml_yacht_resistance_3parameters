# Yacht Resistance Prediction Using Three Key Hydrodynamic Parameters

This project leverages machine learning algorithms to predict the **residual resistance (Rr)** of yachts using just **three core hydrodynamic parameters**. By applying advanced regression models and extensive cross-validation, it aims to offer fast and accurate resistance predictions for naval architects and marine engineers.

## 🚀 Project Highlights

- 📊 **Dataset:** Real-world yacht hydrodynamics data (`yacht_hydro.csv`)
- 🤖 **Models used:** 
  - Random Forest
  - XGBoost
  - LightGBM
  - CatBoost
  - SVR (Support Vector Regression)
  - AdaBoost
- 🔍 **Evaluation:**
  - 10-fold Cross-Validation
  - Metrics: MAE, RMSE, R²
  - Visualizations: Metric comparison bar plots, Actual vs. Predicted scatter plots
- 📈 **Goal:** Enhance design iteration by reducing dependency on expensive CFD simulations

## 🧠 How It Works

1. **Load and preprocess data**
2. **Train models** using grid search for hyperparameter tuning
3. **Evaluate** using cross-validation and standard regression metrics
4. **Visualize performance** and compare models

## 📂 Repository Structure

