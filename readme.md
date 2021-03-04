# (Ford Go-Bike Dataset)
## by (Mohamad AbouElela)


## Dataset

This data set represents trips taken by members of the Ford Go Bike service for month of February of 2019.
Data consists of info about trips taken by service's members, their types, their age, their gender, stations of starting and ending trips, duration of trips etc.

## Dataset Dictionary

1. duration_sec: Trip Duration (seconds)
2. start_time>: Start Time and Date
3. end_time: End Time and Date
4. start_station_id: Start Station ID
5. start_station_name: Start Station Name
6. start_station_latitude: Start Station Latitude
7. start_station_longitude: Start Station Longitude
8. end_station_id: End Station ID
9. end_station_name: End Station Name
10. end_station_latitude: End Station Latitude
11. end_station_longitude: End Station Longitude
12. bike_id: Bike ID
13. user_type: User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)
14. member_birth_year: Member Year of Birth
15. member_gender: Member Gender
16. bike_share_for_all_trip: Boolean to track members who are enrolled in the "Bike Share for All" program for low-income residents


## Summary of Findings

1. Data consists of 183412 rows and 16 columns 
2. Males represent 75% of Ford Go-Bike service users in the dataset, the average age for males and females are quite equal around 33 years of age 
3. More than 90% of users are Subscribers to the Ford Go-Bike service, Higher numbers of Ford Go-Bike service subscriber (both males and females) regardeless of the gender can be explained due to easy and cheap subscribing fees, also can be because of fare difference between subscribers and customers.
4. The age distrubution is right skewed with members of age between 30 to 40 years representing major partition of the dataset
5. Both (Market st, San Francisco caltrain station2) are the highest starting and destination stations, We can use this data to increase number of available bikes at these stations
6. Most Bike ride durations is below 30 min, however the duration have a long tail of outliers may be due to users keeping their bike rented during work or forget to log off after finishing rides.
7. Members aged between 25-40 years tend to do the longest rides durations.
8. Most users prefer not to use the "Bike Share for All" regardless of there gender


## Key Insights for Presentation

we will focus on:
1. Overall explanation for dataset gender distribution and average gender ages
2. Age and Ride duration relation
3. Most active stations
