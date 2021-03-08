# DSI-Project-2
Project 2 (Ames Iowa house price prediction)

# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 2: Ames Housing Data and Kaggle Challenge

---
### Problem Statement

I work for the estate consultant who gives the recommendation about the house price. My customer is the estate company who want to invest in the housing market. The house demand growth expands every year in Iowa, therefore my customers want to know how to increase the house price and which features have high value of house.

---
### Executive Summary

There are many indicators to predict the house price. In Ames Iowa city, there are over 80 features to study the house price. The model is built and predict the price by using linear regression, Ridge and Lasso. The winner features that increase the value of house are the size of area including ground living area, garage area and basement area. Moreover, the overall quality and age of house also impact on sale price. The 5 things that should be avoid are the low quality of exterior, fireplace quality and central air. Also, the zone of house is an important factor because the house in Commercial and Residential Medium Density tends to have low price.

---
### Conclusions and Recommendations

**Model comparison**

- Model 1 : The accuracy is 84% on training data, but the model feature is needed to be adjusted and get more accuracy. The alphas of Ridge and Lasso are so high that means the model still has some error, this can be confirmed by RMSE which is around 31000.

- Model 2 : The accuracy is 90% on training data that higher than R-square on testing data. This might the model is overfitting. The alpha of lasso decreases from model 1. The increasing of features in this model can increase accuracy but also increase the overfit.

- Model 3: As the sale price distribution is not a normal distribution. The log transformation can help to adjust the distribution and get a better prediction result.

**Feature comparison**

- The size of the area is the main feature to increase the house price including ground living area, total basement area and area around the house.
- People love to buy a new house so the estate company should build a new house instead of renovating the old house.
- If the house owner and estate company would like to increase the house price but cannot expand the area, quality improvement is the best way for this problem such as exterior quality, basement exposure, kitchen quality, heating quality and adding the wood deck or porch.
- The zone that will decrease the house price is Commercial and Residential Medium Density, so the estate company should avoid investing in these zones. Moreover, the house with low quality of exterior, fireplace and central air tends to have a low price.

**Limitation of this model**

- This model is trained from the data in Ames Iowa, so this model cannot predict the house price in another city. 
- It requires some adjustment such as increasing the longitude and latitude or the environment around the house (school, hospital and park). This will help this model to be a universal model.

---
### Datasets

* [`train.csv`](./datasets/train.csv): Train data for machine learning model 
* [`test.csv`](./datasets/test.csv): Test data for machine learning model

---
### Data Dictionary

http://jse.amstat.org/v19n3/decock/DataDocumentation.txt


