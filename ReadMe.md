# Boston Bluebikes Data Exploration & Visualization
## by Ayman Metwally


## Dataset

* This project explores a dataset containing about 2.5 million bike trips across Boston City through 2019 including start & end stations & times, user types, genders & birth years.
* You can find it [here](https://www.bluebikes.com/system-data).

## Features of Interest

* When are most trips taken in terms of time of day, day of the week, or month of the year?
* How long does the average trip take?
* Does the above depend on if a user is a subscriber or customer?
* What is the most active stations?


## Summary of Findings

* September has the most trips over the year with 363185 trips with a perdent of 14.4%.
* The third quarter of the year has the most trips with a combined percent of 40.4%.
* September 20th has the most trips over the year with 14282 trips.
* Wednesday has the most trips over the week with 389441 trips.
* Weekends has the least trips comparing to workdays.
* Hourly distribution has two peaks @ two timeframes (08:00-09:00) & (17:00-18:00) hours.
* There were some outliers in trips durations that have been dropped from the data (percentiles 98%).
* Trips duration distribution is much skewed to the right (shorter trips) with a peak @ (6:9 mins) bin.
* There were some outliers in users age that have been dropped from the data (percentiles 99%).
* Users Age distribution is skewed to the right (younger users) with a peak @ 25 years old, except for a peak anomaly @ 50 years old bar.
* 80% of users are subscribers & the other 20% are customers.
* 65.99% of users are males, 23.67% are females & the remaining 10.34% are unknowns.
* Some insights into 50 years old frame:
    1. It looks like that the distribution of the data is not changed much in the 50 years old frame, except that almost all of them are customers with undefined gender.
    2. So, the only explanation I can think of is that when a customer does not enter his birth year, the default is set to 1969 which leads to 50 years old.
* The top two start & end stations are:

No. | Station | Start Times | End Times
--- | --- | --- | ---
1 | MIT at Mass Ave / Amherst St | 60149 | 56255
2 | Central Square at Mass Ave / Essex St | 50345 | 50861

* The top two common trips (from start to end) are:

    1. From **MIT Pacific St at Purrington St** to **MIT Stata Center at Vassar St / Main St** with 4942 occurrences
    2. From **MIT Stata Center at Vassar St / Main St** to **MIT Pacific St at Purrington St** with 4884 occurrences
    
* Some insights into these top two trips:
    1. Trips on each working day are almost twice that on each weekend days
    2. Trips from **MIT Pacific St at Purrington St** to **MIT Stata Center at Vassar St / Main St** has two peaks @ two timeframes (08:00-09:00) & (09:00-10:00) hours
    3. From **MIT Stata Center at Vassar St / Main St** to **MIT Pacific St at Purrington St** has two peaks @ two timeframes (17:00-18:00) & (18:00-19:00) hours
    4. These suggest that people who lives near **MIT Stata Center at Vassar St / Main St** go to their work near **MIT Pacific St at Purrington St** in the morning and return at the end of the day using bicycles.
 


* June has the highest average trips duration per month.
* Saturday has the highest average trips duration per week.
* Weekends (Saturdays & Sundays) have longer trips comparing to workdays.
* Hourly average trips duration distribution has two peaks @ two timeframes (02:00-03:00) & (14:00-15:00) hours with an average of about 17 mins.
* The age of 50 years old has the highest average trips duration with an average of about 24 mins.
* Subscribers have much shorter trips duration on average than customers who have a larger variety of trips duration.
* September has the most trips over the year for subscribers but it's August for customers.
* Males have slightly shorter trips duration on average than females.
* The 50 years old anomaly makes it difficult to compare user types in terms of age.
* Males & females have almost the same age distribution.
* Subscribers have much more trips than customers through all months.
* Males have much more trips than females through all months.

* Subscribers have much shorter trips on average duration than customers through all months & all weekdays.
* Males have shorter trips duration on average than females through all Months & all weekdays.
* Heatmaps show some differences on avergae trips duration distributions between both types.
* Subscribers are used to have longer trips from 2 am to 4 am & slightly shorter trips thoughout the day on work days whereas customers are used to have shorter trips from 4 am to 9 am & longer trips thoughout the day on work days.
* Both types have the same distributions on weekends except that customers have longer trips.
