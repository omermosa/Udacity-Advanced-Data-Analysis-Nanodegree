# (Dataset Exploration Title)
## by (your name here)


## Dataset

> The dataset consists of 183412 instances and 16 cols ['duration_sec', 'start_time', 'end_time', 'start_station_id', 'start_station_name', 'start_station_latitude', 'start_station_longitude', 'end_station_id', 'end_station_name', 'end_station_latitude', 'end_station_longitude', 'bike_id', 'user_type', 'member_birth_year', 'member_gender', 'bike_share_for_all_trip']. 8265 rows were dropped due to the existence on Nans


## Summary of Findings

> Plotting the numeric variable splitted by the categorical variables doesn't seem to strengthen any of the relations between the variables. This might be due to the fact that most of the variables are indpendent.
>I plotted The three categorical variable to split the data of the plots between the distance and the duration. It seems that there is no relation except in the case of sharing the bike. Those who don't share the bike tend to spend higher durations when the birth year is bigger than about 1960.
>surprisingly, when there is no bike sharing, the duraiton tends to be slightly higher. Also, the distance was not directly propotional to the duration which logically should be the case.
>There was almost no effect of most of the variables on the duration of the ride. Only the bike sharing tends to have an effect. Both numerical variables (birth year, distance) had no trend; they only clustered the data in some region, but there was no direct or inverse variation with the duration.


## Key Insights for Presentation

> I plotted the distance relation with the duration, the distance distribution, and the effect of gender on the relation between the duration and the distance.