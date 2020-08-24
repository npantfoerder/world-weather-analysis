# WeatherPy with Python APIs
## Purpose
A hypothetical travel company, PlanMyTrip, wants to use data to recommend ideal hotels based on clients' preferences. 
Specifically, the project is to use Jupyter Notebook and APIs to retrieve and analyze weather data from over 500 cities and provide real-time suggestions:

1) Collect Data
 - Generate random latitudes and longitudes
 - Use CitiPy module to find the nearest cities and the OpenWeatherMap API to request current weather data
 - Parse the JSON data, store it in a DataFrame, and create a CSV file
 
 2) Exploratory Analysis
 - Perform statistical analysis on the data using the SciPy library
 - Use the Matplotlib library and Google Maps API to create a series of plots that show the relationship between latitude and a varity of weather parameters
 
 3) Visualize Data
 - Filter the DataFrame based on user inputs for a temperature range
 - Use the Google Maps API to find nearby hotels and create a heatmaps with pop-up markers

### Resources
- APIs: OpenWeatherMap, Google Maps Platform
- Software: Python 3.7.3, Anaconda 4.8.3, Matplotlib 3.2.2, Requests 2.24.0, SciPy 1.5.0
