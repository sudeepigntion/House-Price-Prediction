# House Prediction With Ridge and Lasso Ression
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This task will predict using two models Ridge and Lasso Regression
- This will help business to determine which house to buy
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.
- We have a training dataset added with the code which have all features for the House and based on these features are needed to make selection for which property to buy

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- After running the models we came into conclusion that we can use Ridge over Lasso because it has better r^2
- These are the important predictive variables
LotArea------------- Lot size in square feet
OverallQual--------Rates the overall material and finish of the house
OverallCond-------Rates the overall condition of the house
YearBuilt-------- ---Original construction date
BsmtFinSF1-------Type 1 finished square feet
TotalBsmtSF------Total square feet of basement area
GrLivArea----------Above grade (ground) living area square feet
TotRmsAbvGrd---Total rooms above grade (does not include bathrooms)
Street_Pave-------Pave road access to property
RoofMatl_Metal--Roof material_Metal

- R^2 of Ridge and Lasso for Train and Test dataset
Ridge
R2 score(Train)--------- 0.88 ----------------------------0.88
Lasso
R2 score(Test)-----------0.87-----------------------------0.86

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas - version 1.4.3
- Numpy - version 1.23.2
- Sklearn - version 1.1.2
- Seaborn - version 0.11.2
- Matplotlib - version 3.5.3

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by Upgrad Tutorials
- Refrerences - Kaggle, Sklearn Documentation

## Contact
Created by [@sudeepignition] - feel free to contact me!
