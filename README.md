# LinearRegressionAssignment

This assignment is a programming assignment wherein you have to build a multiple linear regression model for the prediction of demand for shared bikes.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information
# Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

# Business Objective
* To understand the demand for shared bikes among the people after this ongoing quarantinesituation ends across the nation due to Covid-19.

* To understand the factors affecting the demand for these shared bikes in the American market.

* The company wants to know:
  <br> a. Which variables are significant in predicting the demand for shared bikes. <br> 
  b. How well those variables describe the bike demands.

* To model the demand for shared bikes with the available independent variables. It will be used by the management to 
  understand how exactly the demands vary with different features

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
* co-efficient of yr is 1.04(positive), it suggests the business is expanding with time ,So i would recommend
  you to continue to invest and promote the product.
* season_Winter has co-efficient of 0.34 (positive),it suggests that usage of bike is more during winters,So i would recommend you to have sufficient bikes for users and good customer service to keep the trust.
* in Nov,dec,jan & feb have negative co-efficients , it suggests that usage of bike is less in these months.
  it could be because of extreme low temperature , snow and not suitable weather to use the bike. So i would recommend you to plan accordingly as the demand will be less in these conditions.
* surprisingly season_Spring has negative co-efficient (-0.3760), there is scope for improvement in business during spring season. run compaign ,offer attractive discounts and promote the business.
* workingday has 0.19 co-efficient(positive), it suggests that usage of rental bikes is high during working days, may be the customers are using it for their work.
* atemp has 0.40 co-efficient (positive) which is significant, better feeling temperature encouraging customers to use rental bikes.
* hum and windspeed have negative co-efficient, customers are avoiding usage of rental bikes during conditions which are not suitable for riding.

## Technologies Used
* version pandas 1.5.3
* version matplotlib 3.7.2
* version seaborn 0.12.2
* version scikit-learn 1.3.0
* version statsmodels 0.14.0
* version numpy 1.24.4

## Contact
Created by [@BasavarajG26] - feel free to contact me!
