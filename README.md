# Python-CHICAGO-ENERGY-SAVINGS-Analysis

## Introduction:
Urban buildings significantly contribute to energy consumption and greenhouse gas emissions, requiring targeted efficiency improvements for sustainability.
The Chicago Energy Benchmarking dataset, encompassing over 24,000 properties, offers a comprehensive view into building-level energy performance and emissions.
This study evaluates energy use patterns, identifies inefficiencies, forecasts future emission trends, and proposes strategies to improve building energy efficiency.

## Methodology
#### Dataset Description: 
24,892 records, 30 variables from Chicago's Energy Benchmarking Ordinance, including energy usage, emissions, building size, and age.
#### Data Cleaning: 
Missing values handled using mean/mode imputation; outliers identified and assessed; duplicate records removed to ensure independence.
#### Exploratory Data Analysis (EDA): 
Visualizations (bar charts, heatmaps, boxplots) revealed patterns in GHG emissions, Site EUI, and Energy Star Scores.
#### Modeling Approaches:Classification Models: 
Naive Bayes, Logistic Regression, Decision Tree, Gradient Boosting.Forecasting Model: ARIMA for GHG emissions time series.
#### Classification Metrics: 
Accuracy, sensitivity, specificity evaluated using confusion matrices; binary classification used to improve performance measurement

## Results

Gradient Boosting achieved the best overall classification accuracy (87% cross-validation, 99% binary).
Decision Trees performed well but showed signs of overfitting on training data.
Logistic Regression had strong sensitivity but poor specificity, suggesting issues with class imbalance.
<img width="1947" height="796" alt="Results" src="https://github.com/user-attachments/assets/7ccc1c8d-c35e-4fa8-91dc-756fe44c67da" />

## Forecasting Performance:
ARIMA model showed good stationarity (p<0.05), low prediction error, and realistic trend capture.
<img width="2080" height="1050" alt="ARIMA Model" src="https://github.com/user-attachments/assets/e06395cf-b377-4821-bf95-1096d60d6ee9" />
