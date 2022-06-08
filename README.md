# Bike Sharing Assignment
> This assignment builds a multiple linear regression model for the prediction of demand for shared bikes.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
#### Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

#### Business Goal:
This assignment model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

#### Dataset
The Bike Sharing dataset is  day.csv and Data dictionary is readme.txt.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The feature 'atemp' year '2019', 'windspeed' and 'spring' has highest influence on the Bike Sharing.
- The feature 'atemp' year '2019' has positive correlation and  the feature 'windspeed' & 'spring' has negative correlation.
- The model explains 77 % of the variance in Bike share can be explained by the model, which is a good number.
- The Residual Analysis show the the ditribution is normal and centered around zero.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas - version 1.3.4
- matplotlib - version 3.4.3
- seaborn - version 0.11.2
- sklearn - version 0.24.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@bijupv] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->