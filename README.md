# 🌾 Crop Yield Prediction - an EDA Project

## Project Overview:

This project was developed as part of my **21PCS02 - Exploratory Data Analysis Course Work Mini Project**. The project aims to predict crop yield on Indian crops 🇮🇳 using machine learning by performing exploratory data analysis (EDA), data preprocessing, feature engineering, and regression model comparison.

## 📂 Dataset:

The dataset used in this project is available on Kaggle [Link: https://www.kaggle.com/datasets/akshatgupta7/crop-yield-in-indian-states-dataset]

## Tech Stack:

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost

## 📊 Exploratory Data Analysis (EDA):

The following exploratory analysis was performed on the dataset:

* Dataset inspection and feature analysis
* Missing value identification using a heatmap
* Bar charts for categorical features:

  * Crop
  * Season
  * State
* Histograms for numerical features:

  * Crop_Year
  * Area
  * Production
  * Annual_Rainfall
  * Fertilizer
  * Pesticide

* Kernel Density Estimation (KDE) plot for the target variable (**Yield**)
* Scatter plots to analyze the relationship between numerical features and crop yield
* Correlation matrix (heatmap) to study relationships among numerical features

## ⚙️ Data Preprocessing:

The following preprocessing steps were carried out before model training:

* One-Hot Encoding of categorical features:

  * Crop
  * State
  * Season
* Train-Test Split using an **80:20** ratio

## 🤖 Machine Learning Models:

The following regression models were trained and evaluated:

* Linear Regression
* Random Forest Regressor
* XGBoost Regressor

---

## 📈 Model Performance

| Model                         | Mean Squared Error (MSE) |   R² Score |
| ----------------------------- | -----------------------: | ---------: |
| Linear Regression             |               158,461.93 |     0.8022 |
| XGBoost Regressor             |                64,979.64 |     0.9189 |
| **Random Forest Regressor** ⭐ |            **10,568.91** | **0.9868** |

The **Random Forest Regressor** outperformed the other models, achieving the **lowest Mean Squared Error (10,568.91)** and the **highest R² Score (0.9868)**, indicating the best predictive performance for crop yield on the given dataset.

## 📉 Model Evaluation:

The trained models were evaluated using:

* Mean Squared Error (MSE)
* R² Score
* Actual vs Predicted Crop Yield Scatter Plot

## Project Workflow:

1. Dataset Loading
2. Exploratory Data Analysis (EDA)
3. Missing Value Analysis
4. Data Visualization
5. One-Hot Encoding
6. Train-Test Split (80:20)
7. Model Training
8. Model Evaluation
9. Performance Comparison
