# Exploring and Predicting Rating of Google Apps 

This dataset was scraped from Google Play Store and stored in Kaggle:

https://www.kaggle.com/lava18/google-play-store-apps


# Link to a medium article 

https://medium.com/@aisuluomar123/is-it-possible-to-predict-rating-of-google-play-store-apps-based-on-the-given-information-da9a44a3ac1e

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

The target of prediction is a rating column. This is a regression model. I will be predicting continuous variable. 

### Summary 

To predict rating, I tired different models like Linear Regression, Random Forest Regressor, and XGBoost Regressor models. After applying those models to my dataset, the best MSE and RMSE were produced by XGBoost Regressor.

The best iteration of XGBoost Regressor's MSE is 0.1984, and RMSE of 0.4455.



