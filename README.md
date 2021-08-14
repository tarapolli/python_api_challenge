# Python API project: What's the Weather Like?

What's the weather like as we approach the equator?
...
WeatherPy

In order to analyze the weather, I created a Python script utilizing an API from the openweathermap site. The script is used to visualize the weather of 500+ randomly-selected cities throughout the world, varying distance to the equator. Then I created scatter plots for each map explaining these variables:
•	Temperature (F) vs. Latitude
•	Humidity (%) vs. Latitude
•	Cloudiness (%) vs. Latitude
•	Wind Speed (mph) vs. Latitude

Next, I ran linear regression on each relationship outlined below. Please note the brief r-squared analysis after each pair of plots. 
•	Northern Hemisphere - Temperature (F) vs. Latitude
•	Southern Hemisphere - Temperature (F) vs. Latitude
•	Northern Hemisphere - Humidity (%) vs. Latitude
•	Southern Hemisphere - Humidity (%) vs. Latitude
•	Northern Hemisphere - Cloudiness (%) vs. Latitude
•	Southern Hemisphere - Cloudiness (%) vs. Latitude
•	Northern Hemisphere - Wind Speed (mph) vs. Latitude
•	Southern Hemisphere - Wind Speed (mph) vs. Latitude

Both the city data and maps were exported to folders for your review, and my observations written at the top of the WeatherPy Jupyter notebook. 

VacationPy

Using Google Places API, I created a heat map that displays the humidity for every city from WeatherPy. Then I narrowed down the DataFrame to find my ideal weather conditions to determine where I would like to visit. Again using the API, I found a hotel in each city within 5000 meters of the cities’ coordinates. Please note that 2 cities did not offer any hotels. These hotels are plotted on top of the humidity heatmap. 


