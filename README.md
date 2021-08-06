# Surf's Up with Advanced Data Storage and Retrieval

## Overview of the Advanced Data Retireval and Storgae
Upon completion of a review of precipitation data, we want to ensure that weather patterns will remain conducive to an ice cream shop year-round.  Therefore, temperature data must also be analyzed, specifically, for both June and December.

## Analysis Results
*    ![December Precipitation Results](surfs_up/dec_precip_stats.PNG)




The written analysis has the following:

There is a bulleted list that addresses the three key differences in weather between June and December. (6 pt)
Summary:

There is a high-level summary of the results and there are two additional queries to perform to gather more weather data for June and December. (5 pt)


## Pyber Ride & City Analysis Summary
* Recommendation #1:  Increase the number of drivers in rural areas. 
  * The difference between rural and urban areas in terms of average fare per driver is $38.92.  The difference between rural and urban areas in terms of average fare per ride is $10.09.  The relatively smaller difference in the average per ride per fare tells us that attempting to increase the number of rides will not necessarily have a positive impact on total fares.  Instead, increasing drivers to meet what appears to be a higher demand in general in urban areas would have a greater result.  If we can reasonably tolerate a $16.57 average fare per driver in urban areas, we can reasonably do so in rural areas, meaning rural areas could potentially tolerate ~260 total drivers ($4327.93 / $16.57 ~ $260).  However, since total rides will not likely increase by the same amount in urban areas, the number of drivers should be increased incrementally and results should continue to be assessed weekly.
* Recommendation #2:  Decrease the number of drivers in urban areas.
  * The lower average fare per ride and per driver in urban areas points to a market that is oversaturated relative to suburban and rural areas.  Decreasing the number of drivers would have a positive impact on average fares per driver.  Total rides will likely remain the same.  There are significantly more drivers than there are rides in urban areas as well.  This is causing part of the relatively lower average fares per driver.
* Recommendation #3:  Adjust base rates to account for geographic data on cost-of-living.
  * The base fare rate should be adjusted lower for rural areas (which typically have lower costs of living), and urban areas (which typically have higher costs of living).  This will help encourage more rides in rural areas (leading to greater profit in these areas), while increasing total fares in urban areas (again leading to greater profit, but unlikely to have a significant impact on the number of rides).  Geographic cost of living data can be found at https://fred.stlouisfed.org/.
