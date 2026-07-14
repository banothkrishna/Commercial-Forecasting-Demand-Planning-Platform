# Commercial Forecasting & Demand Planning Platform

## Overview

This project presents an end-to-end commercial sales forecasting solution developed using historical retail sales data. The objective is to forecast future sales by leveraging time-series analysis, feature engineering, and machine learning models. The project demonstrates a complete forecasting workflow, from data preprocessing and exploratory analysis to model development, evaluation, and business visualization.

---

## Problem Statement

Accurate sales forecasting plays a critical role in demand planning, inventory management, and commercial decision-making. The objective of this project is to predict future sales across multiple stores and product families using historical sales records, promotional events, holiday information, transactions, and external economic indicators.

---

## Dataset

The project uses the **Store Sales – Time Series Forecasting** dataset containing:

- Historical sales records
- Store information
- Product family details
- Promotional campaigns
- Holiday and event data
- Daily transaction counts
- Oil price information

---

## Objectives

- Perform exploratory data analysis on commercial sales data
- Build forecasting-ready datasets through feature engineering
- Compare machine learning forecasting models
- Evaluate forecast accuracy
- Develop business dashboards for sales insights

---

## Technology Stack

- Python
- Pandas
- NumPy
- LightGBM
- XGBoost
- SQL
- Matplotlib
- Power BI

---

## Project Workflow

```
Data Collection
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Feature Engineering
        │
        ▼
Model Training
        │
        ▼
Forecast Evaluation
        │
        ▼
Power BI Dashboard
```

---

## Feature Engineering

The following features were used to improve forecasting performance:

- Lag Features
- Rolling Mean
- Rolling Statistics
- Day of Week
- Month
- Year
- Holiday Indicators
- Promotion Features
- Oil Price Trends

---

## Forecasting Model

Machine Learning

- LightGBM

Future Models

- Facebook Prophet
- XGBoost
- SARIMA

---

## Model Evaluation

Forecast performance was evaluated using:

- Root Mean Squared Logarithmic Error (RMSLE)
- RMSE
- MAE
- MAPE

---

## Dashboard

The Power BI dashboard includes:

- Sales Trend Analysis
- Monthly Revenue Trends
- Promotional Impact
- Store-wise Performance
- Product Family Analysis
- Forecast Visualization

## Future Improvements

- Integrate Facebook Prophet and SARIMA for model comparison
- Develop automated forecasting pipelines
- Build inventory demand prediction dashboards
- Deploy the solution using Streamlit or FastAPI

---

## Author

Banoth Krishna

B.Tech, Biosciences and Bioengineering

Indian Institute of Technology Guwahati
