# Surf's Up: A Climate Analysis of Hawaii

## Overview
In hopes of opening a surf shop in Oahu, Hawaii, we will analyze the weather trends to assess the sustainabiliy of the endevor. 

Using weather data obtained from verious weather stations we will use Jupyter Notebook to analyze temperatures for the months of June and December with data spanning the time range between 2010 to 2017.

## Results:
After pulling the daily temperatures for June and December, summary statistics tables were created as seen below:

<p align="center">
<img src=https://github.com/smanowar/surfs_up/blob/main/visuals/june_temps_farenheit.PNG> 
<img src=https://github.com/smanowar/surfs_up/blob/main/visuals/december_temps_farenheit.PNG>  
<br>
Temps in Fahrenheit   
</p>

<br>
Temperatures were then converted to Celcius for ease of analysis:
<br><br>

<p align="center">
<img src=https://github.com/smanowar/surfs_up/blob/main/visuals/june_temps_celcius.PNG> 
<img src=https://github.com/smanowar/surfs_up/blob/main/visuals/dec_temps_celcius.PNG> 
<br>
Temps in Celcius
</p>

Calculations were based on 1700 recordings for June and 1517 recordings for December

From the tables above we can see the following:

The max temperature recorded is: 
- 85°F (29.4°C) for June
- 83°F (28.3°C) for December

The min temperature recorded is:
- 64°F (17.8°C) for June
- 69°F (13.3°C) for December

The average temperatures are:
- 74.9°F (23.9°C) for June
- 71°F (21.7°C) for December

## Summary:
Based on the outcomes from the section above we can see that the temperature was within the range of 64°F and 85°F for June, and 69°F and 83°F for December.

Because weather can vary dramatically it is very likley that our results contain outliers. Because of this we will base our analysis on the average temperatures and the standard deviation. The average temperature for June is 74.9°F with a standard deviation of 3.26, and 71°F for December with a standard deviation of 3.75. Converting to Celcius it is on average 23.9°C for June and 21.7°C for December. While on the cool side for beach weather it is the perfect temperature for surfing. 

Additional queries that should be performed to see the likleyhood of the success of the surf shop are:

- **precipitation levels in Oahu**, as this will affect the volume of tourists coming to the beach
- **wind levels in Oahu**, as this will affect the surfing conditions
