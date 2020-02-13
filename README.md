# Weather/Location Analysis

## Summary

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
* All this data is fed into another model to find ideal locations at this time of year. This file uses Googles API to map the cities and their relative humidity index along with filtering the sample down to locations that would be pleasant from a temp, wind, and cloudiness perspective. All outputs are within the file. 
* Findings and analysis are in the top section of WeatherPy.  

### Files
- The analysis includes the following files (located in the starter file folder):
  - A "WeatherPy.ipynb" Jupyter Notebook that contains the Python code for the analysis
  - "VacationPy.ipynb" is a Jupyter Notebook that utilizes Googles API to heatmap humidity and retrieve hotel information for a subset of the full dataframe that meets weather conditions that are favorable. 
  - Personal API keys were used in this analysis. If downloading this analysis, the user must put their own API keys for Open Weather and Google into this file in order for the  Notebook to work properly
  - A "cities.csv" CSV file in the "output_data" folder that contains the CSV version of the DataFrame created in the Jupyter Notebook
  - Twelve PNG files in the "output_data" folder. Each of the twelve files is a graph created in the analysis
  - Two additional PNG files in the "output_data" folder capturing the heat map and the ideal locations with hotel name. These maps are also located in the "VacationPy.ipynb" file.
  
