# King county house prices prediction
## Overview
The aim of the project is to use multiple linear regression to predict the price of the property using the property features in KingCounty  
Real estate agents, Homeowners can predict sale price of the house and determine its value based on the property features
The data used is about properties in KingCounty region
The model used is the log-log model with dummy variables and continuous variable as the features of the house
The model shows how prices is affect by the square feet of living,square feet of the lot ,bedrooms ,floors, waterfront, view, condition, grade of the house

## Business understanding
Many features of a property affect their prices .We need to determine whether physical aspect of the property in King County region on how they ffect their prices of the .The main purpose is to predict salesprice of property based on its features.This information can be used by homeowners,real estate agents and real estate brokers to predict the price of the property based on its features .Homeowners in KingCounty can use it to assess the value of their property. 
## Data understanding
The data used is from kc_house_data.csv.The data shows the features of houses i.e bathrooms,bedrooms,their size and prices
## Modelling
The final model used is a log log multilinear regression model with the target as the log of price and the independent variable are the log of sqft of living and log of sqft of lot and contains the dummy variables of the bedroom columns,view,waterfront,grade and condition column.The model7 is linear,homoskedastic,independent and normally distributed.It passes all the assumptions of a linear regression.The independent variable chosen are what most peaople value in a house and its the house major features
## Regression results
An increase in square foot of living by one percent increase the price by 0.51%

An increase in square foot of lot by one percent reduces the price by 0.05%

The sale price of 1 bedroom,8 bedroom,2 bedroom house is higher than of a three bedroom house .

The sale price of 4 bedroom house is lesser than of a three bedroom house by 0.02%

he sale price of 1.5, 2.5 floors house is higher than of one floor house by 0.16%

The sale price of 2.0 floors house is less than of one floor house by 0.06%

The sale price of house with a waterfront is higher than a house with no waterfront by 0.37%


## Conclusion
For a realestate agent trying to purchase a house should consider that a house with a waterfront has a higher price than a house with no waterfront

For a homeowner to assess price of their home shold take into account the square feet living space,square feet of lot,Grade,Condition,bedrooms of the property

For a realestate agent trying to purchase a house should consider that a house with a no view has a lower price than a house with good,excellent,average views

For a homeowner trying to assess the value of their house the square feet of living space has a higher impact on price than the square feet of lot

The most sold houses have three bedrooms,showing a high demand in three bedroom houses

The most sold houses have one floor also showing a high demand in houses with one floor
