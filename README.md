# python-api-challenge

![rainbowclouds](https://github.com/celeste1030/python-api-challenge/blob/main/extras/rainbowweather.jpg)

 Part I - WeatherPy

In Part I, I used a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, I used a [simple Python library](https://pypi.python.org/pypi/citipy), and the [OpenWeatherMap API](https://openweathermap.org/api) to create a representative model of weather across world cities.

Your first requirement is to create a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
![temp](https://github.com/celeste1030/python-api-challenge/blob/main/Images/LatitudeVsMaxTemp.png)
* Humidity (%) vs. Latitude
![humidity](https://github.com/celeste1030/python-api-challenge/blob/main/Images/LatitudeVsHumidity.png)
* Cloudiness (%) vs. Latitude
![cloud](https://github.com/celeste1030/python-api-challenge/blob/main/Images/LatitudeVsCloudiness.png)
* Wind Speed (mph) vs. Latitude
![wind](https://github.com/celeste1030/python-api-challenge/blob/main/Images/LatitudeVsWindSpeed.png)

Next I ran linear regression on each relationship, only this time separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):


* Northern Hemisphere - Temperature (F) vs. Latitude
![ntemp](https://github.com/celeste1030/python-api-challenge/blob/main/Images/NorthLatitudeVsMaxTemp.png)
* Southern Hemisphere - Temperature (F) vs. Latitude
![stemp](https://github.com/celeste1030/python-api-challenge/blob/main/Images/SouthLatitudeVsMaxTemp.png)
* Northern Hemisphere - Humidity (%) vs. Latitude
![nhum](https://github.com/celeste1030/python-api-challenge/blob/main/Images/NorthLatitudeVsHumidity.png)
* Southern Hemisphere - Humidity (%) vs. Latitude
![shum](https://github.com/celeste1030/python-api-challenge/blob/main/Images/SouthLatitudeVsHumidity.png)
* Northern Hemisphere - Cloudiness (%) vs. Latitude
![ncloud](https://github.com/celeste1030/python-api-challenge/blob/main/Images/NorthLatitudeVsCloudiness.png)
* Southern Hemisphere - Cloudiness (%) vs. Latitude
![scloud](https://github.com/celeste1030/python-api-challenge/blob/main/Images/SouthLatitudeVsCloudiness.png)
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
![nwind](https://github.com/celeste1030/python-api-challenge/blob/main/Images/NorthLatitudeVsWindSpeed.png)
* Southern Hemisphere - Wind Speed (mph) vs. Latitude
![swind](https://github.com/celeste1030/python-api-challenge/blob/main/Images/SouthLatitudeVsWindSpeed.png)

![beachy](https://github.com/celeste1030/python-api-challenge/blob/main/extras/beach%20scene.jpg)

Part II - VacationPy

For Part II, I used the information found in WeatherPy to determine the ideal destination for a vacation.  By narrowing down ideal temperature, cloudiness and wind speed I was able to plot a heat map with hotel information for locations that matched my dream vacation requirements.



