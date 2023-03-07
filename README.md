# Ford GoBike System Data Exploration
## by Sadeko Daniel


## Dataset

The data [Ford GoBike Data](https://www.google.com/url?q=https%3A%2F%2Fvideo.udacity-data.com%2Ftopher%2F2020%2FOctober%2F5f91cf38_201902-fordgobike-tripdata%2F201902-fordgobike-tripdata.csv&sa=D&source=docs) consists of information regarding 183,000 rides in February year 2019, 
with major features analyzed to be hour and day of ride, user type, age and the bike share feature. 

Feature Engineering was done to extract the day and hour of the ride, 
the distance feature was generated using the Haversine Formula, which served as one of a major feature analyzed.

## Summary of Findings

In the exploration,the duration in minutes took on large range of values and was greatly skewed to the right,
I took a log transformation of the duration and distance feature,
I performed log transformation the data and found the relationship between the duration and distance feature, 
it was a fair linear relationship. 

I further investigated the dataset to check how these two features interact with the other features, 
started with the Gender feature and found interestingly that more females on an average drive for longer durations, 
but this difference was not really distinct,.

I proceeded with the weekdays and the hours of ride and found that people tend to take ride 
for longer times during the weekend and at odd hours like 3:00am. 

I proceeded into Multivariate exploration, to understand the influence of the user type and 
bike share on the relationship between the days of the week and the duration of ride. 

I found that non-subscribers tend to have longer duration of ride during the weekends and same for sharing of bikes. 

There is usually more of bike share during the weekends as opposed to weekdays where there is more of non-bike sharing.


## Key Insights for Presentation

In the presentation, I focused more on just the relationship between the day of the week
with the duration and distance of ride.

I introduced the main feature, duration of rides in minutes and the distance of ride in kilometres
and provided a transformed scatterplot between these two features.
I also showed the distribution of the ride for the hours of ride.

I used a boxplots to show the relationship between the duration, distance and the days of the week. 

Bar charts were used for the other two categorical variables. 
The right colour palette were used and good descriptions for the plots were employed.
