# Surfs_Up

## Overview

For this project we are helping a client determine whether it makes sense or not to open up a surfing and ice cream shop. Our client would like to better understand temperature trends in Oahu, he hopes to see if there are any drastic changes throughout the year and if so, if it would impact sales. We are going to be looking at the months of June and December as these are typically where the most drastic weather changes tend to occur. After gathering summary statistics, we hope to provide this insight to investors to determine if it would be a sustainable business model year round.


### Data Sources

 - hawaii.sqlite

### Software

 - Python 3.9
 - Jupyter Notebooks 6.1.4
 - Anaconda 3.8.5
 - SQLite
 - SQLAclchemy
 - PostgreSQL
 - Flask

## Results

June Summary Statistics

![image](https://github.com/roderickspells/surfs_up/blob/main/june_temperatures.png)


December Summary Statistics

![image](https://github.com/roderickspells/surfs_up/blob/main/december_temperatures.png)

There are three key differences between June and December weather trends.

 - We gathered data from 2010-2017 for June and 2010-2016 for December

 - June had a low temperature of 64F while December had a low of 56F. This could slow sales in December.

 - December has a standard deviation of 3.76 and June has a standard deviation of 3.26. This indicates more variation in December than June, however it can also can indicate that there is very little weather fluctuation throughout the year from the most extreme months





## Summary

Overall, there doesn't seem to be any drastic changes in temperature between the two months. The average temperatures are fairly close and consistent There shouldn't be much impact on surfing sales due to the weather but ice cream sales may dip a bit if temperatures encroach on the December lows re observed in the data collected.

Two more queries we could run to gain more insight would be:
- (1) Gather the amount of precipitation in these two months, as more rain can affect sales. 
- (2) Gather the  amount rainfall and temperature trends next to the stations that recorded the data. This would help us determine where on the island would be ideal to place the business.