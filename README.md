# World_Weather_Analysis

# Project Overview 
The purpose of this project was implenting the use of API keys through the Google Maps Platform as well as the data source from OpenWeatherMap. OpenWeatherMap is an online service, owned by OpenWeather Ltd, that provides real time global weather data via API, including current weather data, forecasts, nowcasts and historical weather data for any geographical location. The organization also provides a minute-by-minute hyperlocal precipitation forecast for any location that coincides and will help witht eh projects analysis, plotting, and visualization with the Python library Pandas, Matplotlib, and SciPy. 

In this project we also plotted the relationship between 1,500 generated randomized latitude and longitude from the weather data and got the nearest city using the provided citipy module while at the same time performing an API call with the OpenWeatherMap. We then created a filtered new DataFram that was then added to a marker layer map that included the desired information:
  - Hotel Name
  - City
  - County
  - Current Weather Description with the maximum temperature
  
 Lastly we created a Travel Itinerary that displayed the route between four cities from the possible travel destinations that the customer's can input as long as it is not separated bodies of water. 
