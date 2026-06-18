# House Price Prediction

## Project Overview

This project focuses on predicting house prices using machine learning techniques. The goal was to analyze various property features and build a model capable of estimating house prices with reasonable accuracy.

## Dataset

* Source: Kaggle Housing Prices Dataset
* File: Housing.csv
* Records: 545 houses
* Features include area, bedrooms, bathrooms, parking, furnishing status, air conditioning, preferred area, and more.

## Tasks Performed

1. Data Loading and Exploration
2. Data Cleaning and Preprocessing
3. Feature Encoding using One-Hot Encoding
4. Model Building using:

   * Linear Regression
   * Random Forest Regressor
5. Model Evaluation using:

   * MAE (Mean Absolute Error)
   * RMSE (Root Mean Squared Error)
   * R² Score
6. Data Visualization

## Results

### Linear Regression

* MAE: 970,043
* RMSE: 1,324,507
* R² Score: 0.653

### Random Forest Regressor

* MAE: 1,021,546
* RMSE: 1,400,566
* R² Score: 0.612

Linear Regression performed better and was selected as the final model.

## Visualizations

The project includes:

* House Price Distribution Histogram
* Correlation Heatmap
* Furnishing Status vs Price Boxplot
* Actual vs Predicted Price Scatter Plot

## Key Findings

* House area is one of the strongest factors affecting price.
* Bathrooms, parking spaces, and air conditioning also influence house prices.
* Furnished houses generally have higher prices than unfurnished houses.
* Properties located in preferred areas tend to have higher market value.

## Repository Structure

├── analysis.ipynb
├── Housing.csv
├── summary.pdf
├── README.md
└── charts/
      ├── price_distribution_histogram.png
      ├── correlation_heatmap.png
      ├── furnishing_status_boxplot.png
      └── actual_predicted_scatter_plot.png

