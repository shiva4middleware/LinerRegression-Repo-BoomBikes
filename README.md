# Bike Sharing Demand Prediction using Linear Regression

## Project Overview
This project implements **Multiple Linear Regression** to predict bike-sharing demand for Boom Bikes, leveraging temporal and weather-related data. It provides insights for demand forecasting, helping the business optimize bike availability and maintenance.

## Problem Statement
The goal of this project is to predict the number of bike rentals for each hour using the historical data. The dataset includes features like date, temperature, humidity, and weather conditions, which impact bike demand.

## Dataset Description
The dataset contains hourly data for the bike-sharing system. Key features include:
- **datetime**: Date and time
- **season**: Season of the year
- **holiday**: Whether it is a holiday or not
- **workingday**: Whether the day is a working day
- **weather**: Weather conditions
- **temp**: Temperature
- **humidity**: Humidity
- **windspeed**: Wind speed
- **cnt**: Total number of bike rentals (target variable)

## Methodology

1. **Data Preprocessing**:
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling
   
2. **Exploratory Data Analysis**:
   - Identifying correlations between features and the target variable
   - Visualizing trends and seasonality
   
3. **Modeling**:
   - Training a Multiple Linear Regression model
   - Evaluating model performance using metrics like R-squared and RMSE

4. **Results**:
   - Comparison of predicted vs. actual demand
   - Model performance metrics

## Requirements

- Python >= 3.x
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/shiva4middleware/LinerRegression-Repo-BoomBikes.git
