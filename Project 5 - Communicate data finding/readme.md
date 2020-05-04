# Data Analysis for Ford GoBike System
## by Huu Tri Nguyen


## Dataset

The data set consist of 239,111 bike ride in April 2019. The data can be found here: https://s3.amazonaws.com/fordgobike-data/index.html

The dataset contained features about:

trip duration: start/end time, how long the trip took in seconds stations: start/end station, name, geolocation (latitude/longitude) user type rented bikes: bike id The dataset was further enhanced with features that I may find neccessary to perform interesting analysis:

rental time: month, day, hour of the day, weekday (both for start and end date)

The following columns were added:

start_time_weekday
start_time_day
start_time_hour
distance_km

## Summary of Findings

Observation:

The majority of users for this system are subscribers (87.1%)
Majority of users are between the working age of 20 - 40 years old
Customers use the bike sharing system equally on any day of the week. On the other hand, subscribers tend to use the system more on weekdays with relatively low usage on the weekend
As depited by the histogram in the bivariables analysis and the heat map above. Between 9am - 4pm, which are working hours, customer generally has higher bike usage than subscribers. Additionally, bike usage for subscribes is also much higher between 8-9am (waking hour/work start hour)
Customer generally take longer trips than subscribers, both in terms of travel duration and distance (km)
There are a higher male-to-female ratio for subscribers than customers
Genders do not appear to affect bike usage in anyway as both males and females have very similar usage pattern


## Key Insights for Presentation

Subscribers are likely people who use it for school and work commute, this is supported by the fact that they generally take shorter and quicker trips. Additionally, they have the highest bike usage before 9am and after 5pm, and very low usage between 9am - 5pm, which makes sense as these people do not use the system during work hour
Customers are likely to be tourists, this is supported by the fact that they take longer trips and the usage is not constrained by day of the week or working hour.
Male are generally more likely to use and become the member of the system as shown by the male-to-female ratio in terms of number of users and subscriber