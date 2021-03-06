# The NYC Citibike Analysis Story

The purpose of the Bikesharing Analysis was to utilize a business intelligence software, Tableau, in order to develop data analysis visualizations that can provide potential investors with valuable insights about the viability of implementing a bike-sharing program in Des Moines, Iowa based upon data from a similar program in New York City. A "NYC Citibike Story" was created within Tableau to build a dynamic and informative data visualization presentation for inclusion within the business proposal. 
 
 [Link to NYC Citibike Story in Tableau](https://public.tableau.com/views/CitibikeChallenge_16371258841600/NYCCitibikeAnalysis?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
 
 
### Resources
- Data Sources: citibike_challenge.csv
- Software: Python 3.7.10, Anaconda 1.7.2, Jupyter Notebooks, Tableau Public 2021.3

## (1) The NYC Citibike Overview - August Data Dashboard
The below dashboard depicts an overview of basic information about the NYC Citibike program including the following key findings based on data from the month of August:

  - We start with a bird's-eye view of NYC with the "Top Starting Locations" map, which reveals the concentration of top locations where customers' bike journeys began
  - Next, our data shifts to the customer-level, where we can understand the population of customers participating in the Citibike program in more detail:
    -  An area plot showing customers' age by the average length of a bike trip tells us that younger riders tend to engage in longer bike trips.
    -  We can see that the total number of bike trips taken in August were 2,344,244
    -  Finally we can view a breakdown of gender within our population of customers:
        - Males represent the largest segment of the entire customer population (1,530,272  or 65.28%)
        - Females comprise approximately 25.10% of the customer population (588,431)   
        - 225,521 customers did not specific their gender and comprised 9.62% of the entire customer population

![image](https://user-images.githubusercontent.com/85533099/142350089-f044d21c-c6d5-4c24-b261-94005c70a195.png)


## (2) August Peak Hours
The next slide in our story shows the peak hours of bike usage in the month of August. This visualization reveals:
  - The start time of 5:00pm yields the largest number of bikes utilized, i.e., 224,566
  - The highest bike usage occurs within the time frame of 5:00pm-7:00pm  
  - The second highest bike usage occurs within the 8:00am-9:00am hour

![image](https://user-images.githubusercontent.com/85533099/142352530-65190da4-9e53-4466-9e97-3c90eb2101a0.png)

## (3) Checkout Time for Users
The next visualization in our story shows the length of time in minutes that bikes are checked out across all users in the customer population. The below graph suggests that the greatest usage occurs within the first hour time block that a bike is checked out, with a peak occurring at the 5 minute mark and subsequently tapering down.  

![image](https://user-images.githubusercontent.com/85533099/142353454-656491be-ac98-46dc-b6fa-aa5a4766e600.png)

## (4) Checkout Time by Gender
The next slide in our story shows the length of time in minutes that bikes are checked out by gender. The line charts for both females and males seem to mirror the above findings with respective peaks at the 5 minute mark and tapering down thereafter. However, bike usage for the group of customers whose gender is unknown appears to be steadier up to the 40 minute mark. 

![image](https://user-images.githubusercontent.com/85533099/142354558-fe99d79f-60c3-413f-b219-645e19401734.png)

## (5) Trips by Weekday per Hour
The next visualization in our story is a heatmap representing the number of bike trips by weekday for each hour of the day. We can see that there are blocks of times and days that indicate a greater concentration of bike trips, i.e., Monday through Friday between the hours of 6:00am - 10:00am; Saturdays and Sundays from 9:00am - 9:00pm; and  Mondays, Tuesdays, Thursdays, and Fridays from 4:00pm - 8:00pm. 

![image](https://user-images.githubusercontent.com/85533099/142557881-696c2f49-1875-4d68-80de-597f7d226d1d.png)

## (6) Trips by Gender (Weekday per Hour)
The next slide in our story is a heatmap representing the number of bike trips by gender and weekday for each hour of the day. Below are the three heatmaps depicting total trips by females, males, and those with an unknown gender. The general pattern of the males and females mirror the previous heatmap results, while those with an unknown gender don't seem to have a specifity around weekdays or hours of their trips. The heatmap for males is consistent with previous results showing the greater volume of bike trips within the male customer population. 

![image](https://user-images.githubusercontent.com/85533099/142559360-ce5dc38b-0101-4f28-a90a-79e072ad838d.png)

![image](https://user-images.githubusercontent.com/85533099/142559375-3acb825c-1d9a-436f-880e-b4fdd20a8b64.png)

![image](https://user-images.githubusercontent.com/85533099/142559384-4ce9d0a2-c4bf-441d-b5e4-807e98f9523c.png)

## (7) User Trips by Gender by Weekday
Finally, the last visualization in our story is a heatmap showing the number of bike trips broken down by gender for each day of the week by each Usertype (e.g., one-time customers and subscribers). This heatmap provides even more interesting and refined results than the previous heatmaps. When we examine the breakdown of bike trips in this manner, we see that one-time customers seem to have a comparable number of bike trips when examining gender, i.e., there appears to be no observable significant difference between the gender categories in volume of bike trips taken during different days of the week. However, this changes remarkably when viewing the data for subscribers, as we see a greater concentration of usage for males across all days of the week, with an emphasis on Mondays, Tuesdays, Thursdays, Fridays, and Saturdays, with females showing a similar trend. It appears that the customers with an unknown gender tend to be one-time users versus subscribers.

![image](https://user-images.githubusercontent.com/85533099/142563939-3bbee57f-0ce6-4119-8966-c0b0347aee06.png)


## Summary and Future Directions

### Key findings
In examining the NYC Citibike Analysis Story, there are some important trends to observe. First, the number of bike trips taken in August is over 2.3 million; younger riders tend to engage in longer bike trips; and males appear to comprise the majority (65.28%) of the customer population utilizing the bikesharing program. The next series of visualizations, in sum, indicate a marked trend in greater usage of bikes during peak rush hour time frames on weekdays as well as Saturdays and Sundays between 9:00am-9:00pm. Data regarding checkout times indicate that bikes tend to be checked out for less than an hour. The last heatmap provides a level of detail that indicates that there appearto be no gender differences within the customer subpopulation of one-time users whereas we see a significantly larger concentration of males being subscribers and using the program somewhat consistently throughout the week.  

### Additional Analyses
The analyses, so far, have focused on gender breakdown regarding bike usage across important dimensions of days and hours of usage. It is recommended that the following analyses be run to gain further understanding about the customer population and build upon the details already acquired regarding usage of bikes within the program:

  - Conduct a basic bar chart examining potential differences in tripduration by usertype (e.g., one-time customers versus subscribers)
  - Repeat the checkout time line graph analysis conducted above by usertype 
  - Repeat the heatmap analysis conducted above examining trips by weekday per hour to determine if these measures vary by usertype


