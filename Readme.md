# Bike Sharing Linear Regression Assignment

## Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

## Business Goal:
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Data Dictionary:
The data dictionary can be found [here](./Readme.txt)

## Conclusion:

The variables which could help predict the bike sharing numbers with their coefficients are as follows:

| Variable                | Coefficient |
|-------------------------|-------------|
| const                   |    0.190855 |
| holiday                 |   -0.096316 |
| weathersit_Mist         |   -0.078741 |
| weathersit_LightFalls   |   -0.285031 |
| season_Winter           |    0.094476 |
| month_name_September    |    0.090998 |
| windspeed               |   -0.148098 |
| temp                    |    0.477737 |
| season_Summer           |    0.062076 |
| year                    |    0.234132 |
| season_Spring           |   -0.055406 |