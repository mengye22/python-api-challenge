# What's the Weather Like? Using Python API

## Goal

Whether financial, political, or social -- data's true power lies in its ability to answer questions definitively. So let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?"


## WeatherPy

Creating a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. 

Plot the following:

* Temperature (F) vs. Latitude

![lat_temp](output_data/lat_temp.png)

* Humidity (%) vs. Latitude

![lat_humi](output_data/lat_humi.png)

* Cloudiness (%) vs. Latitude

![lat_cloud](output_data/lat_cloud.png)

* Wind Speed (mph) vs. Latitude

![lat_wind](output_data/lat_wind.png)

Your second requirement is to run linear regression on each relationship, only this time separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

* Northern Hemisphere - Temperature (F) vs. Latitude

![lat_temp_north](output_data/lat_temp_north.png)

* Southern Hemisphere - Temperature (F) vs. Latitude

![lat_temp_south](output_data/lat_temp_south.png)

* Northern Hemisphere - Humidity (%) vs. Latitude

![lat_humi_south](output_data/lat_humi_north.png)

* Southern Hemisphere - Humidity (%) vs. Latitude

![lat_humi_s](output_data/lat_humi_south.png)

* Northern Hemisphere - Cloudiness (%) vs. Latitude

![lat_cloud_n](output_data/lat_cloud_north.png)

* Southern Hemisphere - Cloudiness (%) vs. Latitude

![lat_humi_s](output_data/lat_cloud_south.png)

* Northern Hemisphere - Wind Speed (mph) vs. Latitude

![lat_wind_n](output_data/lat_wind_north.png)

* Southern Hemisphere - Wind Speed (mph) vs. Latitude

![lat_wind_s](output_data/lat_wind_south.png)



## VacationPy

Use jupyter-gmaps and the Google Places API for this part of the assignment.


* Create a heat map that displays the humidity for every city.

* Narrow down the DataFrame to find your ideal weather condition.

* Using Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.

* Plot the hotels on top of the humidity heatmap with each pin containing the **Hotel Name**, **City**, and **Country**.


