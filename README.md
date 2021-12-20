# python-api-challenge

For Part I - WeatherPy, a series of scatter plots were created to showcase the following relationships:
* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

After this, a linear regression was run on each relationship, separated into Northern Hemisphere and Southern Hemisphere, then this was plotted on top of the scatter plots.
For each relationship, the observations identified by the linear regression modeling were explored.

For Part II - VacationPy, the cities data from Part I was utilised with gmaps and Google Places API to obtain weather data to plan future vacations.
As part of this, a heatmap was created that displays the humidity for every city from Part I.
The DataFrame containing cities data was narrowed down to find ideal weather condition. Then the Google Places API was utilised to find the first hotel for each city located within 5000 meters of city coordinates.
These hotels were then plotted on top of the humidity heatmap.
