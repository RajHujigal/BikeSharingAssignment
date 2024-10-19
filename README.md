
# Bike Demand Prediction Project

> This project aims to model and predict bike-sharing demand using historical data, focusing on understanding the factors that influence bike rental patterns.

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Model Evaluation and Results](#model-evaluation-and-results)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## General Information
- The goal of this project is to analyze the factors influencing the demand for shared bikes and create a model to predict daily bike rentals.
- The dataset contains historical data on daily bike rentals, including weather information, holiday status, and whether it was a working day.
- **Business Problem:** A U.S. bike-sharing company is looking to understand and predict demand fluctuations to adjust their strategy and improve revenue, especially after the COVID-19 pandemic.
- **Dataset:** The dataset includes variables like year, temperature, humidity, wind speed, seasonality, and more, and was used to create a regression model to predict demand.

## Conclusions
- **Seasonality:** Seasons like spring and winter significantly influence bike demand, with a drop in rentals during colder months.
- **Temperature:** There is a strong positive correlation between temperature and demand, indicating that more bikes are rented in warmer weather.
- **Weather Conditions:** Adverse weather (e.g., light snow or rain) significantly reduces bike demand.
- **Other Factors:** Working days and weekends show different rental patterns, with weekends generally seeing higher demand.

## Technologies Used
- Python 3.x
- Libraries:
  - `pandas` - data manipulation and analysis
  - `numpy` - numerical operations
  - `matplotlib` and `seaborn` - data visualization
  - `scikit-learn` - model building and evaluation
  - `statsmodels` - statistical analysis and regression modeling

## Model Evaluation and Results
- **Model Type:** Multiple Linear Regression
- **Metrics:**
  - **R-squared (Train):** 0.82
  - **R-squared (Test):** 0.83
  - **Mean Squared Error (MSE) (Test):** 643,431
  - **Root Mean Squared Error (RMSE) (Test):** 802
- The model performs well with a strong R-squared score, indicating that it explains around 83% of the variance in bike demand.
- The residuals analysis shows that the model satisfies the assumptions of linear regression, with normally distributed residuals and no signs of autocorrelation.

## Acknowledgements
- This project was inspired by the need to understand demand patterns in the bike-sharing industry.
- Data source: The dataset used in this project is part of a publicly available bike-sharing dataset for analysis.

## Contact
Created by Raj Hujigal] - feel free to contact me at rajhujigal@gmail.com.
