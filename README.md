# Sales Forecasting Project

## Overview
This project focuses on forecasting sales data using various machine learning techniques. It employs regression models and time series analysis to predict future sales based on historical data from restaurants and their associated items.

## Table of Contents
- [Technologies Used](#technologies-used)
- [Data Description](#data-description)
- [Usage](#usage)
- [Models Implemented](#models-implemented)
- [Results](#results)

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- TensorFlow (Keras)

## Data Description
The project utilizes the following datasets:
- **items.csv**: Contains details about items available in the restaurants.
- **restaurants.csv**: Contains information about various restaurants.
- **sales.csv**: Contains historical sales data for the restaurants.

## Usage
1. Load the datasets into the Python environment:
   ```python
   import pandas as pd
   items = pd.read_csv('items.csv')
   restaurants = pd.read_csv('restaurants.csv')
   sales = pd.read_csv('sales.csv')
   ```
2. Run the Jupyter Notebook to perform data analysis and train the models.

## Models Implemented
The following machine learning models are implemented for sales forecasting:
- **Linear Regression**
- **Random Forest Regressor**
- **XGBoost Regressor**
- **LSTM (Long Short-Term Memory) Neural Network**

## Results
The results of the models are evaluated using metrics such as R² score and Mean Absolute Percentage Error (MAPE). The best-performing model will be highlighted in the analysis section of the notebook.
