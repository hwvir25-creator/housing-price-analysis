# Housing Price Analysis Using Multiple Linear Regression

#  Project Overview

This project investigates the relationship between housing characteristics and residential sale prices using the Ames Housing dataset. Multiple linear regression was used to identify important predictors of housing prices and evaluate model performance.

The analysis includes:

- Data cleaning and preprocessing
- Exploratory data analysis 
- Multiple linear regression modeling
- Assumption checking and diagnostic analysis
- Box-Cox response transformation
- Multicollinearity assessment using VIF
- Influential observation detection using Cook's distance
- Model validation with training-test split
- Prediction evaluation on both the transformed and original sale price scales

# Dataset

Source: AmesHousing
R package (De Cock, 2011) — 2,930 residential property sales in Ames, Iowa.
Response: Sale price (Box–Cox transformed, λ = 0.25).
Predictors: above-ground living area, total basement area, year built, garage capacity, overall quality (categorical), neighborhood (categorical)


# Result

- Adjusted R² ≈ 0.91
- Test R² ≈ 0.90

The final model explained approximately 91% of the variation in housing sale prices.
