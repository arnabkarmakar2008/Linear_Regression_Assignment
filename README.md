# Bike Sharing(BoomBikes) Demand Analysis 
> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market.

## Table of Contents
* [General Information](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Contact](#contact)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- We need to model the demand for shared bikes with the available independent veraibles in the dataset provided. It will be used by the management to understand how exactly the demands vary with different variables. They specifically want to know :
    - Which variables are significant in predecting the demands
    - How well those variables describe the bike demands

- Given dataset contains bike demand for year 2018 and 2019 with other variables like weather condition, days of the week, season etc. We have to do data analysis and apply linear regression to come up with the model.
- Data can be downloaded from :: https://ml-course2-upgrad.s3.amazonaws.com/Linear+Regression+Assignment/Bike+Sharing+Assignment/day.csv

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Driving factors for demand:
- Temperature : Booking increase in higher temperature
- Year : Significant demand increase from year 2018 to 2019
- Weather(Light rain or snow) : Demand decreses in light rain or snow condition
- Windspeed : Demand decreses in higher windspeed
- Season(Spring) : Seen lower demand during Spring

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
Used python 3 along with follow libraries
- pandas
- numpy
- matplotlib
- seaborn
- statsmodels
- sklearn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [Arnab Karmakar](https://github.com/arnabkarmakar2008)


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
