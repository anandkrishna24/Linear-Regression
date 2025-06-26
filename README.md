# 🏡 Linear Regression - Simple & Multiple (California Housing)

This project demonstrates both **Simple** and **Multiple Linear Regression** using the **California Housing Dataset**.

---

## 📦 Libraries Used

- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Statsmodels
- Joblib

---

## 📁 Dataset

Loaded from `sklearn.datasets.fetch_california_housing`.  
Features include:
- `MedInc`: Median Income
- `HouseAge`: Average age of homes
- `AveRooms`, `AveBedrms`, `Population`, `AveOccup`, `Latitude`, `Longitude`  
Target: `MedHouseVal` — Median House Value

---

## ✅ What’s Implemented

### 1. **Simple Linear Regression**
- Predict house value using only `MedInc` (Median Income)
- Metrics: MAE, MSE, R²
- Visualized with regression line plot

### 2. **Multiple Linear Regression**
- Predict using **all 8 features**
- Evaluation using MAE, MSE, R²
- Visualizations:
  - Actual vs Predicted
  - Residual Histogram
  - QQ Plot
  - Residuals vs Predictions

### 3. **Extra Analysis**
- VIF (Variance Inflation Factor) to check for multicollinearity
- Saved the trained model (`.pkl`)

---

## 📊 Sample Results (Approximate)

| Model | MAE | MSE | R² Score |
|-------|-----|-----|----------|
| Simple (MedInc) | ~0.52 | ~0.53 | ~0.46 |
| Multiple (All features) | ~0.53 | ~0.55 | ~0.60 |

---

## 🧠 Concepts Practiced

- Regression modeling
- Feature vs target analysis
- Residual behavior
- Multicollinearity using VIF
- Saving models for reuse

---

