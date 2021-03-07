# DSI-Project-2
# DSI_Project_1
Project 1 (SAT and ACT analysis)

# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 2: Ames Housing Data and Kaggle Challenge

---
### Problem Statement

I work for the estate consultant who gives the recommendation about the house price. My customer is the estate company who want to invest in the housing market. The house demand growth expands every year in Iowa, therefore my customers want to know how to increase the house price and which features have high value of house.

---
### Executive Summary


---
### Conclusions and Recommendations

**Model comparation**

- Model 1 : The accuracy is 84% on training data, but the model feature are needed to be adjust and get more accuracy. The alphas of Ridge and Lasso are so high that means the model still has some error, this can be confirm by RMSE which is around 31000.

- Model 2 : The accuracy is 90% on training data that higher than R-square on testing data. This might the model is overfit. The alpha of lasso decreases from model 1. The incresing of features in thid model can increase accuracy but also increase the overfit.

- Model 3: As the sale price distribution is not normal dirtribution. The log transformation can help to adjust the distribution and get the better prediction result.

**Feature comparasion**

- The size of area is the main feature to increase the house price including ground living area, total basement area and area around the house.
- People love to buy a new house so the estate company should build the new house instread of renovate the old house.
- If the houseowner and estate company would like to increase the house price but cannot expand the area, the quality  improvement is the best way for this problem such as exterior quality, basement exposure, kitchen quality, heating quality and adding the wood deck or porch.
- The zone that will decrease the house price is Commercial and Residential Medium Density, so the estate company should avoid to invest in these zones. Moreover, the house with low quality of exterior, fireplace and central air tends to have low price.

**Limitation of this model**

- This model is trained from the data in Ames Iowa, so this model cannot predict the house price in other city. 
- It requires some adjustment such as increasing the longitude and latitude or the environment around the house (school, hospital and park). This will help this model to be univeral model.

---
### Datasets

* [`train.csv`](./data/train.csv): Train data for machine learning model 
* [`test.csv`](./data/test.csv): Test data for machine learning model

---
### Data Dictionary

http://jse.amstat.org/v19n3/decock/DataDocumentation.txt


