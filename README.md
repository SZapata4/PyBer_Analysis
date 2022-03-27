# PyBer_Analysis

## Overview of Project

This purpose of this project was to break down ride sharing data given to me by the PyBer CEO into city type: Rural, Suburban, and Urban. Then I was to break the city type data down in the total fare per week for a certain period and present that data with a line graph.

## Results

###City Type Summary Data Frame

After merging the city and ride data frames I used the groupby function to put together a few stats by each city type Rural, Suburban, and Urban. Next, I used those statistics to create the below data frame.


[PyBer_city_type_df.png](https://github.com/SZapata4/PyBer_Analysis/blob/main/analysis/PyBer_city_type_df.png)

Looking at this data frame there some interesting takeaways. One is that Total Rides, Total Drivers, and Total Fares are increase as go from Rural to Suburban to Urban cities. Second is that Average Fare per Ride, and Average Fare per Driver react inversely to the other columns as you go from Rural to Suburban to Urban cities.

### Total Weekly Fare by City Type Graph

After creating the above data frame, I used the pivot and resample functions to create a new data frame where I got the total fare for weeks from 2019-01-01 through 2019-04-28. Then created the below line graph to display the findings.

[PyBer_fare_summary.png](https://github.com/SZapata4/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

Looking at this graph you can see that Urban cities earn more than the Suburban cities and the suburban total fares are greater than the rural total fares. This is interesting because it is the opposite when you deal with average fares by city.

## Summary

Now that I have completed the above analysis there are a few business recommendations that I can make based on the data. 
1.	Looking at the Urban city data it is clearly the most successful of all the types of cities when you look at total fares compared to the other types of cities. For this type of city, I notice that there are more drivers than total rides so I would invest in trying to get the number of rides increased. This could be done by using marketing to target would be riders to use PyBer more often.
2.	For the Suburban cities they are fairly even in all parts but just do not produce as much as the urban areas most likely due to population size. In these cities I would continue to target both drivers and riders via marketing to maximize revenue in the area.
3.	Lastly the Rural cities are the lowest earning type of city. Here I would also use marketing to target potential riders because even a small increase in riders would increase PyBers earning substantially in this type of city. Also with the Rural cities having the highest average fare for driver an increase in rides might also incentives more driver to join PyBer.

