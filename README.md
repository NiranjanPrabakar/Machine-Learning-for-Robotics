# 🌧️ Rainfall Prediction and Agricultural Insights using Machine Learning (1901–2025)

## 📘 Overview

This project presents a comprehensive analysis and forecasting system for rainfall patterns in India — with a special focus on **Tamil Nadu** — using historical rainfall data from **1901 to 2015**. We apply a variety of machine learning techniques including **Ensemble models**, **Hybrid Deep Learning models**, **Clustering techniques**, and **Dimensionality Reduction**. The end goal is to not only achieve accurate rainfall predictions, but also extend the insights for **agriculture-based crop planning and yield optimization**.

---

## 📊 Dataset

- **Source**: Government of India / IMD dataset  
- **File**: `rainfall in india 1901-2015.csv`  
- **Fields**: Yearly and monthly rainfall across various subdivisions including Tamil Nadu  
- **Size**: Covers 115 years of data (1901–2015)

---

## 🧠 Models Used

### 🔁 Ensemble Machine Learning Models
- ✅ `RandomForestRegressor`
- ✅ `GradientBoostingRegressor`
- ✅ `XGBoostRegressor`
- ✅ `AdaBoostRegressor`

### 🤖 Deep Learning & Hybrid Models
- ✅ `LSTM` (Standalone)
- ✅ `Hybrid LSTM + XGBoost`
- ✅ `Hybrid LSTM + Random Forest`

### 📈 Evaluation Metrics
- ✅ `RMSE` (Root Mean Squared Error)
- ✅ `MAE` (Mean Absolute Error)
- ✅ `R² Score` (Coefficient of Determination)

### 📦 Clustering Techniques
- ✅ `KMeans` (for seasonal or year-based clustering)
- ✅ `KModes` (for categorical data clustering)
- ✅ Cluster-based average rainfall prediction per season

### 🧬 Dimensionality Reduction
- ✅ `Kernel PCA` for visualization and noise reduction

---

## 📅 Forecasting Range

- 📌 **Training data**: 1901–2015  
- 📌 **Prediction range**: 2016–2025  
- 📌 **Focus region**: Tamil Nadu and other Indian subdivisions

---

## 📉 Visualizations Included

- 📌 Line Plots (Actual vs Predicted rainfall)
- 📌 Bar Charts (Model-wise RMSE / R² comparison)
- 📌 Heatmaps (Month-wise rainfall prediction per year)
- 📌 Boxplots (Monthly rainfall trends)
- 📌 Clustering visualizations (year/month groups)

---

## 🌾 Agricultural Applications

This model has been extended to:
- 📍 Identify **ideal months for crop sowing**
- 📍 Estimate **crop yield** based on rainfall forecast
- 📍 Aid in **crop recommendation systems** for major crops in Tamil Nadu
- 📍 Support planning for **water resource management** and irrigation

---

## 🗂️ Folder Structure

Rainfall_Prediction_Project/
│
├── rainfall in india 1901-2015 (1).csv # Dataset
├── Machine Learning-Based Rainfall Prediction: A Multimodel Approach and Its Agricultural Impact # Core ML Notebook
├── Model_Evaluation_Metrics.ipynb
├── TamilNadu_Rainfall_Ensemble_Prediction_and_Trend_Analysis.ipynb # Clustering-based Rainfall Analysis
├── TamilNadu_Rainfall_LSTM_Time_Series_Forecasting.ipynb
└── Dataset Preprocessing


