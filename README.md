# _Des Moines Iowa Bikesharing Program Proposal_

![alt text](https://github.com/Yoditatr/bikesharing/blob/main/Image/Citibike.jpg?raw=true)

# _Overview of the analysis_

The Purpose of this analysis is to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis. Hence, using August 2019 data from New York City's Citi Bike-Sharing Program as my case study I have made a tableau worksheet analysis and storyboard to convice that the idea of bikesharing is a profitable business in the city. 

# _Results_

## Data Cleaning 

Before I had began the analysis I will convert the datatype of the "tripduration" column from an integer to a datetime datatype to get the time in hours and minutes by using Pandas in jupyter notebook. Becuase using Tableau instead of Pandas to change the datatype of the "tripduration" column to a "Date and Time" may take more time and might be less effective. 

![alt text](https://github.com/Yoditatr/bikesharing/blob/main/Image/Image/DF.PNG?raw=true)

## Checkout Times for Users

When analyzing the NYC citibike data to figure out a specific trip duration (meaning what is the average trip duration for the majority of the riders), the highest number of riders that is 146,752 have riden the bikes for 5 minutes tops. Ingeneral the majority of the trips have taken less than 30 minutes. 

![alt text](https://github.com/Yoditatr/bikesharing/blob/main/Image/Image/Checkout%20times%20for%20users.PNG?raw=true)

## Checkout Times by Gender

Similary, I have undertaken the analysis for the checkout time by Gender, and the results are consistent to the checkout by users analysis and the majority of the trips have taken under 30 minutes. But, generally males have taken the enormous majority of the trips than the female or the unknown gender had.  

![alt text](https://github.com/Yoditatr/bikesharing/blob/main/Image/Image/Checkout%20times%20by%20Gender.PNG?raw=true)

## Trip by Weekday per Hour

The peak hours of bake utilization during weekdays are between 6am-9am and between 5pm-8pm. During the weekend, users have consisten usage of rides (average of 30k and less) between 9am - 7pm. 
 
![alt text](https://github.com/Yoditatr/bikesharing/blob/main/Image/Image/Trips%20by%20weekday%20per%20hour.PNG?raw=true)

##  Trips by Gender (Weekday per Hour)

Not suprisingly Males have taken the majority of the rides and it is between the 6am-9am and between 5pm-8pm for the weekdays and 9am - 7pm during weekends. The same pattern was seen for female riders except that the volume of rides is much less than the male riders. For the unknow gender type, compared to the whole data set, few riders were there to comeup with a concrete analysis. These riders could perhaps be tourists whose gender profiles isn't available.  

![alt text](https://github.com/Yoditatr/bikesharing/blob/main/Image/Image/Trips%20by%20gender%20by%20weekday%20per%20hour.PNG?raw=true)

## User Trips by Gender by Weekday

Anlayzine this segment I have found out that the majority of riders are commuters and are more likely to take the citi bikes on a day to day basis. We have 1.9 million subscribers compared to just over 400k non subscribing riders. As known the majority of the rides here are by subsicribing male riders, and here the unknown gender rides being non subscribing customers strengthens our assumption of these riders being tourists whose profiles aren't being available or left blank. 


![alt text](https://github.com/Yoditatr/bikesharing/blob/main/Image/Image/Trips%20by%20gender%20by%20weekday.PNG?raw=true)
