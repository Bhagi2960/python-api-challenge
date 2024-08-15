***WeatherPy and VacationPy****

1)The purpose of the WeatherPy project is to visualize the weather of over 500 cities of varying distances from the equator to analyze the relationship between weather and latitiude.

*The purpose of the first part of the project is to create a Python script to visualize the weather of over 500 cities of varying distances from the equator. The citipy Python library and the OpenWeatherMap API were used for this purpose.

*The code generates random geographic coordinates and the nearest city to each latitude and longitude combination.


*The OpenWeatherMap API was used to retrieve weather data from the cities list generated in the code, followed by a series of scatter plots created to showcase the following relationships:

Latitude vs. Temperature

Latitude vs. Humidity

Latitude vs. Cloudiness

Latitude vs. Wind Speed


*Computed Linear Regression for Each Relationship above.


*Plots were seperated into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). 



2)The second part of the project is to plan a vacation according to preferred weather and find the nearest hotel to the city.

***VacationPy****
In this deliverable, I am using weather data skills to plan future vacations by using Jupyter notebook, the geoViews Python library, and the Geoapify API. 


*A map is created that displays a point for every city in the city_data_df DataFrame. The size of the point is the humidity in each city.

Narrow down the search to find the ideal weather condition.

*Find the ideal location to vacation that meets the following requirements:

-A max temperature lower than 27 degrees but higher than 21

-Wind speed less than 4.5 m/s

-Zero cloudiness


*For each city, the Geoapify API  was used to find the first hotel located within 10,000 meters of the coordinates.

Tthe hotel name and the country  were added as additional information in the hover message for each city on the map.

Detailed analysis included in the Jupiter notebook files.
