# python-api-challenge
Create Python script to visualize the weather of over 500 cities of varying distances from the equator using OpenWeatherMap API

Challenge Details:
--------------------
This challenge has 2 files – WeatherPy and VacationPy

WeatherPy performs the following tasks:

•	Generate random geographic coordinates and the nearest city to each latitude and longitude and save it in a csv file.

•	Create plots to showcase the relationship between weather variables and latitude. 

•	Compute Linear regression for the relationships for northern and southern hemispheres seperately.

VacationPy performs the following tasks:

•	For each city saved in the csv file created by WeatherPy, find the first hotel located within 10,000 meters of its coordinates.

•	Create map visualizations of the cities using the Geoapify API and the geoViews Python library and show the hotel in hover text.

Libraries or APIs used:
--------------------------
OpenWeatherMap API - https://openweathermap.org/api 

Geoapify API - https://www.geoapify.com/

citypy Python Library - pip install citipy

geoviews, hvplot Python libraries - if not already installed, the following command can be used to install geoviews and hvplot.

conda install -c pyviz geoviews

conda install -c pyviz hvplot

