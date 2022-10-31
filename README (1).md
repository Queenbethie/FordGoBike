#  Ford GoBike System Data Exploration

## by Okon Elizabeth Queen¶


## Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.

>There are 183,412 bike in the dataset with 16 features.

> Data in the real world rarely comes clean and so some data wrangling process were carried out to ensure the data was clean before analysis and visualisation. The data was assessed visually and programatically and the following steps were carried out:

- Dropped missing values using pandas'dropna() function.

- Changed datatype for start_time and end_time to datetime using pandas' to_datetime

- created duration in minutes and hours

- Changed datatype for member_birth_yearfrom float to integer using pandas' astype

- Age of the members was gotten from member_birth_year

- Dropped irrelevant columns

- Finally I stored the clean dataset in a csv file
## Summary of Findings

> Gender: From the dataset there were more males than females.

There are two types of riders Customers and Subscribers and most riders are Subscribers

Most users did not share their rides.

Market St at 10th St is the most popular start station in the greater San Francisco Bay area.

San Francisco Caltrain Station 2 is the most popular end station in the greater San Francisco Bay area

Customers ride for a longer period than Subscribers

The older the user, the shorter the duration of the trip.


## Key Insights for Presentation

> How does age affect the duration of the trip?

There is a weak negative correlation between the duration and the age. The older the user, the shorter the duration of the trip.

> How does user type affect the duration of the trip?

The visualisation showed that Customers ride for a longer period than Subscribers although most of the users are subscribers

>How does age and gender affect bike share for trip?

The violin plot showed that for all genders, most young people (between the ages of 20-30) share their trips and older people not as much.