# Master Thesis LL
# Demand Forecasting Models - README

This repository contains a series of Google Colab notebooks used for coding and evaluating various demand forecasting models. The notebooks are organized sequentially, covering data preparation, visualization, and the implementation of different forecasting models including naive, statistical, and machine learning approaches. Below is a brief description of each notebook:

## 1. Data Preparation
**Filename:** `MT LL Data Preparation.ipynb`

This notebook includes steps for data cleaning, transformation, and feature engineering necessary for the demand forecasting task. It ensures the raw data is preprocessed and ready for analysis and modeling.

## 2. Data Visualization
**Filename:** `MT LL Data Visualization.ipynb`

This notebook provides various visualizations to understand the underlying patterns, trends, and seasonality in the data. It includes time series plots, and other exploratory data analysis techniques.

## 3. Naive and Statistical Models
**Filename:** `MT LL Naïve/Statistical models.ipynb`

This notebook covers the implementation of naive forecasting methods and statistical models such as:
- Naive methods (e.g., last week observation carried forward)
- ARIMA (AutoRegressive Integrated Moving Average)
- Holt-Winters Exponential Smoothing

## 4. LightGBM Model
**Filename:** `MT LL LightGBM.ipynb`

This notebook details the implementation of the LightGBM (Light Gradient Boosting Machine) model for demand forecasting. It includes steps for hyperparameter tuning, training, and evaluation of the model.

## 5. LSTM Model
**Filename:** `MT LL LSTM.ipynb`

This notebook demonstrates the use of Long Short-Term Memory (LSTM) networks. It includes steps for feature scaling, hyperparameter tuning, training, and evaluation of the model.


## 6. SVR Model
**Filename:** `MT LL SVR.ipynb`

This notebook focuses on the implementation of Support Vector Regression (SVR) for demand forecasting. It includes steps for feature scaling, hyperparameter tuning, training, and evaluation of the model.

---

The forecasting models implemented in these notebooks are compared to determine which one achieves the best accuracy. The goal is to enhance the precision of demand forecasts for perishable products with short shelf lives. Accurate forecasting is crucial for reducing food waste, ensuring that products are available when needed, and minimizing spoilage due to overstocking. Each notebook is designed to be run independently in Google Colab, with the necessary context and explanations provided within. Users can follow along step-by-step to understand the process and methodology used in building these demand forecasting models.
