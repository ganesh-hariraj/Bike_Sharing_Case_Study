# Project Name
>Boombikes Company require a Linear Regression Model to identify variables that are significant in predicting the demand for shared bikes and How well those variables describe the bike demands.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Boombikes is a bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free
- BoomBikes aspires to understand the demand for shared bikes among the people
- Required to model the demand for shared bikes with the available independent variables.
- Bike sharing details for year 2018 and 2019 is available for  data analysis



## Conclusions
- Linear Regression Model for Bike demand as follows
Bike Demand = 0.016755 + (0.569401 *temp) + (0.237103 * yr) - (0.073795 * holiday) - (0.187961 * windspeed) + (0.078003 * summer) + (0.092325 * Clear) + (0.120680 * winter) - (0.092325 * weekday) <br/>

where<br/>
    yr : year (0: 2018, 1:2019)<br/>
    holiday: yes (1) or no (0)<br/>
    windspeed: windspeed<br/>
    summer: if season is summer, yes (1) or no (0)<br/>
    winter: if season is winter, yes (1) or no (0)<br/>
    Clear: if weather is Clear, yes (1) or no (0)<br/>
    weekday: weekday, 0 to 6 <br/>
    temp:  temperature<br/>

Train Dataset R2 Score: 80% <br/>
Test predicted R2 Score: 78%

- During Holidays and during misty/cold weather - demand is low
- There is significant improvement in customer demand year after year




## Technologies Used
- Pandas version: 2.1.4
- Numpy version: 1.24.3
- Seaborn version: 0.13.2
- Matplotlib version: 3.8.0
- statsmodel version: 0.14.0
- The Scikit-Learn version is 1.1.3.



## Acknowledgements

- Upgrad Module 2 Linear Regression Assignment



## Contact
Created by [@ganesh-hariraj] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->