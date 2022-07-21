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

## Vacation Search

This step utilized Google Maps API to provide potential destination hotels to travellers. A potentiall user of the app is asked a question about minimum and maximum temperature ranges that they prefer and they are presented with a map featuring those destinations that fit the criteria. Markers contain alll of the pertinent weather information in addition to a hotel in the area.

## Vacation Itinerary

As a final element to add to the developing app, we included a feature in which users could select a number of destinations and receive directions to link them together. 

