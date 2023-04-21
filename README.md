# Bike-Sharing in Des Moines

## Overview of the challenge

After having a delightful vacation in New York City, I realized that a large key ingredient to the magic was touring the city on bicycles from the bike-sharing company Citi Bike.  I would like to start a bike-sharing company in my hometown of Des Moines, Iowa.  Utilizing NYC Citi Bike data from 2019, I would like to show potential investors how it worked in NYC and how it might work in Des Moines. 

In this Challenge, I used Python, Pandas, and Jupyter notebooks to do the extract and transform phases. Specifically, I extracted the NYC Citi Bike data from August of 2019  from a CSV file into a DataFrame.  I then transformed the trip_duration column into a datatime data type.  I then exported the new DataFrame as a CSV file.  I lastly, created several visualizations in Tableau to create a story that we can present to the investors.

## Resources
- Python, Pandas, Jupyter notebook, Tableau Public 
- 201908-citibike-tripdata.csv

## Story Link
[Tableau story link](https://public.tableau.com/shared/TNB3Q33G7?:display_count=n&:origin=viz_share_link)

## Results

The vast majority of trips last less then one hour
![Trip Duration](https://github.com/BlazeMedina/bikesharing/blob/main/images/Trip%20Duration%20by%20Gender.png)

Peak checkout times corollate to the start and end times of the "standard" workday.  ![Checkout Times by Gender](https://github.com/BlazeMedina/bikesharing/blob/main/images/Checkout%20Times%20by%20Gender.png)

Males rent more bikes than females. The rental times for all genders through the weekdays occur around 0800 and 1700.  During the weekend the rental times are during daylight hours of 1000-1800.
![Trips by Gender](https://github.com/BlazeMedina/bikesharing/blob/main/images/Trips%20by%20Gender.png)

Majority of rentals occur during the weekdays.
![Trips by Gender by Weekday](https://github.com/BlazeMedina/bikesharing/blob/main/images/Trips%20by%20Gender%20by%20Weekday.png)

The ending locations are very near the starting locations.
![Starting Locations](https://github.com/BlazeMedina/bikesharing/blob/main/images/Top%20Starting%20Locations.png)
![Ending Locations](https://github.com/BlazeMedina/bikesharing/blob/main/images/Top%20Ending%20Locations.png)

By visualizing the bike utilization, one can prioritize which bikes to be scheduled for assessment and service.
![Bike Utilization](https://github.com/BlazeMedina/bikesharing/blob/main/images/Bike%20Utilization.png)
