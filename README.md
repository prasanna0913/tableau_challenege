# Tableau-Challenge

# Summary:
* From the citi bike page, 2019 and 2020 JC_citibike_tripdata are considered and combined into one CSV file using jupyter notebook. 
* The combined CSV file is read using the TABLEAU which is used for creating the Visualizations, Dashboards and Stories.

# Data:
The data used for this project were collected from Citi Bike Data, The data includes following information:
*   Trip Duration 
*	Start Time and Date
*	Stop Time and Date
*	Start Station Name
*	End Station Name
*	Station ID
*	Station Lat/Long
*	Bike ID
*	User Type (Customer = 24-hour pass or 3-day pass user; Subscriber = Annual Member)
*	Gender (1=male; 2=female)
*	Year of Birth
*	Age (as of 2021)

# Visualizations:
*	Popular stations to Begin Ride.
*	Popular stations to End Ride.
*	Peak hours of Ride-summer months 
*	Average trip duration Vs Age
*	Number of Rides Vs Age
*	Avg Trip duration Vs Gender 
*	Avg Trip duration Vs Age & Gender
*	User type Vs Gender

# Data Cleaning:
* Considered 2019 and 2020 JC_Citibike_tripdata. 
* Combined the csv files in the Jupyter notebook.
* While cleaning up the combined CSV file, removed the data from 'Gender' column, where gender is read as Unknown. 
* Then the complete file is read into the tableau. 

The task in this project is to aggregate the data found in the Citi Bike Trip History Logs to build a data dashboard that can answer the following questions:

# A static map that plots all bike stations with popular locations to start and end a journey
![start_stations](Images/start_stations.PNG)
![end_stations](Images/end_stations.PNG)

From the above plots, its clear that "Grove St Path" is the most popular start station and the end station to start and end their rides.
Probably this is a big station with more number of citi bikes available for rides.

Solution: Few stations have less than 10 rides. These stations should be promoted by publishing adds or can encourage the riders by offering discounts.

# What are the peak hours in which bikes are used during summer months?
Number of rides for each Month broken down by time(hour) and Year (2019 & 2020). Color shows details about Year. The marks are labeled by number of rides. The view is filtered on Month, which keeps June, July, and August.
![Morning_hours](Images/summer_hours_morning.PNG)
Inference: When we look at the plot, the most preferred morning hours for the rides are between 7AM to 9AM. Peak hours are at 8AM.
Of the three months, maximum number of rides(5,237 ) were noticed in the month of August. 
![Evening_hours](Images/summer_hours_evening.PNG)
In the Evening, the most selected hours for the rides are between 5PM to 7PM. The peak hours are at 6PM.
Of the three months, maximum number of rides(4,926) were noticed in the month of August. 


# Moving to the next question, Did the pandemic affect the citibike rides during the summer months of 2020?
Certainly, the number of rides were comparatively less in 2020 than in 2019.
However, during the summer months, the intensity of the pandemic was gradually reducing. This might be the reason for a gradual increase in the number of rides in the month of August 2020.

Observation: Seems August month is the busiest month. 
Comfortable time for the Rides are 8AM and 6PM.

# What is the gender breakdown of active participants (Male v. Female)?

Active participants are males. But the total trip durations are on the higher side for females. 

![summer_rides](Images/summer_rides_gender.PNG)

Looking at the plot, females have greater trip duration than males. 
The graph is plotted across the summer months (June, July, August) for the years 2019 and 2020.
In Spite Of the pandemic situation in 2020, rides are more in 2020 than in 2019 for both males and females. 

![rides_gender](Images/gender_VS_ride.PNG)

Considering the total number of rides, female have a fewer number of rides than males.
![rides_age_gender](Images/avg_td_age_gender.PNG)

Though the number of rides for females is less than males, their duration of rides are high. Seems that trip duration was decreasing with increase in age. Age 20 and under category has greater trip durations. 

# How does the average trip duration change by age?

![trip_duration_VS_age](Images/trip_dur_age.PNG)

The plot of Avg Trip duration(min) against Age(yrs). Color shows details about age (group). The view is filtered on age, which ranges from 17 to 70.

# Inference:
The average trip duration is more for the riders with the age group of 17yrs to 22yrs.
Surprisingly, avg trip duration is on higher end for people with 52yrs age group. 

![rides_VS_age](Images/rides_VS_age.PNG)

When we look at the plot of number of rides Vs age, number of rides are more for people who are above 25yrs of age. Interesting part of the plot is that people of age 52yrs are enjoying the citi bike rides, as their total number is on the higher end. 

# Solution: 
 From the above two plots (trips Vs age), we see that teens participation is comparatively less. So, to draw their attention, we can try giving concessions on the student ID cards so that the amount they need to pay would be less. Generally, the younger generations account higher number of rides and average duration of the trips which improves the statistics. 

# Estimating the number of rides for Users (Customer or subscriber) Vs Gender?

![usertype_gender](Images/usertype_gender.PNG)

Of the total number of rides, visualization shows that subscriber rides are more than customer rides. However, number of rides for males are more than females. 

# Setup:
*	Tableau public is used to develop the visualizations

# Status
Project is finished

# Contact
D. Sai Prasanna

