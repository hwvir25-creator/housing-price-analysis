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

# Focus on
1.  Which housing characteristics (factors) are most strongly associated with sale price?
2.  How accurately can a multiple linear regression model predict prices for new homes?
3.  How can the results support real-world housing decisions?


# Dataset

Source: AmesHousing
R package (De Cock, 2011) — 2,930 residential property sales in Ames, Iowa.
Response: Sale price (Box–Cox transformed, λ = 0.25).
Predictors: above-ground living area, total basement area, year built, garage capacity, overall quality (categorical), neighborhood (categorical)


# Result

- Adjusted R² ≈ 0.91
- Test R² ≈ 0.90

The final model explained approximately 91% of the variation in housing sale prices.

The results also show that square footage alone does not fully explain housing prices.  Two homes of a similar size may still have different values because of differences in condition, quality, garage space, and location.

# Implication
This model helps explain how features such as living area, overall quality, basement size, garage capacity, and neighborhood are related to house prices. Buyers can use the results to better understand price differences between similar homes, while sellers and real estate agents can use them as a starting point when evaluating a property. 

# PDFs :If the PDF preview shows an error, click the three-dot menu (`...`) in the upper right corner and select View raw or Download!

