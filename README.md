# Project Name
> Build a Multiple Linear Regression model to predict demand of shared bikes.

## Table of Contents
* [Problem Statement](#problem-statment)
* [Objective](#Business-Objective)
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Libaries Used](#libaries-used)

## Problem Statement:
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 


## Conclusions
### Observations from the bar plots for categorical variables:
- Yearly distribution of Total number of Users indicates that more bikes are rent during 2019.
- Seasonal distribution of Total number of Users indicates that more bikes are rent during fall season.
- Distribution of Total number of Users across various seasonal changes indicates that more bikes are rent when weather is clear for both the years.
- More number of bikes were rented on Working days.
- More bikes are rent for the year 2018 in the month of June.
- More bikes are rent for the year 2019 in the September month.
### Variable ‘temp’(temperature) has the highest co-relation with the target variable ‘cnt’.
#### Following are the top 3 features contributing significantly towards explaining the demand of the shared bikes based upon their co-relation with target variable:
- temp
- Yr 2019
- Weather Light Snow

## Libaries Used
- numpy
- pandas
- matplotlib.pyplot 
- seaborn
- sklearn
- statsmodels.api
## Contact
Created by:
- Abhishekh Pareshkumar Shah [[https://github.com/abhi-alone]]