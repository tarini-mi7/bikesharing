# Bikesharing with New York CitiBike data
An analysis of CitiBike bike sharing data in New York from August, 2019, with Tableau.

## Overview
The [Tableau Story](https://public.tableau.com/views/BikeShareChallenge_16580830916700/ChallengeStory?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link) for this project shows a summarized view of all the graphs described here.

The framework for this project was to analyze bikeshare data from CitiBike in New York City for presentation to investors to begin a bikeshare program in Des Moines, Iowa. While Des Moines is a long way away from the hustle and bustle of NYC, this analysis might help answer a few key questions:
- Which customer segments use bikeshare programs?
- What areas of a city see the most bikeshare usage?
- What time of day are bikes used the most and the least?
- What is the gender-wise usage distrbution?

## Results
While the demographics of Des Moines may be different from the make up of the citizenry of NYC, a cursory look at the makeup of CitiBike riders may shine light on who Bikeshare might appeal to, regardless of locale.
***
![](https://github.com/tarini-mi7/bikesharing/blob/main/images/customer%20segments.png)

In the above image we can see that more than 3/4 of the users are **Subscribers**, who make regular use of the bikes and are a predictable source of income for the program. Bikeshare program users are also predominantly male, at approximately 5/8 to only about 1/4 female. The remaining 1/8 gender is unknown or undeclared.
***
![](https://github.com/tarini-mi7/bikesharing/blob/main/images/ride%20start%20locations.png)

The above map displays the bike stations from which recorded bike trips started. The size of the circles and darkness of the orange indicate the relative number of trips started at those locations. It is apparent that the bulk of the bike trips are originating in the bustling **commercial heart** of Lower Manhattan, known for towering office buildings, densely packed residential skyscrapers, and entertainment venues. Bike usage is lower in the less densely packed surrounding neighborhoods. 
***
![](https://github.com/tarini-mi7/bikesharing/blob/main/images/peak%20hour%20usage.png)

The above chart displays the number of bike rides initiated during each hour of the day, totalled across the entire month of August. We can see peak usage during morning rush hour and end-of-workday commute times. What is also noteworthy is the low-usage hours between 2 AM and 5 AM. These hours would be the best times to conduct **bike repairs** and **redistribution** of bikes from full stations to less-full stations.
***
![](https://github.com/tarini-mi7/bikesharing/blob/main/images/Trips%20per%20Hour%20by%20weekday.png)
 
The above heatmap helps show weekly usage patterns. Once again we can see the heavy bike usage during **weekday commute times**, and weekend usage is spread throughout the middle of the day. An interesting anomaly is the relatively low bike usage during Wednesday's end-of-day commute. It could be useful to explore reasons for this (system outage, Wednesday holidays in August, something less obvious?), but it could just be an arbitrary anomaly. Also, we can still see such a low-usage time in the early morning hours, every day of the week.
***
![](https://github.com/tarini-mi7/bikesharing/blob/main/images/bike%20usage.png)

To see what proportion of the bikes get heavy usage, we can look at the above stepped-level heatmap. This tiling shows each individual bike in the fleet and is sized, colored, and sorted by its **degree of usage** during the month. In green we can see a small number of bikes that get heavy usage, which will require more regular repair, or possibly even replacement. In shades of red, we can see all the other bikes that get much lower levels of use, and will probably not need to be repaired as often.
***
![](https://github.com/tarini-mi7/bikesharing/blob/main/images/av%20trip%20duration%20by%20birthyear.png)

The above chart of average trip duration by birth year shows two things:
- the bikeshare userbase covers all age demographics, from teenagers to nonagenarians (and older);
- teenagers and early-twenty-somethings enjoy taking much longer bikerides than older users.
***
![](https://github.com/tarini-mi7/bikesharing/blob/main/images/trip%20duration%20usage.png)

The above graph of number of trips by duration shows that the vast majority of trips taken on CitiBike bikes are under an hour in length. More specifically, most trips are under a half-hour in length, with a swift dropoff in number of rides over an hour in length.
***
![](https://github.com/tarini-mi7/bikesharing/blob/main/images/trip%20duration%20genderwise%20usage.png)

The above breakdown of number of rides by duration, separated by gender, makes it even more apparent that more rides are taken by male-identifying customers.
***

![](https://github.com/tarini-mi7/bikesharing/blob/main/images/trip%20by%20usertype.png)

Lastly, the above heatmap reinforces how much of the userbase is dominated by male-identifying, subscribing users. Why this is the case is unclear and warrants additional study.

## Summary
In conclusion, bikeshare services are remarkably popular in busy metropolitan areas, where occupied real estate is densely packed and parking spaces may be scarce. The user base is made up mostly of male subscribers, providing regular income to the program. More outreach should be done to attract female riders, but male users seem to be a reliable market. And, main usage seems focused around morning and evening commute times.

If I were to pursue additional lines of inquiry for analysis and visualization, given the data provided, I would explore:
- trip starting and ending locations during morning and evening rush hour time-windows, to display the flow of traffic between neighborhoods at peak hours;
- average trip duration, by birth year, by gender, to explore if there was any difference in male or female or un-gendered riders as they age.



