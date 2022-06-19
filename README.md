# Bikesharing
 Module14_Tableau

# Overview and Purpose
This project aims to cretae a report that helps in the analysis of bikeshare data from CitiBike in New York City. focusing on the data of August 2019. The analysis will be used in a presentation for investors persuading them in starting a bikeshare program in the city of Des Moines.  The investors are interested in gaining information in regards to the following:  
- The user demographic (age and gender)  
- Number of trips taken with breakdowns (by weekday/hour, by gender)
- Trip Duration (general, by gender, by age and gender)
- Customer type (customer or subscriber)
- Most use in city (NYC) by area  

These questions were answered by obtaining the CitiBike data of August 2019 from the available Citi Bike Trip Histories and using the data in Tableau to create visualisations. The visualisations are analysed to draw conclusions that will help the stakeholders in determining if a bikeshare program is needed and will be successful in Des Moines. Another tool used was Jupyter Notebook. The pandas module was used in Jupyter Notebook to convert the tripduration from seconds (an integer) to a datetime value.

# Results
A story was created in Tableau that presents the created visualisations. This story can be found [here](https://public.tableau.com/app/profile/nour.abu.hantash/viz/NYC_Citibike_Challenge_16549918571580/Story1).
Below are the visualisations/results found in the story and their analysis:

## Overall Summary 
Overall, around 2.3 million bikeshare trips were taken in NYC, with 1.5 million male users, 0.6 million female users, and 0.2 million users whose gender is unknown.  
![image1](/Results/8.png)

## **a. Trip Duration or Checkout Times**  
The tripduration line graph demonstrates that the largest number of trips, 1446,752, had a duration of 5 minutes. Most trips were between 0 and 60 minutes most specifically between 3 and 23 minutes. Overall trips between 61 and 180 minutes made up a small amount of the trips.  
![image2](/Results/1.png)

## **b. Trip Duration or Checkout Times by Gender**  
Overall male users had taked more trips than female users. For example at the highest tripduration of 5 minutes 108,087 users of the 1446,752 users (or 73.7%) were male users. Between 61 and 180 minutes tripduration, the male, female, and unknown users were mostly equal as seen by the overlappin line graphs below.  
![image2](/Results/2.png)

## **c. Number of Trips by Weekday/Hour**
The heatmap below demonstrates the highest use of the bikeshare program by each day per hour. The heatmap shows that duriing the weekdays the highest use occurs during the morning between 7 and 10 am (when poeple go to work) and in the evening between 5 and 7 pm (when poeple go home). Durin the weekend the highest use is between 9 am and 5 pm. Overall the use was very low 10 pm and 5 am.  
![image3](/Results/3.png)

## d. Number of Trips by Gender & Weekday/Hour
This heatmap follows the same patterm as the previous heatmap especially where the genders are known. Similar the line graph there is a higher number of male users than female users.  
![image4](/Results/4.png)

## e. Number of Trips by Usertype & Gender over Weekdays
Subscribers to the sevice used the bikeshare service more than non-subscribed customers with weekdays seein more use.  
![image5](/Results/5.png)

## f. Average Trip Duration (in seconds) by Age and Gender
Overall older customers where the gender in known had a larger trip duration than younger customers, yet after the birth year of 1930 the trip durations have become more consistent. Where the gender is unknown, the pattern of average trip duration was inconsistent.  
![image6](/Results/6.png)

## g. Usertype by Hour and Gender
This visual summarizes the previous visuals where it shows that subscribed male users during the morning (7 to 10 am) and evening (5 and 7 pm) were of the highest users.  
![image7](/Results/7.png)

# Summary
Overall the visualisations showed that males have used the rideshare service more by day and hour which is expected as males make up 65% of the service's users. Two suggested visualisations are above (visual f & g) that demonstrate age & tripduration date along with a summary visual (usertype by hour & gender). Based on the results, in the future the company should target female customers overall.
