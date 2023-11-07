# House-Price-Prediction-for-a-US-based-housing-company
Build a linear regression model to predict the actual value of the prospective properties and decide whether to invest in them or not.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.The company is looking at prospective properties to buy to enter the market. 
- The company wants to know: 1)Which variables are significant in predicting the price of a house, and 2)How well those variables describe the price of a house.
- Dataset consists of 81 columns


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Top 5 features impacting the price of a house are the ones with Excellent & Very Good Overall Quality,Excellent Overall Condition,Condition of sale as 'Allocation' and DUPLEX dwelling MSSubClass
- OverallQual_9_Excellent & OverallQual_8_VeryGood: if the overall material and finish of the house is Very Good or Excellent, the price of house will increase by 1.63 to 2 times
- OverallCond_9_Excellent: if the overallcondition of the house is Excellent, the price of house will increase by 1.67 times
- SaleCondition_Alloca: If condition of sale is allocation having condo with a garage unit,the price of house will increase by 1.65 times
- MSSubClass_90	: Dwelling subclass will negatively effect price
- Optimal value of lambda for Ridge Regression is 4
- Optimal value of lambda for Lasso regression is 0.001

Neighborhood_Crawfor: if Crawford is a nearby location, then the price of house will increase by 1.07 to 1.09 times
Functional_Typ: if the home functionality is typical, then the price of house will increase by 1.07 to 1.08 times
Exterior1st_BrkFace: if the exterior covering on the house is Brick Face, the price of house will increase by 1.07 to 1.08 times.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python
- GitHub
- Jupyter Notebook
- Python Libraries: - Python
- GitHub
- Jupyter Notebook
- Python Libraries: Pandas,Seaborn,Matplotlib,sklearn,statsmodelssklearn,statsmodels,pandas,numpy,matplotlib,seaborn,warnings


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

## Contact
Created by [@Trezajacob] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->