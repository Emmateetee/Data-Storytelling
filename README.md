# Ford GoBike Analysis
## by Taiwo Ajagunsegun


## Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.
A total of 183,412 bike trips were recorded in the dataset with 16 features ('duration_sec', 'start_time', 'end_time', 'start_station_id', 'start_station_name', 'start_station_latitude', 'start_station_longitude', 'end_station_id', 'end_station_name', 'end_station_latitude', 'end_station_longitude', 'bike_id', 'user_type', 'member_birth_year', 'member_gender', 'bike_share_for_all_trip').


## Summary of Findings

> I explored the distribution of some features and the relationships inherent between some of the features in the dataset. I observed that the duration_sec column has a heavily right skewed distribution which suggests that most of the trips are short trips. Also, most of the members are male which doesn't seem unusual.

> I also found out that members between the ages of 20 years and 50 years spent higher percentage of time in their trips. Also, most of the stations act as both start_stations and end_stations as both latitude vs longitude plots represent the same shape on the map.

> One of the interesting findings I discovered is that all the members that shared bike for all their trips are basically subscribers. None of the customers shared a bike for all their trips.

## Key Insights for Presentation

> For this presentation, I focus on the distribution of the features and the relationships that exist between them. Majority of the insights uncovered in this analysis are as expected since they are intuitive.

> I start by plotting the distribution of the trip duration column. Afterwards, I establish a relationship between the trip duration and the ages of the members using a scatter plot with a hue of bike_share_for_all_trip column.

> Conclusively, I figured out that only subscribers are the major members that share bike for all their trips. I used a unique color style for each quality variable to make sure insights are clear and straight to point.