# Rossmann Store Sales Forecasting Using Machine Learning

## Overview
Accurate sales forecasting is a critical task in retail analytics, directly impacting inventory planning, workforce allocation, and promotional strategies.  
This project applies machine learning techniques to predict daily sales for Rossmann drugstores using historical sales data, store characteristics, and promotional information.

The project was developed as part of the MSc Data Science Final Project at the University of Hertfordshire.

## Dataset
This project uses the **Rossmann Store Sales dataset**, originally released as part of a Kaggle competition.

Source: https://www.kaggle.com/c/rossmann-store-sales
Description: Daily sales data for multiple Rossmann stores, including information on promotions, holidays, store types, assortment, and competition distance.

⚠️ The dataset is **not included** in this repository due to size and licensing restrictions.  
Instructions for obtaining the data are provided in `data/README.md`.

## Project Workflow

The overall workflow of the project is summarised below:

1. Exploratory Data Analysis (EDA) to understand sales patterns and feature relationships  
2. Data cleaning and preprocessing to handle missing values and inconsistencies  
3. Feature engineering based on temporal and promotional factors  
4. Model training and optimisation  
5. Model evaluation and comparison using appropriate performance metrics  

The workflow was designed to ensure a systematic and reproducible approach to model development.

---

## Models Implemented

The following regression models were implemented and evaluated:

- **Linear Regression** (baseline model)  
- **Random Forest Regression**  
- **XGBoost Regression**  

Model performance was evaluated primarily using **Root Mean Squared Error (RMSE)**, with **R²** used as a supplementary metric to assess goodness of fit.

---

## Results Summary

The experimental results demonstrate that ensemble-based models outperform baseline linear approaches on the Rossmann dataset.

- **XGBoost** achieved the **lowest RMSE** and **highest R²**  
- Ensemble methods were more effective at capturing non-linear relationships and feature interactions  
- Feature importance analysis highlighted the significance of customer counts, promotions, and temporal features  

Detailed results, analysis, and visualisations are presented in the final project report.
