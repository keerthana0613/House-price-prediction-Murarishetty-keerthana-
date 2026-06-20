 House Price Prediction
## Project Overview
This project focuses on predicting house prices using machine learning techniques. The goal is to analyze housing data, identify the factors that influence property prices, and build regression models capable of estimating house prices accurately.

## Dataset
Dataset used: Housing Prices Dataset
Source:
https://www.kaggle.com/datasets/yasserh/housing-prices-dataset

The dataset contains various housing features such as:
- Area
- Number of bedrooms
- Number of bathrooms
- Stories
- Parking spaces
- Main road access
- Guest room availability
- Basement availability
- Air conditioning
- Preferred area
- Furnishing status
- House price (target variable)

## Project Tasks
### 1. Data Loading and Exploration
- Loaded the dataset using Pandas
- Displayed sample records
- Checked dataset dimensions
- Identified target and feature columns
- Examined missing values

### 2. Data Cleaning
- Removed duplicate records
- Handled missing values
- Converted categorical variables into numerical format using one-hot encoding
- Prepared data for machine learning models

### 3. Model Building
Two regression models were trained and evaluated:

#### Linear Regression
A baseline model used to predict house prices.

#### Random Forest Regressor
An ensemble learning model used to improve prediction performance.

### 4. Model Evaluation
The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

### 5. Data Visualization
The following visualizations were created:

- House Price Distribution Histogram
- Correlation Heatmap
- Feature Importance Treemap

## Technologies(libraries) Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Squarify

## Repository Structure
```
House-price-prediction-Murarishetty-keerthana/
│
├── analysis.ipynb
├── Housing.csv
├── summary.pdf
│
└── charts/
    ├── price_distribution.png
    ├── correlation_heatmap.png
    ├── feature_importance_treemap.png
    └── README.md
```

## Key Findings
- Property area was one of the strongest predictors of house price.
- Houses with more bathrooms, parking spaces, and premium amenities generally had higher prices.
- Random Forest Regressor performed better than Linear Regression by capturing complex relationships between features.
- Location-related features significantly influenced property values.

## Conclusion
This project demonstrates how machine learning can be applied to real estate price prediction. By analyzing housing characteristics and training regression models, it is possible to estimate property values and identify the most influential factors affecting house prices.

## Author
Murarishetty Keerthana

Internship Project – Week 1  
House Price Prediction
