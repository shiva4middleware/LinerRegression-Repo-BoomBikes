# Bike Sharing Demand Prediction

## Overview
This project builds a multiple linear regression model to predict the demand for shared bikes. The goal is to identify factors that significantly influence bike demand and help the company optimize its business strategy.

## Dataset
- **Source:** Provided dataset on daily bike demand.
- **Features:** Various meteorological and temporal factors.
- **Target Variable:** `cnt` (total bike rentals).

## Methodology
1. **Data Preparation**
   - Categorical encoding for `season` and `weathersit`.
2. **Exploratory Data Analysis**
   - Visualizations and correlation analysis.
3. **Model Building**
   - Multiple linear regression using `sklearn`.
4. **Evaluation**
   - R-squared score and residual analysis.
