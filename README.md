# bikesharing
Dashboard link to citibike visualization in [Tableau Public](https://public.tableau.com/views/bikesharing_16524026126010/citybikeAnalysis?:language=en-US&:display_count=n&:origin=viz_share_link).

## Overview
"The Team" was tasked to review rider data collected by citibike, a bicycle ride share program in New York, to spot service trends amongst their user base. Of interest is a dataset from August 2019, a typically peak time in service utilization. Pulled from this information is visualization capitalizing on the program Tableau that focuses on subscriber type and ride duration with an hourly and weekday breakdown by demographics.

## Results
Figure 1.) Composite Dashboard Highlighting Ride Duration, Membership and Demographics.

![](Resources/Fig1.png)

* Checkout Time for Users displays the ride duration (Tripduration) as a function of bicycle count over a three hour window. The visual result is that most bikes are used for approximately a 5-minute trip which then rapidly drops off before the 1-hour mark.
* Customer Type highlights that over 80% of the bike ridership is annual subscribers vs. short-term customers.
* Gender Breakdown showcases the Gender breakdown of ridership. Women account for roughly 25% of the user base.
* Checkout Time by Gender follows Checkout Time for Users in metrics displayed, separated out by Gender. Of note is that drop-off slope for Women riders is not as steep for Men after the 5-minute peak.

Figure 2.) Trips by Weekday per Hour.

![](Resources/Fig2.png)

* This heat map indicates that for Monday through Friday, peak bicycle utilization is between 6-9 AM and again at 4-7 PM. Weekends activity shows a rising spread starting around 10 AM, cresting around noon that then tapers off slowly to 7 PM. It can also be inferred that overall usage steadily increases after Thursday leading in to the weekend and drops off on Monday.

Figure 3.) Trips by Gender (Weekday per Hour).

![](Resources/Fig3.png)

* Paralleling Trips by Weekday per Hour, this heat map breakdowns by Gender and highlights similar day by day usage. Of note is that Men make a heavy proportion of Weekday ridership.

Figure 4.) User Trips by Gender by Weekday.

![](Resources/Fig4.png)

* Again, focusing on demographics but now separating out Annual Subscribers reveals that bicycle usage is predominant with Male Annual Subscribers during the weekdays.

## Summary

With an Annual Subscriber base that composes over 80% of bike utilization, it is apparent that for citybike their primary in-service duration for a bicycle is focused between 5 to 30 minutes. Men account for a majority of users, with their ridership heavily focused on the Weekdays in the windows right-before and right-after normal business hours.

Two additional analyses that would be informative within the dataset is a bucketing by age groups for Subscriber count and Ride Durations by both minutes and Weekdays.



