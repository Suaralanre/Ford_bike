# San Francisco's BAY AREA FORD GO BIKE SHARING SERVICE

## by Mohammed Suara


## Dataset: Ford GoBike System Data

> Provide basic information about your dataset in this section. If you selected your own dataset, make sure you note the source of your data and summarize any data wrangling steps that you performed before you started your exploration.
> Ford Go Bike is a regional public bicycle sharing system in California's San Francisco Bay Area in a partnership with Ford Motor Company.
> Ford GoBike consists of a fleet of bikes that can be unlocked in one station and returned in any other network station. Thus, this is ideal for one-way trips. These bikes are available for use thorughout the year and riders have access to all bikes in the network.
>  The dataset has the following columns:
1. duration_sec: Trip Duration(seconds)
2. Start Time and Date
3. End Time and Date
4. Start Station ID
5. Start Station Name
6. Start Station Latitude
7. Start Station Longitude
8. End Station ID
9. End Station Name
10. duration_min: Trip Duration(minutes)
11. End Station Latitude
12. End Station Longitude
13. Bike ID
15. User Type (Subscriber or Customer — “Subscriber” = Member or “Customer” = Casual)
16. Member Gender

##### Data wrangling steps include the following:
- drop rows with null/incomplete data
- convert duration_sec to minutes by dividing by 60
- derive hour of the day, day of the week and month of the year from start_time and end_time
- check the number of stations in start and end stations 
- check the unique values in user_type and gender column
- convert the columns to a category data type
- convert the years to ages to make visualization even clearer
- drop rows with ages greater than 100



## Summary of Findings

> I began with univariate exploration of main variables of interest and sequentially moving to other variables. The main variables of interest were Age and duration(min) of trips. The duration exploration revealed most trips were under 40 min and a transformed plot was created to reveal this key information. "Other" gender had a higher average age relative to Male gender with the least average being amongst the females. The Males however spent the least average time on trips and this was a consistent feature everyday of the week as shown by the multivariate exploration. Rather suprisingly, highest average duration spent on trips was by the 80-89 age group. 

> Other variables also revealed some interesting information. For example, there were more trips by subscribers than by customers(casuals) by a very wide margin which is unexpected with most subscribers being males. Most of the subscribers were in the 30-39 age group. The dataset was collected for only the month of February.



## Key Insights for Presentation

> For the presentation, I started with the univariate exploration of the main variables of interest - duration(min) and member age distribution. 
> Then I looked at the relationship between the two variables.
> Then I subsequently looked at a multivariate relationship between gender, day of the week and the duration(min).

