# Python API Challenge - What's the Weather Like?

[This repository](https://github.com/anulkar/python-api-challenge) contains two Juypter Notebooks as follows:
* [WeatherPy](https://github.com/anulkar/python-api-challenge/blob/master/WeatherPy/WeatherPy.ipynb): Analyze and visualizes weather data of 500+ cities picked randomly from across the world, of varying distance from the equator. It utilizes simple Python libraries along with the [OpenWeatherMap API](https://openweathermap.org/api) to create a representative model of weather across world cities. We primarily explore relationships between a city's Latitude vs the current day's Maximum Temperature, Cloud Coverage, Humidity and Wind Speed. Refer to the various plots and markdown cells in the notebook directly, to read the observations, trends and analysis.  
* [VacationPy](https://github.com/anulkar/python-api-challenge/blob/master/VacationPy/VacationPy.ipynb): Analyzes weather data of the 500+ cities to help with planning future vacations! We use [jupyter-gmaps](https://jupyter-gmaps.readthedocs.io/) and the [Google Places API](https://developers.google.com/places/web-service/intro) to create a heat map that displays the humidity for every city that we gathered weather data for. We then narrow down the list of cities based on ideal weather conditions for vacation planning purposes and then use the Places API to find the first hotel for each city located within 5000 meters of the city's geo-coordinates. Lastly, we plot the hotels on top of the humidity heatmap with each pin containing the **Hotel Name**, **City**, and **Country**.