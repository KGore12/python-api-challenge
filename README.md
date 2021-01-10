# python-api-challenge
Weather API homework

## Background
Whether financial, political, or social -- data's true power lies in its ability to answer questions definitively. So let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?"

Now, we know what you may be thinking: "Duh. It gets hotter..."

But, if pressed, how would you prove it?

![Summary](https://github.com/KGore12/python-api-challenge/blob/main/images/equatorsign.png)


## Part I - WeatherPy
Contained in this analysis done with jupyter notebook: 

* Over 500 randomly selected (non-repeat) cities based on latitude and longitude.

* A weather check on each of the cities using a series of successive API calls.

* A print log of each city as it's being processed with the city number and city name.

* Saved CSV file of all retrieved data and a PNG images for each scatter plot.

* A series of scatter plots to showcase the following relationships:

**_Temperature (F) vs. Latitude_**
<br><br>
![Summary](https://github.com/KGore12/python-api-challenge/blob/main/images/Temperature_vs_Latitude.png)
 
**_Humidity (%) vs. Latitude_**
 <br><br>
<p align="left">![Summary](https://github.com/KGore12/python-api-challenge/blob/main/images/Latitude_vs_Humidity.png)
      
<p align="center">**_Cloudiness (%) vs. Latitude_**
 <br><br>
![Summary](https://github.com/KGore12/python-api-challenge/blob/main/images/Latitude_vs_Cloudiness.png)
      
<p align="center">**_Wind Speed (mph) vs. Latitude_**
 <br><br>
![Summary](https://github.com/KGore12/python-api-challenge/blob/main/images/Latitude_vs_WindSpeed.png)

*  A series of linear regression plots on each relationship, separated into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude).



