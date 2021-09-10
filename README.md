# Citi Bike Analysis
## Overview
The idea of this analysis is to better understand Citi Bike users. We do this by visualizing ride data into meaningful charts and breaking it down by different groupings such as ride duration, gender, popular ride times, and user types.

## Results
[Navigate to visualizations](https://public.tableau.com/views/CitiBike_16312434019900/Navigation?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link "visualizations")

The "Trip Duration" dashboard holds the "Length of Rides", "Length of Rides by Gender", and "Gender" visualizations.

### Trip Duration
* Length of Rides represents the number of rides per ride duration (minutes).
* Length of Rides by Gender shows the same data as Length of Rides but breaks rides down by gender
* The Gender visual is a pie chart that shows the different users by their gender. This helps give perspective on the total of each gender type. It would make sense for there to be more male rides when there are nearly 3 times more males than females.

The "Time of Week Breakdown" dashboard hold the "Rides by Hour & Day of Week", "Rides by User Type, Day of Week, & Gender", "Rides by Time & Gender", and "User Types" visualizations.

### Time of the Week Breakdown
* Rides by Hour & Day of Week is a heat map that shows the most popular ride times for each day of the week.
* Rides by User Type, Day of Week, & Gender is similar to the Rides by Hour & Day of Week visual but it adds in genders to the columns, user types to rows, removes the hour and replaces it with the day of the week in the rows.
  * This heatmap mostly shows that subcribed males ride the most out of any gender/user type breakdown.
* Rides by Time & Gender is the same as Rides by Hour & Day of Week but splits out the coulmns by gender.
  * If there was a major difference in popular times between genders we could see that in this visual. In this case, it confirms that males and females ride at similar times
* User Types is a pie chart that shows there are nearly 5 times more subscribed users than customers.


## Summary
A majority of rides last 2 to 12 minutes. There is a slight difference between gender. It seems that females are more likely to ride for a longer time. The number of rides drops at a slower rate after the 12-minute mark for females than males. There are nearly 3 times more men than women that use this service. It appears that the busiest hours are from 4pm to 7pm on all weekdays but Wednesday. It is obvious that male subcribers make up a majority of the rides and they ride the most on Thursdays. Male and females have similar popular ride times.

### Future Visualizations
* Average distance per ride by time of day would be a helpful analysis so that we can better understand how far people are riding their bikes depending on the situation. I'm sure that weekend ride lengths and weekday ride lengths are much different.
* Bike start and stop locations & the demand of those locations. There are people that depend on these bikes as a means to commute. For some people there might be a shortage of bikes at their nearest location. Doing an analysis on a user and whether or not they pick up a bike where they last dropped off their bike could give us a good idea of whether or not there need to be more bikes at a spcific location at a specific time. Stations with 0 bikes at those particular times could be shown on a map.
