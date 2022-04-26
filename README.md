# World_Weather_Analysis

## Purpose

- The purpose of this analysis is to use openweathermap.org and google API's to import weather and location data in order to plot potential vacation spots based on a range of desired temperatures.

## Summary

- Using the random() function in python3, 2000 random data points that corresponded to latitude and longitudes were found.  The citipy module was used to find the closest city to these 2000 points.  Using the openweathermap.org API, city name, country code, location, maximum temperature, humidity %, cloudiness %, wind speed, and weather description were added to a pandas DataFrame.
 The DataFrame was used in conjunction with the GoogleMaps API to determine the hotel to each data point and this data was added to a new DataFrame. The new DataFrame was displayed using the gmaps.figure function to provide an interactive map that shows the cities and hotels with a marker that displays "Hotel Name", "City", "Country", and "Current Weather".
 The final step of the analysis was to use the Google Directions API in order to map out a route of 4 cities that were chosen to be the vacation route.  This also produced an interactive map with the same markers as above to show the vacation itinerary. 

## Results

 The results of this analysis were 2 functional, interactive maps that show cities around the globe and their weather conditions.