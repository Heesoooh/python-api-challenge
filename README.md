# python-api-challenge

## Purpose of Project
In this homework assignment, you’ll apply what you've learned on Python requests, API, and JSON to a real-world situation and dataset
which to answer "What's the weather like as we approach the equator?" and show proves.
This assignment is applying concepts that I learned in python API to tell better story with graph by pulling data using api sites and api keys.

### WeatherPy
In this challenge, you'll create a Python script to visualize the weather of 500+ cities of varying distance from the equator. To do so, you'll use a simple Python library, the OpenWeatherMap API, and your problem-solving skills to create a representative model of weather across cities.

1. The first requirement is to create a series of scatter plots to showcase the following relationships:
* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

After each plot, add a sentence or two explaining what the code is analyzing.

2. The second requirement is to compute the linear regression for each relationship. This time, separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):
* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

After each pair of plots, explain what the linear regression is modeling. For example, describe any relationships that you notice and any other findings you may have.
Your final notebook must:
* Randomly select at least 500 unique (non-repeated) cities based on latitude and longitude.
* Perform a weather check on each of the cities using a series of successive API calls.
* Include a print log of each city as it's being processed, with the city number and city name.
* Save a CSV of all retrieved data and a PNG image for each scatter plot.

### VacationPy
In this challenge, use Jupyter-gmaps and the Google Places API for this part of the assignment.
* To complete this part of the assignment, you will need to do the following:
    * Create a heat map that displays the humidity for every city from Part 1
* Narrow down the DataFrame to find your ideal weather condition. For example:
    * A max temperature lower than 80 degrees but higher than 70.
    * Wind speed less than 10 mph.
    * Zero cloudiness.
    * Drop any rows that don't satisfy all three conditions. You want to be sure the weather is ideal.
* Use Google Places API to find the first hotel for each city located within 5,000 meters of your coordinates.
* Plot the hotels on top of the humidity heatmap, with each pin containing the Hotel Name, City, and Country  

## Analysis 
By analyzing the report, followings found:
1. Cities closest to latitude 0 shows higher temperature than cities that are nearby latitdue -90 and 90.

2. From the linear regression, cloudiness, humidity and wind speed have weak relationship with latitude.

3. Due to sun and rotation of earth and calendar date (currently in July in US), northern hemisphere temeperature is higher than southern hemisphere.
## Recommandation 
From this challenge and analysis, I can prove that cities near latitude 0 has the highest temperature. This founding can be present to different companies that are looking for weather details on the latitude cities.   