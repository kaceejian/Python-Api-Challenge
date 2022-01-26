# Python API Challenge - What's the Weather Like?

## Part I - WeatherPy

Create a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, utilized a [Simple Python Library](https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api), to create a representative model of weather across world cities.

---

### Steps:

First, create a series of scatter plots to showcase the following relationships:

- Temperature (F) vs. Latitude
- Humidity (%) vs. Latitude
- Cloudiness (%) vs. Latitude
- Wind Speed (mph) vs. Latitude

Secondly, run linear regression on each relationship, separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

- Northern Hemisphere - Temperature (F) vs. Latitude
- Southern Hemisphere - Temperature (F) vs. Latitude
- Northern Hemisphere - Humidity (%) vs. Latitude
- Southern Hemisphere - Humidity (%) vs. Latitude
- Northern Hemisphere - Cloudiness (%) vs. Latitude
- Southern Hemisphere - Cloudiness (%) vs. Latitude
- Northern Hemisphere - Wind Speed (mph) vs. Latitude
- Southern Hemisphere - Wind Speed (mph) vs. Latitude

---

## Part II - VacationPy

Work with weather data to plan future vacations. Use jupyter-gmaps and the Google Places API for this section.

### Steps:

- Create a heat map that displays the humidity for every city from the part I.

- Narrow down the DataFrame to find the ideal weather condition. For example:

  - A max temperature lower than 80 degrees but higher than 70.

  - Wind speed less than 10 mph.

  - Zero cloudiness.

  - Drop any rows that don't contain all three conditions. You want to be sure the weather is ideal.

- Use Google Places API to find the first hotel for each city located within 5000 meters of the coordinates.

- Plot the hotels on top of the humidity heatmap with each pin containing the **Hotel Name**, **City**, and **Country**.

---

## References:

- [OpenWeatherMap API](https://openweathermap.org/api)

- [Citipy Python Library](https://pypi.python.org/pypi/citipy)

- [Geographic Coordinate System](http://desktop.arcgis.com/en/arcmap/10.3/guide-books/map-projections/about-geographic-coordinate-systems.htm)

---

## Thank you!
