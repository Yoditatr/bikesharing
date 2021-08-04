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
  
  
