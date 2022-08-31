# bikesharing

## Overview of Analysis

### Purpose of Analysis 

This analysis of NYC CitiBike data from August 2019 was completed in order to test feasibility for starting a similar program in another city.

### Process

This analysis was completed using Tableau for data visualization, and Pandas/Python to manipulate the data.

## Results

### Full Results

The full Tableau story can be viewed [here](https://public.tableau.com/app/profile/elizabeth1287/viz/CitiBike_Challenge_16619006191940/ChallengeStory).

### Visualizations

#### Customer Type

![Customer Type Breakdown](https://github.com/ehalprin/bikesharing/blob/main/images/Customer_Type.png)

Most of the users of CitiBike were subscribers, rather than one-time consumers. This suggests there is a robust user base returning again and again.

#### Gender Breakdown

![Gender Breakdown](https://github.com/ehalprin/bikesharing/blob/main/images/Gender_Breakdown.png)

The vast majority of users were also men. 

#### Trip Duration

![Trip Duration](https://github.com/ehalprin/bikesharing/blob/main/images/Checkout_Time.png)

Most users checked out a bike for less than an hour, with most rides only five minutes in duration. Very few trips lasted longer than an hour.

#### Trip Duration by Gender

![Trip Duration by Gender](https://github.com/ehalprin/bikesharing/blob/main/images/Checkout_Times_By_Gender.png)

This pattern was consistent across gender, though users of "unknown" gender did not have as high of a spike at 5 minutes, instead plateauing between 8-25 minutes. This suggests that most users were using CitiBike for relatively quick or short trips (rather than longer, more strenuous journeys, for which the subway or a cab might be a better alternative). 

#### Trips by Weekday per Hour

![Trips by Weekday per Hour](https://github.com/ehalprin/bikesharing/blob/main/images/Trips_by_Weekday_Per_Hour.png)

CitiBike was most highly utilized between 7 am-9 am, and again between 5 pm-7 pm. This suggests that many are using CitiBike for their daily commute to work or school, which aligns with the fact that most users are regular subscribers.

#### Trips by Weekday per Gender

![Trips by Weekday per Gender](https://github.com/ehalprin/bikesharing/blob/main/images/Trips_By_Weekday_per_Gender.png)

This pattern again held true across gender, suggesting that though more men used CitiBike overall, men and women used CitiBike in similar ways.

#### User Types by Weekday by Gender

![User Types by Weekday by Gender](https://github.com/ehalprin/bikesharing/blob/main/images/UserTrips_By_Gender_By_Weekday.png)

Looking at CitiBike utilization by weekday and across both user type and gender shows that male subscribers are the highest utilizers of CitiBike throught the entire week. Most of the users of "unknown" gender were one-time consumers, rather than subscribers -- which could explain why they had slightly longer trip durations, as perhaps they were using bikes more recreationally than functionally (i.e. on a commute).

## Summary

### Main Take-Aways

Overall, the CitiBike data suggests that other bike rental programs could develop a sustainable, regular user base and source of revenue, by providing an alternative commute option to residents of the city that it serves. Because the bikes have high utilization before and after regular business hours, maintenance should be performed late at night to reduce interruption of service. CitiBike is also used, at a lower but still significant rate, by one-time users, likely tourists. These tourists used bikes more in the weekend (Thurs-Sun), so mid-week late at night would not interrupt service for either group. 

### Further Research

To futher develop a strategy for implementing a CitiBike-like program in a new city, further information should be gathered via a visualization showing where subscribers vs. consumers are likely to travel -- overall, bikes were most highly used in lower Manhattan, but that pattern might be different for the regular subscribers using it for commuting compared to tourists. Another visualization that would be helpful to see would be a comparison of utilization across age and gender; this could help target marketing efforts when rolling out the new bike program.
