# What's the Weather Like?

## Part I - WeatherPy

"What's the weather like as we approach the equator?" - Visualizing the weather of 500+ cities across the world of varying distance from the equator using Python,  and the OpenWeatherMap API, to create a representative model of weather across world cities.

<img src="https://github.com/the-Coding-Boot-Camp-at-UT/UT-MCC-DATA-PT-01-2020-U-C/blob/master/homework-instructions/06-Python-APIs/Instructions/Images/equatorsign.png" alt="Global Weather">

### Scatter Plot visualizations

<img src="https://github.com/hrao-dev/python-API-Challenge/blob/master/WeatherPy/output_data/Lat_Cloud_Plot.png" alt="Latitude vs Cloudiness">
<img src="https://github.com/hrao-dev/python-API-Challenge/blob/master/WeatherPy/output_data/Lat_Humid_Plot.png" alt="Latitude vs Humidity">
<img src="https://github.com/hrao-dev/python-API-Challenge/blob/master/WeatherPy/output_data/Lat_Temp_Plot.png" alt="Latitude vs Temperature">
<img src="https://github.com/hrao-dev/python-API-Challenge/blob/master/WeatherPy/output_data/Lat_Wind_Plot.png" alt="Latitude vs WindSpeed">

## Part II - VacationPy 

Utilizing the weather data to plan future vacations.Jupyter-gmaps and the Google Places API are used to find cities from the WeatherPy notebook results that have the ideal weather for a vacation spot. Ideal weather conditions include:

  * A max temperature lower than 80 degrees but higher than 70.
  * Wind speed less than 10 mph.
  * Zero cloudiness.
  
 Using Google Places API,the first hotel for each city located within 5000 meters of the coordinates is found and plotted on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.
 
<img src="https://github.com/the-Coding-Boot-Camp-at-UT/UT-MCC-DATA-PT-01-2020-U-C/blob/master/homework-instructions/06-Python-APIs/Instructions/Images/hotel_map.png" alt="Heat Map with Hotels">


## Conclusions
Weather data was collected from several random cities around the world (Note: since the cities are generated randomly, the number of cities and their weather data will differ each time the script is run).

* As expected, the cities closer to the equator were observed to have higher maximum temperatures. In the northern hemisphere, temperature decreases in strongly linear fashion as we move north away from the equator. Cities in the southern hemisphere do not seem to experience the same rapid decrease in temperatures with latitude.

* For the cities considered, there seems to be little to no correlation between humidity and Latitude and with cloudiness and Latitude, as the scatter plots showed that cities with a similar latitude had a considerable diversity in the levels of humidity and cloudiness.

* Similarly, there seems to be almost no correlation between latitude and wind speed in the northern hemisphere whereas in the southern hemisphere wind speed seems to weakly correlate with latitude (i.e., wind speed seems to slightly increase as we move from the equator towards south pole). However, for a majority of the cities in both the northern and southern hemispheres, the wind speed seems to fall in the range of 0-15 mph.

