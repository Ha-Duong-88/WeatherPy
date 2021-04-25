# World Weather Analyis for Vacation Travel Planning 

## Project Background
PlanMyTrip is a technology company specializing in internet related services in the hotel and lodging industry. The PlanMyTrip application helps travelers plan their international travel. This project collected and presented extensive data via the search page. Travelers can filter the search page based on their preferred travel criteria in order to find their ideal hotel(s) anywhere in theh world. 

## Scope
The scope of this project involves using Jupyter Notebook and citipy module to find over 500 random latitudes and longitudes, and perform requests on the OpenWeatherAPI to retrieve the JSON weather data from these cities. The weather data will be added to a Pandas DataFrame where we will use Matplotlib to create a series of scatter plots to show the relationships between latitudes and a variety of weather parameters for over 500 cities around the world.

As part of this analysis, statistical analysis was performed on the data using linear regression on the weather parameters in the Northern and Southern Hemisphere.
This data will help the PlanMyTrip team predict best time of year for people to plan their vacation and provide this information through the search engine for travelers using their application to plan their ideal trip.

Finally, the data was exported and cleaned, and weather data was used to choose the best cities for vacation based on certain weather criteria. These cities were mapped using Google Maps and Directions APIs.

## Objectives
The objective of the project was to enhance the existing PlanMyTrip app to provide weather description to the weather data retrieved from the OpenWeather API and provide travelers the ability to filter the data for their weather preferences. Travelers can use the weather parameters to set their preferences in order to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, travelers will be able to choose four cities. The PlanMyTravel app will create a travel itinerary. Using the Google Maps Directions API, PlanMyTravel app will create a travel route between the four cities and display it in the direction and marker layer maps.


# Summary 
The following illustrates an example of a travel itinerary based on the search criteria for weather conditions entered by travelers. 

## Weather Condition Search Parameters
   ### What is the minimum temperature you would like for your trip? 70
   ### What is the maximum temperature you would like for your trip? 90

## Results of Search Criteria

![image](https://user-images.githubusercontent.com/80140082/116012545-e8fb3780-a5df-11eb-8bde-cda1be5ac692.png)


<img width="1273" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/80140082/116012391-0da2df80-a5df-11eb-88e3-3368cbed85f1.png">

<img width="827" alt="WeatherPy_travel_map_markers" src="https://user-images.githubusercontent.com/80140082/116012401-198ea180-a5df-11eb-943f-e60a98675211.png">

<img width="752" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/80140082/116012409-227f7300-a5df-11eb-8e92-a8d9185d5d0d.png">

