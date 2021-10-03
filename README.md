# World_Weather_Analysis

## Overwiew

The purpose of the following project was to assist a travel site by providing weather information for locations around the globe in order to help travellers make decisions on vacation plans arrording to the weather. The project is broken into three parts which can be found in the Weather Database folder, the Vacation Search folder and the Vacation Itinerary Folder. 

## Weather Database

In this section, pandas and numpy were used in order to generate latitude and longitude coordinates around the globe. Next citipy was used to attach the nearest cites to these coordinates. Next, data from the weather API was brought in to find the Max temperature, humidity percentages, cloudiness percentage, wind speed and current weather description for each city. All of this data can be found in Weather_Database/cities.csv

## Vacation Search
In vacation search, we used the cities data from cities.csv, and asked what temperature range the traveller would like to experience on their trip. A new dataframe was created for citites that have a low temperature of 60 F and a high of 75. From here, google maps was used to find the nearest hotel to the preferred cities. A map was then created so the customer could see the hotel name, city, country, currect weather description and Max temperature for their potential locations, as seen in the image Vacation_Search/WeatherPy_vacation_map.png

## Vacation Itinerary

Lastly, once the traveller chpse their destination, google maps was used to show them the best route for a round trip on their upcoming roadtrip (the travellers dicided driving would be the most fun for them.) Our maps showed them the optimal route to take, and when hovering over thir upcoming destination in our map there were able to view the hotel name, city, country and current weather desciprion. 

Vacation_Itinerary/WeatherPy_travel_map.png

Vacation_Itinerary/WeatherPy_travel_map_markers.png