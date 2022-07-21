# World Weather Analysis

## Project Overview

For this project, I assisted my colleague Jack in analyzing weather data as part of the work that contributed to an app for helping travellers select vacation destinations. We created a database of cities from around the world and their weather profiles. From there, users could provide input about their desintation preferences and, utilizing Google Maps API, receive information about cities and hotels that met their criteria. Finally, we used Google Maps directions API to allow users to string together a trip including four destination cities.

## Weather Database

We utilized an API to retrieve weather for cities around the world, after generating random latitude/longitude pairs. For our cities, we included the following data points:

- Maximum temperature
- Cloudiness
- Wind Speed
- Humidity
- Current weather description

![image1](https://github.com/brianbutler08/World_Weather_Analysis/blob/main/DataFrame_Weather.png)

## Vacation Search

This step utilized Google Maps API to provide potential destination hotels to travellers. A potentiall user of the app is asked a question about minimum and maximum temperature ranges that they prefer and they are presented with a map featuring those destinations that fit the criteria. Markers contain alll of the pertinent weather information in addition to a hotel in the area.

![image2](https://github.com/brianbutler08/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

## Vacation Itinerary

As a final element to add to the developing app, we included a feature in which users could select a number of destinations and receive directions to link them together. In a Google Maps window, they are presented with the route(s) between destinations, with possible transporation modes of driving,, biking or walking.

![image3](https://github.com/brianbutler08/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)

## Additional Analysis

In addition to the app development work detailed above, we also created scatter plot charts for looking at how latitude correlates with our various weather data points - 

![image4](https://github.com/brianbutler08/World_Weather_Analysis/blob/main/weather_data/Fig1.png)

![image5](https://github.com/brianbutler08/World_Weather_Analysis/blob/main/weather_data/Fig2.png)

![image6](https://github.com/brianbutler08/World_Weather_Analysis/blob/main/weather_data/Fig3.png)

![image7](https://github.com/brianbutler08/World_Weather_Analysis/blob/main/weather_data/Fig4.png)
