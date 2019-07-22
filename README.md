# WeatherPyHW

## Background
This module attempts to answer the question: "What's the weather like as we approach the equator?" 
by creating a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. 

## Approach
This module randomly selects over 500 unique cities based on latitude and longitude using citipy 
and then performs a weather check on each of the cities using a series of successive API calls to 
[OpenWeatherMap API](https://openweathermap.org/api).
A print log of each city is created as it's being processed with the record number and city name.
A series of scatter plots are created showing the following relationships:
Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude
