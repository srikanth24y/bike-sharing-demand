# Linear Regression Model for Bike Sharing demand Prediction and Inferences

A US bike-sharing company has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

The company wants to know:

* Which variables are significant in predicting the demand for shared bikes
* How well those variables describe the bike demands
     
## Table of Contents
* [Business Goal](#business-goal)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## Business Goal
It is required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Conclusions
- Top 3 features which influence the bike bookings are
	Temperature (temp)
	Weather (Weathersit = light rain or snow)
	Year
- A unit increase in temperature, increases the bike bookings by 0.5155 units
- A unit increase in weathersit (Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds) decreases the bookings by 0.2863 units
- A unit increase in year, increases the bike bookings by 0.2348 units
- Equation for Bike booking cnt can be expressed: cnt = 0.2342 + (0.3884temp) - (0.2932light_rain_or_snow) + (0.2366yr) - (0.1472windspeed) - (0.1067spring) - (0.0777misty) + (0.0662sep) + (0.0662sat) + (0.0556workingday) - (0.0504jan) + (0.0416*winter)           

## Technologies Used
- numpy - version 1.21.6
- matplotlib - version 3.2.2
- seaborn - version 0.11.2
- statsmodels - version 0.10.2
- sklearn - version 1.0.2

## Contact
Created by [@srikanth24y] - feel free to contact me!
