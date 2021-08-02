# Bikesharing

## Overview of Analysis

In this analysis, Tableau Public is used to visualize data from New York City Citibike rentals to show that a similar company would be successful in Des Moines, Iowa. Based on customer trip duration, checkout times, daily usage patterns, and other factors, comparisons can be made to bikeshare history in New York with the demographics and likely usage within Des Moines to show that this would be a great investment.

## Results
Using Tableau, 8 different visualizations were created to show different key aspects of the New York Citibike business that could lead to success within Des Moines. Many of these also show filters that can be changed to dig into certain data points even more.

#### Trips by User Type
More than 80% of bike trips were taken by subscribers vs. single-use customers. 
![Alt Text](https://github.com/lyanneagger/bikesharing/blob/main/Resources/usertype.png)</br>


#### Trip Starting Location
The trip starting location shows larger and darker circles in areas where more bike trips started. Manhattan has many of the busiest locations, which may be skewed by having more tourists and density among housing and workplaces. However, the map does show widespread use among the other boroughs and surrounding areas as well, proving that a densely populated area like Manhattan isn't entirely necessary for success.
![Alt Text](https://github.com/lyanneagger/bikesharing/blob/main/Resources/location.png)</br>

#### Trip Duration
The trip duration summary shows that the vast majority of bikes were rented for less than an hour, with the most common trip length being 5 minutes.
![Alt Text](https://github.com/lyanneagger/bikesharing/blob/main/Resources/checkout_times.png)</br>

#### Trip Duration by Gender
The same trip duration data was split by gender. Some of the rental information did not specify the gender of the user, but the majority of users were male. It is clear here that trip duration shows similar patterns among male and female riders both renting for short periods of time.
![Alt Text](https://github.com/lyanneagger/bikesharing/blob/main/Resources/checkout_times_gender.png)</br>

#### August Peak Hours
The peak hours visualization shows that the busiest hours for checkout tend to be in the evening (5 p.m. and 6 p.m.) as well as in the morning just before the workday at 8 a.m. 
![Alt Text](https://github.com/lyanneagger/bikesharing/blob/main/Resources/peak_hours.png)
The filter for day has been included in this visualization because the data shows very different trends from weekends to work days. If Sunday and Saturday are removed, the morning and evening rush hour trends become stronger, as shown in the first image below. If only Saturday and Sunday are checked, the trend changes greatly to show busy hours from 11 a.m. to 6 p.m., as shown in the second image below.</br>
![Alt Text](https://github.com/lyanneagger/bikesharing/blob/main/Resources/peak_hours_weekday.png)![Alt Text](https://github.com/lyanneagger/bikesharing/blob/main/Resources/peak_hours_weekend.png)</br>

#### Trips by Weekday per Hour
The trips by weekday per hour reinforce the August peak hours visualization, further breaking down each day to show darker red during morning and evening rush hours. The busiest day is Thursday from 5 p.m. and 6 p.m., with a bit of a comparitive lull on Wednesday nights. Again, the filter for day was added to better see week day commutes compared to steady weekend traffic.</br>
![Alt Text](https://github.com/lyanneagger/bikesharing/blob/main/Resources/trips_weekday_hour.png)</br>


#### Trips by Gender (by Weekday per Hour)
The trips by weekday per hour were also broken up to reflect usage across genders. Users are predominantly male, but as with trip duration, both male and female users show similar trends in renting around rush hour and throughout the day on weekends.
![Alt Text](https://github.com/lyanneagger/bikesharing/blob/main/Resources/trips_weekday_gender.png)</br>


#### Trips by Day by Gender by User Type
The last visualization shows trips by day broken out by gender and customer vs. subscriber. Again, we see male users completing most of the trips, but it is clear here that they are mainly by male subscribers. In addition, single-use customers tend to rent slightly more on weekends, while subscribers tend to rent more on Thursday and Friday.
![Alt Text](https://github.com/lyanneagger/bikesharing/blob/main/Resources/trips_weekday_gender_user.png)</br>


## Summary

In summary, a bikeshare business would be successful in Des Moines either as a means of transportation or as a form of recreation. Between the many corporate offices, the state's capitol, six universities, and bustling nightlife, the city is prime for a number of markets and potential subscribers/ customers. 

Despite New York's large numbers of tourists, the overwhelming number of subscribers' trips shows that there is a large base of locals who rent bikes, rather than single-use customers. The short average trip duration and trips by weekday show a clear pattern of heavy traffic for using the bikeshare as a means of transportation, especially during morning and evening rush hours. In addition, the Saturday and Sunday afternoon trips per hour show that afternoon rides are also busy times for bikeshare. This shows how versatile and broad the reach of a bikeshare business can be.

Some additional visualizations that may give more insight would be to compare trip duration by day (exploring work day commutes compared to weekend or evening rides) and bike utilization by number of trips and trip duration (to establish longevity of each bike). Comparing trip starting location or ending location to age may also give some information as to demographics around workplaces and offices vs. schools or college campuses. It would also be helpful to compare different data sets throughout the year to examine how weather affects usage patterns.

[Click here for NYC Citibike Analysis](https://public.tableau.com/app/profile/ly.agger/viz/NYC_Citibike_Challenge_Story/NYCCitibikeAnalysis?publish=yes)