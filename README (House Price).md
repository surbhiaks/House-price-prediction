# House Price Prediction
In this project there are number of factor which determine property price, based on transportation, location, property age, basic amenities nearby. 

The goal is to understand the relationship between house features and how these
variables affect the house price.


## Data Description 

•	Transaction Date : Date of transaction when the house was purchased.

•   House Age	     : Age of the house.

•   Distance from nearest Metro station (km) : Nearest Metro Station from the house/property.

•   Number of convenience stores	: Number of convenience store from the location.

•   latitude         : latitude of the house.

•   longitude        : longitude of the house.

•   Number of bedrooms	: Total number of bedrooms.

•   House size (sqft)	: Size of the house in Square Feet.

•   House price of unit area : Price of the house per unit.

## Evaluation Parameters 

Evaluation will be based on: 

•   Data Preprocessing

•	Model Comparison 

•	Model Selection 

## Tools Used

Jupyter Notebook

## Libraries Used
Pandas

Numpy

Matplotlib

Seaborn

## Roadmap To The Project

### Exploratory Data Analysis

I have performed bi-variate analysis with the help of pairplot to get the insight for each variable.

### Data Preprocessing

As I can see that there is O missing values in the data.

Removed Outliers by Z-Score Formula.

After this, I have Selected important Feature with the help of HeatMap.


### Model Comparison

Before building the model I have splited the data into train and test by the ratio of 70:30 and Scaled the data.

I have used different models(like Linear Regression, Random Forest Regressor, Ada-Boost Regressor) for building the models however Random-Forest-Regressor fit good in this data sets which is robust to the outliers and avoid the overfitting also gives the best accuracy as compared to others.

1) Random Forest Regressor	98.49.

2) AdaBoost Regressor Regressor	91.77

3) Linear Regression	91.38

I have also check the Mean Squared Error(MSE) and Root Mean Squared Error(RMSE) for each model to get the error which the model is giving.

### Model Selection

I have Selected Random Forest Regressor as a final model which is giving the highest R2 score i.e., 98.49

