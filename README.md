# Customer Engagement Hypothesis: Statistical & ML Analysis
## Overview
This repository contains an analysis of customer engagement, retention, and conversion at Acem.ai using statistical methods and machine learning techniques. By leveraging key data sources, we explore:

New customer acquisition trends
Paying customer patterns
Churn rate impact
Conversion rate optimization
Our goal is to identify trends, correlations, segmentations, and predictions to improve customer acquisition and retention strategies.

## Methodology
✅ Exploratory Data Analysis (EDA) – Cleaning, visualizing, and summarizing customer engagement trends.  
✅ Statistical Analysis – Pearson correlation, hypothesis testing, and regression modeling to measure key relationships.  
✅ Machine Learning Techniques:  
    Clustering (K-Means, PCA) – Identifies customer segments based on behavior.
    Regression Models (OLS, Linear Regression) – Predicts paying customer trends.
    Time Series Forecasting – Analyzes trends in customer acquisition and retention.

## Key Findings
1. **Declining New Customer Acquisition**: A significant decline in new customer acquisition over time, impacting conversion rates and the number of paying customers.
2. **Strong Correlation**: A strong positive correlation between new customers and paying customers, indicating that acquiring new customers directly increases paying customers.
3. **Segmentation**: Customer clustering revealed two distinct groups: high-engagement/high-conversion customers and low-engagement/low-conversion customers. This segmentation will help in crafting targeted marketing strategies.

## Dataset
The analysis uses the following data sources:
1. **Active Users**: Daily active user counts.
2. **Landing Page Visitors**: Daily visitor counts to the landing page.
3. **Subscription Churn**: Tracks the rate at which users discontinue services.
4. **Subscription Conversion**: Conversion rate from free users to paying subscribers.

## Technologies Used
Python (Pandas, NumPy, Scikit-learn, Statsmodels)  
Data Visualization (Matplotlib, Seaborn)  
Machine Learning (K-Means, Linear Regression, PCA)  
