# Surfs_up Challenge Written Analysis

## Overview
### We are planning on opening a **Surf n' Shake Shop in Oahu, but in order to do so we need help by investors to invest in our shop. The investor who is interested is a tad worried about the weather in Hawaii, and therefore has asked us to run an analysis on the weather data. Our analysis will include the following steps:

- Ensure we have the data provided by the investor downloaded correctly.
- Store the weather data in SQLite. 
- Retrieve the precipitation data and analyze the precipitation levels showing how much it rained on any given day.
- Plot the results of our precipitation analysis.
- Summarize a few statistics.
- Confirm if we have enough data collection from stations to ensure our analysis is valid.
- Analyze temperature data to help determine the best location for the surf shop.
- Provide a plot chart of all the temperatures in a given year for the station with the highest number of temperature observations.
- Create a Flask application for better visualization of our analysis creating five routes for out investors: *Welcome*, *Precipitation*, *Stations*, *Monthly Temperature*, and *Statistics*.
- Provide information about temperature trends for the months of June and December in Oahu.

## Results
###
1. We can predict per our analysis that the June temperatures will be higher than the temperatures in December.
![June Temperatures](https://github.com/mavalenz/surfs_up/blob/main/Resources/June%20Temperatures.PNG)
![December Temperatures](https://github.com/mavalenz/surfs_up/blob/main/Resources/December%20Temperatures.PNG)

2. We can predict per our analysis that temperatures can drop to a low of 56 degrees in December. 
![December_Summary_Statistics](https://github.com/mavalenz/surfs_up/blob/main/Resources/December_Summary_Statistics.PNG)

3. The average temperature for the month of June vs December isn't that much of a difference. Both months average around 70 degrees.

## Summary
### In summary, per our analysis of the temperatures for the months of June and December. The differences in weather does not change drastically. Therefore, opening a surf shop in Hawaii seems to be a good investment all year round. Additional queries that could be performed to gather more data for June and December could be the following:

1. Precipitation levels by day for the month of June.
2. Precipitation levels by day for the month of December.

Running the above additional queries to our analysis will help indicate whether the conditions for surfing based on water levels will attract more surfers to the area. 