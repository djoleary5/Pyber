# Ride Share Analysis

We've been given access to the company's complete recordset of rides. This contains information about every active driver and historic ride, including details like city, driver count, individual fares, and city type.

## Visualizations

A [Bubble Plot](https://en.wikipedia.org/wiki/Bubble_chart) that showcases the relationship between four key variables:
* Average Fare ($) Per City
* Total Number of Rides Per City
* Total Number of Drivers Per City
* City Type (Urban, Suburban, Rural)
On the y-axis we have `Average Fare ($)` and on the x-axis we have `Total Number of Rides Per City`.  Each dot represents a city.  The color of the dot denotes the `City Type` (Urban(Coral), Suburban(SkyBlue), Rural(Gold)) and the size of the dot represents the `Total Number of Drivers Per City`; the larger the dot, the more drivers in that city. 

Three pie charts:
* % of Total Fares by City Type
* % of Total Rides by City Type
* % of Total Drivers by City Type

## Conclusions

* The highest average fares are in rural and suburban cities. This makes sense as destinations would be farther apart in those regions (longer rides lead to higher fares).

* There are also fewer rides and drivers per city than urban cities(supply/demand) which would contriute to the higher fares.

* The overwhelming majority of total fares, rides, and drivers are in urban cities. Reasons for this would probably be higher demand, as less people own cars and the shorter rides would yeild more affordable fares.
