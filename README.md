# python-api-challenge

## Summary

- A homework assignment for Georgia Tech's Data Analytics Bootcamp
- The Python code randomly selects a group of 500+ cities across the world. Then, the code collects data from the OpenWeatherMap API to create a representative model of weather across world cities. The API data is used to graph the following relationships:
  - Temperature (F) vs. Latitude
  - Humidity (%) vs. Latitude
  - Cloudiness (%) vs. Latitude
  - Wind Speed (mph) vs. Latitude
- The next objective is to run linear regression on each relationship, only this time separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):
  * Northern Hemisphere - Temperature (F) vs. Latitude
  * Southern Hemisphere - Temperature (F) vs. Latitude
  * Northern Hemisphere - Humidity (%) vs. Latitude
  * Southern Hemisphere - Humidity (%) vs. Latitude
  * Northern Hemisphere - Cloudiness (%) vs. Latitude
  * Southern Hemisphere - Cloudiness (%) vs. Latitude
  * Northern Hemisphere - Wind Speed (mph) vs. Latitude
  * Southern Hemisphere - Wind Speed (mph) vs. Latitude

### Files

- The analysis includes the following files:
  - A "WeatherPy.ipynb" Jupyter Notebook that contains the Python code for the analysis
  - A "api_keys.py" Python file that contains the OpenWeatherMap API key used in the analysis. If downloading this analysis, the user must put her or his OpenWeatherMap API key into this file in order for the "WeatherPy.ipynb" Jupyter Notebook to work properly
  - A "weather_df.csv" CSV file in the "Output" folder that contains the CSV version of the DataFrame created in the Jupyter Notebook
  - Four PNG files in the "Figures" folder. Each of the four files is a graph created in the analysis