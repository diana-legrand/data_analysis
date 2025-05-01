# Customer Churn Prediction

Due to the large file size and potential rendering issues in Jupyter ("The notebook took too long to render"), it is recommended to view the project via nbviewer using the [provided link](https://nbviewer.org/github/diana-legrand/data_analysis/blob/main/churn_prediction_using_ml/churn_prediction_using_ml.ipynb).


## Objective

The goal of this project was to develop a machine learning model to predict customer churn for a fitness center.

## Summary

This analysis focused on identifying the key factors contributing to customer churn. The most influential features were explored in detail. Churn prediction models were built using **logistic regression** and **random forest** algorithms, with logistic regression delivering the best performance. In addition to predictive modeling, customer segmentation was performed using clustering techniques. Based on the resulting clusters, targeted marketing recommendations were developed to help reduce churn for each customer segment.

## Project Overview

- The project involved a full-cycle data science workflow:
- Exploratory Data Analysis (EDA). We examined behavioral, demographic, and contract-related data to understand usage patterns and identify early warning signs of churn.
Feature Engineering & Correlation Analysis. Key drivers of churn were identified, such as contract length, visit frequency, and customer lifetime. Irrelevant or weakly correlated features (e.g., gender, phone availability) were removed or deprioritized.
- Model Development. Two classification algorithms were implemented:
- Logistic Regression: Delivered high interpretability and solid performance.
- Random Forest: Captured non-linear relationships and interactions.
The logistic regression model was selected as the final model due to its slightly better accuracy and transparency in explaining business decisions.
- Customer Segmentation via Clustering. Clients were grouped into five distinct segments using hierarchical and KMeans clustering. Each cluster was profiled, and actionable recommendations were created for the marketing team to reduce churn by tailoring engagement strategies.

## Libraries Used:
- *pandas*
- *numpy*
- *itertools*
- *re*
- *matplotlib*
- *seaborn*
- *sklearn*
- *datetime*
- *stats*

## Project Status: Completed.
