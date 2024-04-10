# Bike Sharing Assignment 
> BoomBikes, A US basedbike-sharing provider has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company aspires to understand the demand for shared bikes among the people in the American market after this ongoing quarantine situation ends across the nation due to Covid-19.

> The company wants to know:

> 1. Which variables are significant in predicting the demand for shared bikes.
> 2. How well those variables describe the bike demands

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.

- What is the background of your project?
  This is an assignment study taken as a part of AI&ML Jan 2024 batch IIIT-Bangalore

- What is the business probem that your project is trying to solve?
  Identifying the variables that help in predicting the demand for shared bikes

- What is the dataset that is being used?
  day.csv - This file contains data spanning two years (2018-2019), detailing the number of users renting bikes per day. Each day is characterized by various attributes such as working day, temperature, season and more. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The r2 is 79.6 on test set and on trian set it is 83.5 with lr_model. The difference is less than 5%
- Demand for the bikes depend on variables: temp, workingday, windspeed, year, September, Saturday, Summer, Winter, Mist, weathersit -3 (Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds)
- Further from EDA analysis: 
- Company should focus on expanding buisness in September
- Company can provide offers during weekends/holidays as the users count is high these days
- During Adverse weather conditions user count is too low, company can focus on vechile maintainence.
- Year by year the user count has increased, so this might give a clue that post pandamic situation can improve. So, company should be prepared to handle user needs accordingly.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas library - version 2.0.3
- numpy library - version 1.24.3
- matplotlib library - version 3.7.2
- seaborn library - version 0.12.2
- statsmodels library - version 0.14.0
- sklearn library - version 1.3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This Linear Regression assignment was taken as a part of AIML - Jan 2024 batch IIIT-Bangalore


## Contact
Created by [@smarunkumar] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->