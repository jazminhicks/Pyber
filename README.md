# Pyber

The ride sharing bonanza continues! Seeing the success of notable players like Uber and Lyft, you've decided to join a fledgling ride sharing company of your own. In your latest capacity, you'll be acting as Chief Data Strategist for the company. In this role, you'll be expected to offer data-backed guidance on new opportunities for market differentiation.

You've since been given access to the company's complete recordset of rides. This contains information about every active driver and historic ride, including details like city, driver count, individual fares, and city type.

Your objective is to build a *Bubble Plot* that showcases the relationship between four key variables:

* Average Fare ($) Per City
* Total Number of Rides Per City
* Total Number of Drivers Per City
* City Type (Urban, Suburban, Rural)

![ride_share_scatter](https://user-images.githubusercontent.com/49836101/59642549-17c63e00-912b-11e9-84c7-bda88bcc291f.png)

In addition, you will be expected to produce the following three pie charts:


* % of Total Fares by City Type

![total_fares_pie](https://user-images.githubusercontent.com/49836101/59642610-5b20ac80-912b-11e9-9dbc-4223b9c74eab.png)


* % of Total Rides by City Type

![total_rides_pie](https://user-images.githubusercontent.com/49836101/59642632-6bd12280-912b-11e9-8be4-47a732cf7d10.png)



* % of Total Drivers by City Type

![total_drivers_pie](https://user-images.githubusercontent.com/49836101/59642593-493f0980-912b-11e9-9a84-9858e68373d4.png)



# Pyber Analysis
##### Using the above data visualizations we can note the following trends:

* There is a negative correlation in the number of rides provided in a city and the average fare. More rides are provided in urban cities and the average fare is also lowest in comparison to rural or suburan areas. 

* Similarly, the most drivers can be found in urban cities and make up nearly 81% of all drivers in the area. We should take into consideration that the lower average fare in urban cities may partially be a result of more driver availability compared to that of rural cities. 

* There may be potential opportunity to expand the market in the suburban area. Currently the number of rides exceeds the number of available drivers by about 10%. Adding more drivers to this area may allow prices to be driven down some, making riding in the area more affordable and potentially drive up total revenue. 
