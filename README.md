# PyBer Ride Sharing Analysis

## Overview
### Project Purpose
The purpose of this project was to analyze the ride sharing data by the type of city (Urban, Suburban, and Rural).  The data was put into a dataframe and then graphed using a multi-line chart showing the weekly fares for each city type (from the beginning of January to the end of April).
### Metrics
This report analyzed the ride sharing data of Total Rides, Total Drivers, Total Fares ($USD), the Average Fare per Ride ($USD), and the Average Fare per Driver($USD), per city type.
## Results
### Multi-Line Graph
![PyBer_fare_summary](https://user-images.githubusercontent.com/99417460/162585042-10ebfbb1-ac4d-4c98-8903-bb2159a8ef24.png)
As you can see from the chart above, the weekly total fares for urban cities is nearly double that of the suburban cities.  The weekly total fares for suburban cities is nearly triple that of rural cities.  This shows that urban cities are the revenue leader for the company, while suburban cities come in second, and rural cities come in last.  

The chart also shows the following:
* The beginning of January is the least revenue generating time for Urban and Suburban city types.
* Urban and Suburban city types peak near the end of February.
* While Urban cities peak again in the beginning of March, Suburban cities don't peak again until the end of April (and appeared to be still going up).
* Rural cities peak at the beginning of April.

### DataFrame Summary
<img width="629" alt="PyBer_Summary_DataFrame" src="https://user-images.githubusercontent.com/99417460/162585712-ace2f2bb-fe5c-4ed0-a926-a5430d6b38ed.png">

Based on the DataFrame Summary above, we can determine the following:
* Urban cities account for 68.4% of the total rides, while Suburban cities account for 26.3%, and Rural cities account for 5.3% of the total rides.
* There are more drivers in urban cities than there were rides.  
* Urban cities have 80.9% of the total drivers, while suburban cities have 16.5%, and rural cities have 2.6% of the total drivers.
* Urban cities account for 62.7% of the total fares.  Suburban cities account for 30.5% of the totla fares, and rural cities account for 6.8%.
* Rural cities have the highest average fare per ride, at $34.62.  Suburban cities' average fare per ride is $30.97.  Urban cities have the cheapest average fare per ride, at $24.53 (approximately $10 less that rural cities).
* Rural cities have the highest average fare per driver, at $55.49.  Suburban cities' average fare per driver is $39.50.  Urban cities, again, have the cheapest average fare per driver, at $16.57 (nearly $40 less than rural cities and nearly $23 less than suburban cities).

## Summary
Based on the results of the analysis, I would make the following recommendations to the CEO of PyBer:
* Reduce the number of drivers in Urban cities.  From January to April, there were nearly 800 more drivers in Urban cities than there were rides.  Reducing the amount of total drivers can cause the average fare per driver to increase.
* Do more marketing in the Urban cities to increase the number of rides, especially in January.  
* Increase the number of drivers in Rural Cities.  There were only 78 drivers for Rural Cities.  Increasing the number of drivers will cause the average fare per driver and average fare per ride to decrease, which can make our company more competitive in those markets.  Also, this will reduce the burdan on our rural drivers so that they are not having to drive farther to the customers.
* Increase the advertising in Suburban cities to increase the number of rides.
