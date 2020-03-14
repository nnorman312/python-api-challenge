In this exercise, I address a fundamental question: "What's the weather like as we approach the equator?"

WeatherPy:
In this example, I create a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, I utilize a simple Python library, the OpenWeatherMap API, and a little common sense to create a representative model of weather across world cities.

First, I build a series of scatter plots to showcase the following relationships:

Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude

Next, I run linear regression on each relationship, only this time separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

Northern Hemisphere - Temperature (F) vs. Latitude
Southern Hemisphere - Temperature (F) vs. Latitude
Northern Hemisphere - Humidity (%) vs. Latitude
Southern Hemisphere - Humidity (%) vs. Latitude
Northern Hemisphere - Cloudiness (%) vs. Latitude
Southern Hemisphere - Cloudiness (%) vs. Latitude
Northern Hemisphere - Wind Speed (mph) vs. Latitude
Southern Hemisphere - Wind Speed (mph) vs. Latitude

In conclusion, I include a written description of three observable trends based on the data.

VacationPy: 
In this example, I work with weather data to plan future vacations. 

First, I create a heat map that displays the humidity for every city from WeatherPy above. Then, I narrow down the DataFrame to find my ideal weather condition. 

Using Google Places API, I find the first hotel for each city located within 5000 meters of my coordinates. Then I plot the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.
