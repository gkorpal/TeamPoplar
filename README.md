# Predicting Housing Prices in Ames, Iowa 
This is Team Poplar's final project for the data science bootcamp organized by the Erdos Institute. The team members are Michael Annunziata, Gaurish Korpal, Bartosz Langowski, Abraham Rabinowitz

## Problem Description
The aim of this project is to accurately predict and explain the features that have the greatest impact on the sale price of houses in Ames, Iowa. We can help sellers understand what features of a house provide the greatest impact on value, and buyers attain a fair price and budget toward a home purchase. Our key performance indicators are the root-mean-squared error (RMSE) of our predictions, as well as the mean absolute error (MAE). Our main KPI is RMSE, as it is more sensitive to inaccurate predictions. We also aim for an interpretable model to understand how the house is priced.

We will be working with the Ames, Iowa housing prices dataset provided by the Kaggle Competition [House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)

## Repository Description
- The folder marked 'Data' holds files giving a detailed description of the features and the meaning of their values. In addition it comes with a training set on which we will train our statistical models as well as a test set with unlabeled prices on which we will demonstrate our model's accuracy on unseen data. The sample submission file contains predictions on the test set with a baseline linear model as provided by Kaggle

- The folder titled 'Modeling Notebooks' has 3 key Jupyter notebooks
  - 'Exploratory Data Analysis' consists of the exploratory data analysis and graphs we used to develop a modeling strategy
  - 'Linear Regression' compares and contrasts the performance of severeal regularized and unregularized linear models.
  - 'Model Training and Interpretation' compares linear models, boosted trees and ensembled models. It also explains how we use the SHAP package to interpret our final chosen models predictions.
  
## Acknowledgments
First and foremost we would like to thank Anna Willman for helpful discussions as well as bringing the SHAP package to our attention. We would also like to thank the Erdos Institute as a whole for a wonderful data science semester. 
