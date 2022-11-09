# Bike Sharing Demand Prediction using Linear Regression
A US bike-sharing provider BoomBikes wants to understand the demand for shared bikes. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

## Conclusions
- The demand of bikes is highly influenced by feeling temperature ("atemp") variable. People tend to rent bikes when the temperature is on the higher side.
- Since the demand for the bikes has increased naturally over time, we could see the influence of year ("yr") variable on the target variable. This shows that, the demand for bikes would increase even if the company does nothing new provided if all the other factors remain the same.
- The demand of bikes is slightly increased in the winter and summer season.
- Misty and snowy weather conditions reduces the demand for bikes.
- Higher windspeed reduces the demand for bikes.
- Interestingly, if the day is a holiday, the demand for bike reduces slightly.

## Technologies Used
- pandas - version 1.1.5
- seaborn - version 0.11.0
- matplotlib - version 3.5.3
- numpy - version 1.18.5
- statsmodels - version 0.13.5
- scikit-learn - version 0.23.1
