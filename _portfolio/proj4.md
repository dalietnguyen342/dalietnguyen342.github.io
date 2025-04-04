---
title: "Evaluating Livability and Human Development in Vietnamese Provinces"
collection: portfolio
category: projects
excerpt: "Technologies: Python, Power BI, Pandas, Numpy, Tableau, Seaborn, Regression, Clustering"
---

Github: [Github](https://github.com/NhiNguyen34/DS105.O11.KHDL)

![image](https://github.com/user-attachments/assets/0e2d3227-0782-4e16-ae99-7bf348b5b02b)

## Overview

In this project, our team aimed to evaluate the livability of 63 Vietnamese provinces and predict their Human Development Index (HDI) by building a robust data-driven model. The project was executed as part of our Data Analysis and Visualization coursework, and it involved the following key steps:

## Data Collection & Integration

-   We sourced raw statistical data from the General Statistics Office of Vietnam, covering the period from 2002 to 2022.
-   The dataset encompassed various indicators including healthcare, social security, economic performance, labor, employment, and average income per capita.
-   Data was originally spread across 55 separate files and then consolidated into a comprehensive CSV dataset after filtering and integrating multiple formats.

## Data Preprocessing & Exploration

-   Extensive cleaning and standardization were performed, such as normalizing province names, converting numerical values, and handling missing data (e.g., replacing placeholder values with NaN).
-   We eliminated attributes with excessive missing data and standardized the remaining features to ensure consistency.
-   Exploratory Data Analysis (EDA) was conducted to assess distributions, detect outliers, and evaluate correlations among various features.

## Design of Custom Livability Indices

-   Four custom indices were developed to measure different dimensions of livability:
    -   Public Security
    -   Labor-Employment-Income
    -   Healthcare
    -   Quality of Life
-   Each index was calculated by averaging the normalized values of relevant attributes, and the resulting scores were standardized on a scale from 0 to 1.

## Predictive Modeling of HDI

-   The target variable was the Human Development Index (HDI) for each province.
-   The dataset was split into training and testing sets for model evaluation.
-   Several regression algorithms were tested, including Linear Regression, Stochastic Gradient Descent (SGD), Random Forest, Gradient Boosting, LightGBM, and CatBoost.
-   Model performance was assessed using R², Mean Squared Error (MSE), and Mean Absolute Error (MAE).
-   The CatBoost model outperformed others, achieving an R² of 0.9359, which demonstrated its superior predictive capability.

## Clustering Analysis

-   K-means clustering was applied to group provinces based on the custom livability indices.
-   This clustering provided clear insights into the developmental profiles of different regions, distinguishing provinces with high economic and social development from those facing significant challenges.

## Data Visualization

-   Visualization tools and libraries such as Pandas, Numpy, Tableau, PowerBI, and Seaborn were used to create interactive dashboards and comprehensive charts.
-   These visualizations effectively communicated trends, correlations, and cluster patterns across the various indicators.

## Conclusion

This project delivers a comprehensive view of the developmental landscape across Vietnamese provinces. By combining rigorous data preprocessing, custom index creation, advanced regression techniques, and clustering analysis, the study provides valuable insights that can inform policy decisions and strategic planning for regional development. The integration of interactive data visualizations further enhances the accessibility and impact of the findings.

