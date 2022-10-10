# BikeSharing Project - Proposal for Des Moines
Create worksheets, dashboards and stories to visualize data using Tableau.

## Overview

![Citi_Bike_image](https://github.com/tiffanylin706/bikesharing/blob/a03624df7c6616dec50d96edc543dd8816f21dea/images/Citi-Bike.png)

The purpose of this analysis is to provide a business proposal that can convince investors that developing a bike-sharing program in Des Moines is a profitable venture. Throughout the process, the data we use is publicly available from the NYC CitiBike program [archives](https://s3.amazonaws.com/tripdata/index.html) and `Tableau` to create visualizations. 

While the data is based on activity that occurred in New York City, which is very different from Des Moines, we use our data expertise and critical thinking skills to build a story that can be presented to the investors. 

## Tableau Public Link

[Link to Dashboard](https://public.tableau.com/app/profile/tiffany.lin4386/viz/BikeSharing_16653582188570/Story1)

## Results

### Total Rides, Customer Type and Gender Breakdown
![totalrides](https://github.com/tiffanylin706/bikesharing/blob/0b35a174c07afaf14bc1b3f77ec047710e0c1c28/images/total_rides.png)

In NYC, there were over 2.3M trips that occurred during the month of August with 81% of the riders in the **"subscriber"** category and that **Men** were the primary user of this program (65%).


### Checkout Times for Users
![CheckoutTimes](https://github.com/tiffanylin706/bikesharing/blob/0b35a174c07afaf14bc1b3f77ec047710e0c1c28/images/CheckOutTimes.png)

Almost all of the trips (99%) were under 60 minutes with 49% under 10 minutes (1.1M vs. 2.3M).

### Checkout Times by Gender
![checkoutgender](https://github.com/tiffanylin706/bikesharing/blob/0b35a174c07afaf14bc1b3f77ec047710e0c1c28/images/checkoutgender.png)

Male riders are the primary user of the bike share program making up 65% of the population, with the remaining being 25% female and 10% unknown.

### Trips by Weekday for Each Hour

![TripsWeekday](https://github.com/tiffanylin706/bikesharing/blob/0b35a174c07afaf14bc1b3f77ec047710e0c1c28/images/TripsWeekday.png)
Most of the rides during the weekdays (M-F) occur during commuting hours of 8-9a and 5-7pm. It can be assumed that the bike sharing program is the preferred method for commuting to and from work


### Trips by Gender (Weekday per Hour)

![TripGender](https://github.com/tiffanylin706/bikesharing/blob/0b35a174c07afaf14bc1b3f77ec047710e0c1c28/images/TripGender.png)
Male riders are more inclined to use the bike sharing program to commute to and from work, as well as during the weekend.

### Trips by Gender by Weekday

![TripWeekGender](https://github.com/tiffanylin706/bikesharing/blob/0b35a174c07afaf14bc1b3f77ec047710e0c1c28/images/TripWeekGender.png)

Thursday was the highest usage day among subscribers with the most usage occurring on Saturday for non-subscribers.


## Summary
By looking at the visualizations we created based on NYC, we can summarize:

* Stalls were seen more common in business areas, such as Midtown and Downtown made up the majority of the usage. 
* Subscribers are the majority of users of the program.
* The duration of most trips were under 10 minutes.

In summary, developing a bike share program in Des Moines, IA may be a good business investment. However, the program needs to be installed in densely populated areas where mass transportation is highly used and parking is limited. We would need to review additional data in order to provide a strong case to support this recommendation by adding:

* Create visualization that maps out usage from starting to ending location to determine the distance traveled. Where are users starting their trip from and why? Are they using the bike to complete their commute after taking the bus or the train? 
* Add visualization to explore the activity by age group and adding demographic information to identify areas in which bikeshares would most likely be used (i.e. census data).

