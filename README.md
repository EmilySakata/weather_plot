## Unit 6 | Assignment - What's the Weather Like?

As part of the weather_plot assignment, this WeatherPy.ipynb file will visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, the file utilizes a [simple Python library](https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api) to create a representative model of weather across world cities.

The exported markdown file of the Jupyter notebook is here: https://github.com/EmilySakata/weather_plot/tree/master/weather_plot/WeatherPy
Following 4 scatter plots were made to showcase the following relationship:

* Temperature (F) vs. Latitude
![temp_vs_lat](https://github.com/EmilySakata/weather_plot/blob/master/WeatherPy/output_5_0.png)

* Humidity (%) vs. Latitude
![humidity_vs_lat](https://github.com/EmilySakata/weather_plot/blob/master/WeatherPy/output_6_0.png)
* Cloudiness (%) vs. Latitude
![Cloudiness_vs_lat](https://github.com/EmilySakata/weather_plot/blob/master/WeatherPy/output_7_0.png)
* Wind Speed (mph) vs. Latitude
![wind_vs_lat](https://github.com/EmilySakata/weather_plot/blob/master/WeatherPy/output_8_0.png)


From the plot, following observations can be made:
1) The maximum tempreture is corrolated to the lattitude of the city. As the city lattitude is close to 0 (equator ) the maximum temperature increases, and the more farther away 

2) The maximum humidity does not depend on the lattitude of the city. Any city that has rain will have max 100 % humidity and hense there are more cities that have 100% humidity than others.

3) Intrestingly, the cities located between lattitude of -40  through -20 and 20 through 40 has 0 cloudiness more frequently than other cities. During this time, the windspeed between the same lattatide range has miled wind. This makes it beleive that because the wind is blowing, there is little cloud in the associated cities. 
