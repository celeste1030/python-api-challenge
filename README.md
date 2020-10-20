# python-api-challenge

![rainbowclouds](https://github.com/celeste1030/python-api-challenge/blob/main/extras/rainbowweather.jpg)

 Part I - WeatherPy

In Part I, I used a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, I used a [simple Python library](https://pypi.python.org/pypi/citipy), and the [OpenWeatherMap API](https://openweathermap.org/api) to create a representative model of weather across world cities.

Your first requirement is to create a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

Next I ran linear regression on each relationship, only this time separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):


* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude


![beachy](https://github.com/celeste1030/python-api-challenge/blob/main/extras/beach%20scene.jpg)

Part II - VacationPy

For Part II, I used the information found in WeatherPy to determine the ideal destination for a vacation.  By narrowing down ideal temperature, cloudiness and wind speed I was able to plot a heat map with hotel information for locations that matched my dream vacation requirements.



