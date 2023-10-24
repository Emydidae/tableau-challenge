# Citi Bike Trends During August from 2020 to 2023

## Hourly & Yearly Data
Looking at various trip-related statistics sorted by year and type of membership revealed multiple interesting phenomenon.
- Where number of trips & average trip distance follow a general upward trend (2020 being the only exception for trip distance), average trip duration has had a consistent downward trend.
	- This means as trips are getting longer & more people are using the bikes, the amount of time those trips takes is actually decreasing.
	- This is the only place where COVID seems to have caused a major change (with avg. trip distance not matching the trend for that year), as everything else looks pretty uniform.
- Casual users use the bikes much more later in the day, likely that many non-member users are tourists (as will be seen more in the next section).
	- Casual users also tend to have greater trip distance & duration.
- Regarding the actual shape of the graphs, each seems roughly independent.
	- Spikes in number of trips during rush hours, but trip duration is actually at its lowest around these times.
	- Trip distance varies quite a bit, but does seem to have slight spikes around rush hours.

## Top Spots - Casual vs. Members
Hoping to investigate the casual vs. member relationship more, these maps show the top 25 stations in August of each year, with the options to sort by year and membership.
- Findings seem to initially support the idea that many casual users are tourists / sightseers, as Central Park consistently has many top stations for casual users, but few or only 1 for members.
	- Interestingly, the center of the island is much LESS popular with casual users.
	- On the other hand, the outer edges of the island and Brooklyn see much MORE traffic from casual users, and less from members.
	- These factors combined may suggest that casual users aren't necessarily tourists, as you'd expect a lot of traffic to other spots in the center of the island. Instead, it may just be people who need transportation on short notice and don't have other options, with the more trafficked locales being areas further apart from each other so it's worth the money not to walk.

## Full Station View
The full station view ranks all the stations found in the data by their usage in August over the 4 years tested. Red stations are in the top 500 out of the 2080 tested (legend shows 2069 due to 11 stations tying for last).
- Trends are mostly what you would expect, far greater usage on the island of Manhattan vs outside, likely due to more people having memberships.
- The stations that are most traveled to are generally very close in rank for departures as well, with more time, a time-of-day slider might be interesting to see if you can see spikes based on when people are coming in / out of the stations.
- Less popular stations on seemed to have similar trip durations to popular ones. This surprised me, as I expected the value from those stations would come from people using the bikes to travel longer distances to get to / from the more busy bike stations, but this suggests most stations likely have about a 15-minute range on average.
- Would also be interesting to know more about how Citi Bikes make money, and compare that with info like the type of bikes used or distances traveled.