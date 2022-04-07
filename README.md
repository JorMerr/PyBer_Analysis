# PyBer_Analysis
## Overview of the Analysis

The purpose of this analysis project is to calculate the total weekly fares of PyBer Ride Sharing per city type (Urban, Suburban, and Rural). The analysis will include a multiple-line graph showing data for the date range of 2019-01-01 through 2019-04-28.

Finally, the following report will summarize the differences between each city type in order for PyBer management to make future business decisions.


## Results

Analysis of PyBer Ride Sharing data shows several clear differences between ride-sharing data based on city type, as can be seen on the summary dataframe below.

![Pyber Summary DataFrame](https://github.com/JorMerr/PyBer_Analysis/blob/main/analysis/pyber_summary_df.PNG)

1- The number of Total Rides per city increases as the population density of the city type increases.

2- The number of Total Drivers per city increases as the population density of the city type increases.

3- The Total Fares collected increases as the population density of the city type increases.

4- The Average Fare per Ride decreases as the population density of the city type increases.

5- The Average Fare per Driver decreases as the population density of the city type increases.

The above trends appear to indicate that as the population of a city increases there is more market for ride-sharing services for travel. This increase in the number of drivers and the number of rides in an Urban city results in a larger total value of fares collected, while the Average Fare per Ride and the Average Fare per Driver decreases.

Based on the data, some assumptions may be drawn regarding the rides based on city type. 

1- In an Urban city, the distance of the ride may be shorter than in a Rural city, thereby reducing the fare for the ride.

2- In an Urban city there is a likelihood of more rides per day per driver when compared with a Suburban or Rural city.

3- In Rural cities over the dataset, we see the number of Total Rides at 125 and the number of Total Drivers at 78. This indicates that each driver does an average of approximately 1.6 fares over the entire dataset. 
In comparison, Suburban fares indicate approximately 1.3 rides per driver, and Urban fares indicate approximately 0.6 rides per driver.
This difference is visible when comparing the Average Fare per Driver between the different city types.

4- While the largest Total Fares is found in Urban cities, it appears the primary cause is simple the Total Rides in Urban cities.

![Fare Summary](https://github.com/JorMerr/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)


## Summary

The final recommendations of this report to the CEO as a means of addressing disparities among city types are as follows.

1- Further analysis to determine the average distance per ride. This will allow for more clear indication of the type of ride per city type, such as how far the destination must be for users to request PyBer Ride Sharing in each city type.

2- Analysis of data to determine the number of riders per ride in each city type. The number of riders, whether all going to the same location or new riders joining partway through a trip, will help determine the preference of users to allow for sharing rides with other users.

3- The analysis did not take in account any premium fare pricing, or discounted fare programs or times. 
Dedicated analysis for premium and discounted fare times may indicate further business potential, such as dedicated assignment for Ride Sharing provided by PyBer at large events (concerts, sporting events, festivals, etc.), and whether these locations would be suitable for additional advertising. Initial assumptions would appear the indicate that Rural markets are less likely to benefit for premium pricing and services.