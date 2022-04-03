# Bikesharing
## Overview of the analysis: 
Des Moines requested data for a business proposal. August 2019 Citibike data from NYC was reviewed by looking at geographical data as well as data disaggregated by user types and genders to determine if it would be a good investment for Des Moines. Other data points include usage durations, peak usage times, and the key target market.

There is still some more work to be done to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis.

For this analysis, we will use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to:

Show the length of time that bikes are checked out for all riders and genders
Show the number of bike trips for all riders and genders for each hour of each day of the week
Show the number of bike trips for each type of user and gender for each day of the week.
Finally, I need to add these new visualizations to the two I created in this module for your final presentation and analysis to pitch to investors.
Explain the purpose of this analysis.
### Resources:
Data:[CitiBike_Data](https://ride.citibikenyc.com/system-data)
Software: Tableau, Pandas



## Results: 

Cleaning the Data:
Jupyter Notebook was used to change the trip duration data to a datetime field.
![]()

Using two csv file [citibike_tripdata.csv] I have I have analyzed the NYC citibike trip data for August 2019 in Tableau and generated story for the analysis.


[link to dashboard](https://public.tableau.com/app/profile/nishat.sultana7638/viz/NYCCitibikeanalysis_16488811692500/Story1)

Below are the images of data that were analyzed :
### 1.Checkout Times for All Users:
![Checkout Times for users](https://github.com/NishatSultana3538/Bikesharing/blob/main/image/Checkout%20times_users.png)
Bike trips are mostly shorter than one hour.

### 2.Checkout Times by Gender
![Checkout times for genders](https://github.com/NishatSultana3538/Bikesharing/blob/main/image/Checkout%20times_genders.png)
Male users take approximately 3 times more rides than the female users.

### 3.Trips (Weekday per Hour)
![Trips by weekday each hour](https://github.com/NishatSultana3538/Bikesharing/blob/main/image/Trips%20by%20weekday:hour.png)
Highest activity hours are from 5:00 PM to 7:00 PM and require the most resources mobilized.

### 4. Trips by Gender (Weekday per Hour)

![Trips by gender](https://github.com/NishatSultana3538/Bikesharing/blob/main/image/Trips%20by%20gender.png)

Males are high users during the peak hours.

Those rides are mostly taken by male users.

### 5. Trips by Gender and User Type (Weekday per Hour)
![Trips by Gender and User Type](https://github.com/NishatSultana3538/Bikesharing/blob/main/image/user%20trips%20by%20gender%20by%20weekday.png)

### 6. Number of Rides per Hour
Non-peak hours are 1-5 am.
![August peak hour](https://github.com/NishatSultana3538/Bikesharing/blob/main/image/August%20peak%20hours.png)

### Gender breakdown of users
![Gender breakdown](https://github.com/NishatSultana3538/Bikesharing/blob/main/image/Gender%20Breakdown.png)

Males subscribers are the highest users followed by female subscribers.
The activity from 2:00 AM to 5:00 AM is low so this would be the window for bike maintenance.
![]()
Most weekday rides are around 7:00 AM to 9 AM and 5:00 PM to 7:00 PM.
Weekend rides are highest from 10:00 AM to 7:00 PM.

![Gender breakdown]()
65% of the users were confirmed males and 25% were confirmed females.
## Summary: 

Bike Repairs for 1/3 of the Citibikes need to be done during non-peak hours around 1-5 am.
Male subscribers are the highest users and follow the traditional high use times of travel to and from work.
Target market should be males needing transportation to work and weekend activities and push for subscribing to the services.


The data shows high activity of the bike sharing service in New York during the month of August 2019.
The far majority of the rides were in the very busy Manhattan Island, taken by male users during morning and evening rush hours. This implies that Citi Bike services are used as an alternative to public transportation by commuting workers.


## Additional Analysis:
Additional analysis would be beneficial by :

comparing data for different months to determine trends across the year,
including weather data to find the correlation between the weather and the rides.