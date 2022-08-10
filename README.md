# HOUSEPRICE_ESTIMATION
> Estimating sale price of houses in Australia using past housing sales data set.
  Finding the significant variables in predicting price of a house

BACKGROUND OF PROJECT
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at
 a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses
 in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

 The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.

BUSINESS GOAL:
You are required to model the price of houses with the available independent variables. This model will then be used by the management to 
understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will 
yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


Conclusions:
1. The optimal values of alpha for ridge and lasso are 3 and 0.0001 respectively
2. The significant variables in predicitng the price of house are
GrLivArea
OverallQual
TotalBsmtSF
OverallCond
GarageCars
1stFlrSF
2ndFlrSF
BsmtFinSF1
GarageArea and
BsmtUnfSF
LotArea
Neighborhood_StoneBr
These variables' coefficients are in the range 0.1-0.04

Among them strong co-relation varaibles with sales price are
1.GrLivArea -0.77
2.OverallQual-0.83
3.TotalBsmtSF-0.66
4.GarageCars-0.72
5.1stFlrSF-0.64
6.GarageArea-0.72

