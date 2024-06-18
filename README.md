**Emergency - 911 Dataset**
In this project, we'll analyze Emergency - 911 calls data from Kaggle. (https://www.kaggle.com/datasets/mchirico/montcoalert)

Created by Congress in 2004 as the 911 Implementation and Coordination Office (ICO), 
the National 911 Program is housed within the National Highway Traffic Safety Administration at the U.S. Department of Transportation 
and is a joint program with the National Telecommunication and Information Administration in the Department of Commerce. 
The data contains the following fields:

lat : String variable, Latitude
lng: String variable, Longitude
desc: String variable, Description of the Emergency Call
zip: String variable, Zipcode
title: String variable, Title
timeStamp: String variable, YYYY-MM-DD HH:MM:SS
twp: String variable, Township
addr: String variable, Address
e: String variable, Dummy variable (always 1)

**Business Objective:** 
Improving Emergency Response Efficiency and Resource Allocation for 911 Calls

**Objective Statement**
The primary objective is to enhance the efficiency and effectiveness of emergency response services in Montgomery County by analyzing the 911 call data.
This analysis aims to identify patterns and trends in emergency calls to optimize resource allocation, reduce response times, and improve overall emergency management.

a. Top 5 Zipcodes for 911 Calls
b. Top 5 townships (twp) for 911 calls
c. Examine the 'title' column, to see how many unique title codes are present?
d. Extract and classify the reasons for emergency calls from the "title" column
Using the .apply() method with a custom lambda expression to create a new column called "Reason" that captures the emergency type (EMS, Fire, Traffic)

e. What are the most common types of 911 calls?

f. How do the number of 911 calls vary over time?

g.During which hours of the day are 911 calls most frequent?

h. Which days of the week see the highest volume of 911 calls?

i. How is the geographical distribution of 911 calls?

j. Are there any seasonal patterns in 911 call volumes?

k. How do the types of calls vary by time of day and day of the week?

l. What are the key insights derived from the data?
