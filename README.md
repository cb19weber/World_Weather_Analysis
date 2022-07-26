# World_Weather_Analysis

## Overview of Project
Module 6 of DU's Data Analytics bootcamp introduced using API's and parsing JSONs to collect and analyze data. The ability to utilize this kind of data gathering technique opens up the world of data to our programming and analysis toolbox. I will explore the data collected below and provide analysis and visualization to bring the story to life and hopefully provide some meaning to users of this information. The underlying code is written in Python and utilizes Pandas and NumPy libraries, an online weather API, and the CityPy module.

### Purpose
What if consumers could add a greater sense of adventure to their vacations? What if instead of trying to go through the tremendous amount of data regarding travel destinations all over the world, they could instead answer a few simple questions and be given potential dream travel destinations? That's the purpose of this week's module, to create an interactive application to suggest travel destinations based on user preferences.

## Analysis and Challenges

### Analysis of Weather Data Based on Module
The bulk of the guided module sought to establish suggested travel destinations based on user weather preferences and geographical weather data. The initial exploration gathered data from OpenWeather, collecting city data for maximum temperatures, cloudiness, wind speeds, and relative humidity. This data was then organized to produce several visualizations. The graphical information and associated regression analysis demonstrated the relationships between city geographicl location and general weather. While some relationships seems correlated (see city latitude vs temperatures below), other relationships did not seem to be purely effected by location (e.g. humidity, wind speed, cloudiness). The r-value of the regression analysis demonstrates the level of correlation of the independent variable (geographical location) to the various dependent variables.
<TABLE align="center" CELLSPACING="20">
<TR>
<TD><p align="center">
    <img src="https://github.com/cb19weber/World_Weather_Analysis/blob/main/weather_data/Fig5.png" />
    </p></TD>
<TD><p align="center">
    <img src="https://github.com/cb19weber/World_Weather_Analysis/blob/main/weather_data/Fig1.png" />
    </p></TD>
<TD><p align="center">
    <img src="https://github.com/cb19weber/World_Weather_Analysis/blob/main/weather_data/Fig6.png" />
    </p></TD>
</TR>
</TABLE>
The fact that none of the dependent variables had a true linear relationship with latitudinal location is due to the existance of other forces that combine to determine weather in any particular location. The r-value of latitude relationship to the variables simply tells us how much of an impact geographical location has on the other variables. This data tells us that as far as humidity, cloudiness, and wind speed are generally caused by other more impactful forces.

Temperature does seem to be more impacted by the distance a particular location is from the equator, but with some interesting and necessary discussion. It was noticable that the r-value for the temperature versus location relationship in the northern hemisphere was significantly lower than in the southern hemisphere. This begs the question as to why? There are numerous hypothesis that could be explored with additional research.

The summary of the story for this current exploration into the data is that temperature preferences for travel experiences should at least in part take into consideration geographical location, with warmer temperatures occuring closer to the equator and cooler temperatures extending closer to the poles (which is not surprising, but is supported by the data.)

### Analysis of Weather Data Based on Challenge
The challenge portion of the module attempted to expand the dataset for the JSON pull from OpenWeather to include 25% more locations in the hopes for a larger population of cities. This not only expands consumer choice, but also provides a larger dataset for analysis. With a larger dataset, the r-values for the northern and southern relationships remained similar, with latitudinal location being approximately 29% more impactful in the southern hemisphere than in the north.

The interactive graph, allowing potential consumers to view city, weather, and hotel information on the map allows for some immersion into the travel choices. This was a great addition to the application and has great potential with the final offering of the app.
<p align="center">
  <img src="https://github.com/cb19weber/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png" />
</p>

qwerty, qwerty

### Challenges and Difficulties Encountered


## Results
