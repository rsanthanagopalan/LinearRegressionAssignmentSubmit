# LinearRegressionAssignmentSubmit
> Problem Statement:
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system. A US bike-sharing provider has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.In such an attempt, they aspire to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits. They wantto understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
a) Which variables are significant in predicting the demand for shared bikes.
b) How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

## Table of Contents
* [General Info](#general-information) 
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
> Goal: 
Model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Conclusions
> Analysis: 
- Categorical variables of interest in the dataset - Month, Season, Holiday, Weather Situation, Weekday, Working Day
- Continous variables of interest in the dataset - Temperature, Adjusted temperature aka Feels Like, Humidity and Windspeed
- Target variable - Cnt which is the sum of Casual and Registered bikers
- No missing values found in the dataset
- Scaling techniques applied to normalize the continous variables
> Proposal: 
- The target variable has a linear relationship with key independent variables and the relationship is expressed as below,
- Temperature (temp): A coefficient value of "0.53" indicating that a unit increase in temperature results in the bike demand to grow by "0.53" units 
- Year (yr): A coefficient value of "0.23" indicating that a unit increase in year results in the bike demand to grow by "0.23" units 
- Weather Situation 3 (weathersit_3): A coefficient value of "-0.22" indicating that a unit increase in weather_sit3 results in bike demand to decrease by "0.22" units
 

## Technologies Used
- Pandas
- Seaborn
- Matplotlib
- SKLearn
- Statsmodels

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by upGrad course in Linear Regression
- This project was based on [Linear Regression](https://www.upgrad.com).


## Contact
Created by [@rsanthanagopalan] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
