# Real Estate Price Prediction

## Overview

This project aims to predict house sale prices using the **Ames Housing Dataset**. The dataset contains various features related to properties in Ames, Iowa, such as **building class**, **overall quality**, and **lot size**, among others. We use machine learning techniques to build a model that predicts the sale price based on these features.

## Dataset

The dataset comes from the **Ames Housing Dataset** by Dean De Cock, available on Kaggle. It contains **80 features** about the properties, such as:

- **SalePrice**: Target variable representing the property's sale price.
- **OverallQual**: Overall material and finish quality.
- **YearBuilt**: Year of construction.
- **GrLivArea**: Above-ground living area square feet.
  
For a detailed description, check: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques

## Project Steps

1. **Data Preprocessing**:
   - Handling missing values.
   - Encoding categorical variables.
   - Scaling numerical features.
   
2. **Feature Engineering**:
   - Filling missing values with appropriate substitutes.
   - Dropping columns with too many missing values.
   - Encoding categorical variables using **One-Hot Encoding** and **Ordinal Encoding**.

3. **Modeling**:
   - Various models like **Linear Regression**, **Random Forest**, and **XGBoost** were tested.
   - **Stacking Regressor** was used to improve accuracy.

4. **Evaluation**:
   - **Root Mean Squared Error (RMSE)** was the main metric used to evaluate model performance.

## Results

The **XGBoost** regressor provided the best results with the lowest RMSE. Key features influencing price were **Overall Quality**, **GrLivArea**, and **YearBuilt**.

## Acknowledgements

This project is based on the **Ames Housing Dataset** from Kaggle. Inspiration was taken from popular Kaggle notebooks, with additional improvements added.