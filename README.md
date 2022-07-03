# PyBer with Matplotlib

## Project Overview
The purpose of this project was to conduct an analysis of ride sharing information for the company PyBer in order to determine trip differences among urban, suburban, and rural cities. Knowing the differences would allow PyBer to implement recommendations for improving rider access and increasing profitability.

## Resources
Data Source: city_data.csv, ride_data.csv

Software: Python 3.7.6 

## Results
Two sets of data were provided: one with information on cities and the other with information on rides. The city information included the name of the city as well as the number of drivers and city type (urban, suburban, or rural). Ride information included the date of the ride and the city it took place in, as well as the fare amount for the trip and the ride id. After the data was merged into one data set, it was possible to create a new DataFrame summarizing the number of rides and drivers per city type, as well as the total fares and average fare per ride and driver by city type. The summary DataFrame is shown below:

![This is an image](https://github.com/EricaEidelman/PyBer_Analysis/blob/main/Analysis/DataFrame.png)

The summary DataFrame shows that urban and suburban cities have quite a number more rides than rural cities, with suburban cities having 5 times the number of rides than rural ones, and urban cities 13 times the number of rides. This also means that urban cities have about 2.6 times the number of rides than suburban ones. In terms of drivers, urban cities have about 4.9 times the number of drivers as suburban cities, and suburban areas have about 6.28 times the number of drivers as rural ones. That means that in urban areas there are about 30.83 times as many drivers as in rural areas. This does result in an imbalance of drivers to rides, as the urban cities overall are the only ones where there are more drivers than rides happening.

The imbalance between the number or rides an drivers becomes more visible when looking at the fares. Overall, suburban and urban areas bring in about 5 and 10 times, respectively, the amount of fares than do rural areas. However, when comparing the average fare per ride, rural rides cost about $34.62 per ride, compared with $30.97 in suburban areas and $24.53 in urban ones. The differences in average fare per driver are even greater, with rural drivers making about $55.49, compared with $39.50 for susburban drivers and only $16.57 for urban ones.

## Summary
After looking at the differences between trip information among different city types, two conclusions can be drawn. One is that the relationship between the number of drivers and average fare is an inverse one: as the number of drivers increase, fares go down. Another conclusion that can be drawn is that riders in urban and suburban areas might be taking shorter trips, which results in lower fares. Based on the above, the following recommendations can be made.

1) The first recommendation would be to increase the number of drivers in rural areas. With an increase in drivers, rural residents will have greater access to trips and are more likely to experience a reduction in fares. Fare reduction could be offset by an increase in rides due to greater trip affordability, allowing total fares to not see a significant drop.

2) A related recommendation is to bring in the urban drivers to rural and suburban areas during slower periods in urban cities. The chart below shows a breakdown of weekly fares among the urban, suburban, and rural cities.
![This is an image](https://github.com/EricaEidelman/PyBer_Analysis/blob/main/Analysis/Fig8.png) 
As can be seen in the chart, there are certain periods, such as the middle and end of March, when fares in urban cities drop while in suburban and rural ones they stay steady or increase. Given that urban cities already have more drivers than requested rides, in those periods the app can open up requests from suburban or rural residents to urban city drivers. Doing so will increase availability of rides, therefore decreasing the average fare per ride while increasing the average fare per driver.

3) A final recommendation would be to provide PyBer as a transportation partner for various events occuring in rural areas. On the one hand, this will bring more drivers, allowing for greater availability of rides and thus greater attendance, increasing revenue for both PyBer and the even in question. Also, serving as an offical partner might allow PyBer to advertise to it urban and suburban users and convince them to use PyBer to attend the event, once again increasing visibility and revenue for the event and for PyBer. Likewise, this recommendation can be expanded to make PyBer a transportation partner for events in suburban and urban areas also.
