# bikesharing

## Analysis Overview
The purpose of the analysis was to look at bikesharing data from New York to draw conclusions about the program to help with the pitch to investors who are looking to invest in a bikesharing project in Des Moines, Iowa.

## Resources
- Software: Tableau Public
- Software: Visual Studio Code
- Language: Python
- Library: Pandas

# Checkout Times for Users
![chart 1](https://github.com/tessiertodd/bikesharing/blob/main/Checkout%20Times%20for%20Users.png)
Looking at the amount of time people have bikes checked out for, we see that a large % of people are using the bikes for a short period of time (less than 20 minutes) and while there are people who use the bikes for more than an hour, the frequency is much lower than with shorter trips.

# Checkout Times by Gender 
![chart 3](https://github.com/tessiertodd/bikesharing/blob/main/Checkout%20Times%20by%20Gender.png)
As we split out the bike usage by gender, we see that men are using the service on the most popular time of just under 10 minutes at least 3x more than women.  Once we get to a 45 minute ride, the split between gender disappears, though as mentioned before the number of riders decreases as we approach 60 minutes and beyond.  

# Trips by Weekday per Hour 
![chart 4](https://github.com/tessiertodd/bikesharing/blob/main/Trips%20by%20Weekday%20per%20Hour.png)
We see some of the highest usage on Thursdays from 5-7pm, with some strong usage during the same times on Monday & Tuesday.  Monday to Friday we also see some good demand from 8-9am as people are going to work/school.  Weekends have good usage between 9am and 8pm, but Saturdays have more volume than Sundays.

# Trips by Gender (Weekday per Hour) 
![chart 5](https://github.com/tessiertodd/bikesharing/blob/main/Trips%20by%20Gender%20(Weekday%20per%20Hour).png)
The trends we saw in terms of weekday and time usage can really be seen when we look at this information for males.  You can see some of this same trend with female and unknown, however it is not as pronounced as there are just not as many riders from those two gender groups, when compared to the number of males.  When looking at the male view and comparing to the prior (all genders together) chart, we see the trends we see with male riders impact the total riders such that the trends look very similar.  

# User Trips by Gender by Weekday 
![chart 6](https://github.com/tessiertodd/bikesharing/blob/main/User%20Trips%20by%20Gender%20by%20Weekday.png)
Looking at this chart we can see that subscription riders drive much more of the demand than casual customers.  Its interesting however that with female riders, this observation is the opposite, there are more women riders who are casual customers versus subscribers.  Understanding the differences between different gender behavior can impact the marketing plan for the service.

# Usage by Hour
![chart 7](https://github.com/tessiertodd/bikesharing/blob/main/Usage%20by%20Hour.png)
We can see that there are some peak periods for bike usage - 7-9am as people are getting to work/school mo5st days of the week and 4-9pm as people are heading home after their day or out and about enjoying the city.  There is a lower level of demand from 2-5am, which is a great opportunity for bike maintenance as that is when the most bikes will be available to be serviced.  We can also see there are large differences in the number of bikes you might need at 5pm and even 10pm, which means that many bikes will be sitting idle for a portion of the day. 

# Top Starting Locations 
![chart 8](https://github.com/tessiertodd/bikesharing/blob/main/Top%20Starting%20Location.png)
We can see in the map that the starting stations with the highest volume are in areas where there are many people going to different places (work, school, home, social, ect.) which highlights the importance of choosing the right locations for the bike stations to ensure many people have an opportunity to use as there are many people going by those locations.

# Top Ending Locations 
![chart 9](https://github.com/tessiertodd/bikesharing/blob/main/Top%20Ending%20Locations.png)
The most used ending locations are also in the same very busy (lots of people) locations, which holds as we saw earlier that most trips were very short (many less than 10 mins).  This highlights the importance of having stations located in high people traffic areas, where there are many different reasons people may want transportation.  

# Top Starting and Ending Locations
![chart 10](https://github.com/tessiertodd/bikesharing/blob/main/Start%20and%20End%20Stations.png)
Here are the views of both the start and ending bike stations so that we can that they are both very similar in terms of usage.
Setting up a bike program with the bulk of the stations in a busy downtown core seems to be a strategy that can work quite well.

# Tableau Public Link
Here is the link to the Tableau Public story using the visualizations that were built.
[Link to story](https://public.tableau.com/app/profile/todd7889/viz/citibike_16378989468410/CitibikeReview)

# Summary
## Overview 
Here are some of the high-level conclusions that we have gotten about bikesharing programs through our analysis.  Many of the conclusions that we have drawn can be applied to looking at the opportunity in Des Moines, with adjustments for local differences (ie. difference in population, location of potential destinations).

There are times of the day, and days of the week where bikes are much more in demand than others.  For example Thursday from 5-7pm has the highest demand, with other times and days with very good demand at times that make sense (ex. 7-10am and 5-7pm weekdays when people are commuting from or to their homes).  Understanding the demand at various times will give an idea of required investment in bicycles to satisfy rider demand at peak periods and allow for better maintenance planning (low demand from 2-5am so good time to do maintenance as many more bikes would be available). 

Subscribers tend to drive much more of the demand than casual drivers, so a key part of the success of such of program will required a focus on having a good subscriber program with marketing campaign to attract them into the program quickly.  There is however a difference on types of riders with women, they tend to be more casual customers and so it would be important to also factor that into marketing program to ensure to capture as many customers as possible.

The ride times tend to be quite short with a large % of people riding for less than 20 minutes.  There are however some people riding much longer (60min and more), but the number of rides drop very quickly by 45 minutes.  Interesting enough that as we approach 60 minutes, the split between genders converges and continues at similar level beyond 60 minutes.  Understanding the key usage of riders may have an impact of the type/style of bicycle that should be purchased for the program.

Looking at the most popular start and stop bike stations, we see that most are gathered in busy downtown core, where there is both business as well as tourist sites and other attractions, so that should be considered as the choice for where to have stations setup.

## Recommended Additional Visualizations
- Something else that would be interesting to see along with all the other information we have looked at is the distance that each bike travels (using the start and end stations as a proxy) to get an idea of what % of bikes are used the most and what does that distance look like (measure of usage).  This information could help us understand a little more around what type of maintenance program may be required. This would require some calculations to be made using the information of each station and bike information.
- We looked a lot at all the usage, but another visualization we should look at are the number of bikes that are not being used on different days and times.  This would give us a better understanding of how much of the fleet of bikes are underutilized throughout the week.  The investment in bikes for such a program is very high, and we would want to make sure to have the right level of bike inventory to service the peak periods, but also good to see how many bikes are spending time idle.

