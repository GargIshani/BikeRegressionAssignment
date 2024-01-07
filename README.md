# Project Name
> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
This assignment helps the company to identify below, 
 1. Which variables are significant in predicting the demand for shared bikes.
 2. How well those variables describe the bike demands


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
- Background of the project - 
   A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

- What is the business probem that your project is trying to solve?
   Boom Bikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

- What is the dataset that is being used?
   day.csv provided as part of the problem statement

## Conclusions
- yr: The coefficient for 'yr' is positive, suggesting an increase in 'cnt' over the years.
- workingday: The 'workingday' variable has a small positive effect on 'cnt'.
- temp: The 'temp' variable has a strong positive effect, indicating that higher temperatures are associated with higher 'cnt'.
- hum: The 'hum' variable has a negative effect on 'cnt', suggesting higher humidity levels correlate with lower 'cnt'.
- windspeed: Higher wind speeds are associated with lower 'cnt', as indicated by the negative coefficient.
- spring: Being in the spring season is associated with a lower 'cnt', as indicated by the negative coefficient.
- The presence of Light Snow, Light Rain + Thunderstorm + Scattered clouds, is associated with a significant decrease in 'cnt'.

## Technologies Used
- Numpy
- Pandas
- Matplotlib
- Seaborn
- SkLearn
- StatsModel

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@GargIshani] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
