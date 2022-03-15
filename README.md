# Linear Regression Model for Bike Sharing System
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

The company wants to know:
Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Develop a model to find the variables which are significant the demand for shared bikes with the available independent variables
- It will be used by the management to understand and manipulate the business strategy to meet the demand levels and meet the customer's expectations.
- Further, the model will be a good way for management to understand the demand dynamics of a new market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- As per above analysis of the categorical variables from the dataset
  * The season box indicates that more bikes rented during fall season
  * The year 2019 indicates that more bikes rented
  * The working day & holiday box indicate that more bikes rented during normal working days than on weekends or holidays.
  * The weathersit box plots indicates that more bikes are rent during Clear Sky days
- By looking at the pair plot 'temp' variable has the highest (0.84) correlation with target variable 'cnt'
- Significant variables to predict the demand for shared bikes¶
  * temp
  * yr_2019
  * Season(Spring,Summer,Winter)
  * months(September, July)
  * weathersit( Light Snow, Mist Cloudy)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python Library
  * pandas 
  * numpy
  * matplotlib
  * seaborn 
  * sklearn
  * statsmodels
- ML algorithm
  * RFE (Recursive feature elimination)

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Linear Model building assignments
- References https://github.com/ContentUpgrad/Linear-Regression

## Contact
Created by [@smardev] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
