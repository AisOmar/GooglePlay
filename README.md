# Exploring and Predicting Rating of Google Apps 

This dataset was scraped from Google Play Store and stored in Kaggle:

https://www.kaggle.com/lava18/google-play-store-apps




## Dataset and Attributes

The dataset includes 9360 apps and 14 features after final cleaning:

- App name

- Category

- Rating

- Reviews 

- Size

- Installs 

- Type

- Price 

- Content Rating 

- Current Ver

- Android Ver

- Year

- Month 

- Day

  
  

## Goal of the Project

I came up with five different business questions and my goal is answer them. Please find questions below:

- #### What quantitative feature is the most correlated to a rating of apps?

- #### What category has the highest amount of apps?

- #### What is the average rating of the apps in different categories?

- #### Can we predict the rating of apps based on the other features in the dataset?

- #### What are the most important features determining the rating of the apps?




## Prediction 

The target of prediction is a rating column. This is a regression model. I will be predicting continues variable. 

### Summary 

1. After trying out different models like: Linear Regression, XGBoost Regressor, Random Forest Regressor I was not able to get the ideal model. 
2. The highest r squared is 0.08, which means only 8% of the model is explained. 

#### The features of the model are not crucial to predict the rating of different apps. 


