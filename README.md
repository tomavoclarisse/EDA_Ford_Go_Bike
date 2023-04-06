# Ford GoBike system data February 2019
## by TOMAVO Clarisse


## Dataset

Ce jeu de données, j'ai pu la télécharger via le lien : https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv.
Il vient avec 16 colonnes. Au cours de notre analyse nous nous sommes retrouvés avec 18 colonnes ( 2 de plus donc)
Les colonnes de notre jeu de données:
'duration_sec': (in seconds),
'start_time' (In seconds),
'end_time' (In seconds),
'start_station_id',
'start_station_name',
'start_station_latitude',
'start_station_longitude',
'end_station_id',
'end_station_name',
'end_station_latitude',
'end_station_longitude',
'bike_id',
'user_type' (Which has two values: customer, subscriber),
'member_birth_year',
'member_gender' (Which has three values: Male, Female, Other),
'bike_share_for_all_trip' (Which has two values: Yes or No),
'start_month',
'start_day'.


## Summary of Findings

### On this dataset we notice that Ford GoBike system has many customers in 2019 who use its system whose age group is [1978,2001]
### All the trip departure station IDs are all present at the trip end stations. And vice versa.
### The top 10 departure stations
0 Market St at 10th St
1    San Francisco Caltrain Station 2  (Townsend St...
2                                   Berry St at 4th St
3     Montgomery St BART Station (Market St at 2nd St)
4         Powell St BART Station (Market St at 4th St)
5    San Francisco Ferry Building (Harry Bridges Pl...
6       San Francisco Caltrain (Townsend St at 4th St)
7         Powell St BART Station (Market St at 5th St)
8                                Howard St at Beale St
9                              Steuart St at Market St

### We notice that we have two types of users, Subscriber users use more than Customer users
### Unfortunately, our dataframe only contains trips made in the month of February.
### I could not make a difference, nor a comparison to have the months which are the most used.
### 0 trips were made on Saturday using the ford bike system.
### The top 3 days when there is more use of Ford bikes are: Thursday, Tuesday, Friday.
### Of the 100% users, 74.6% are male; 23.3% of users are women and 2.1% are from other systems.
### Of the 183,215, recording, 165,869 opt for No for bike sharing during a trip and 17,346 opt for Yes for bike sharing during their trip.
### There is no day when 'customer' type users use the system as 'subscriber' type users
### On Thursdays, both types of user use the bike system a lot more.
### Customer type users travel longer than subscribers.
### ....

## Key Insights for Presentation
We have noticed that the type of user influences the duration of the trip.
We noticed that on Saturdays there is no use of the ford goBike system.
We have noticed that the day influences the number of trips you can have during the day.