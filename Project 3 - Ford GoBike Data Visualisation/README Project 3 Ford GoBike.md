# Ford GoBike Data Exploration
## by Tayo Olowu


## Dataset

This data set includes information about over 150,000 individual rides made in a bike-sharing system covering the greater San Francisco Bay area within the month of February, 2019.
It includes information about where the trip started, where it ended, and how long it lasted. It also includes basic information about the customers such as their age and gender.
The dataset can be found from Udacity [here](https://video.udacity-data.com/topher/2019/April/5ca78b26_dataset-project-communicate-data-findings/dataset-project-communicate-data-findings.pdf).
More information about bike-sharing can be found on [Wikipedia](https://en.wikipedia.org/wiki/Bay_Wheels), and on [these](https://www.moneycrashers.com/bike-sharing-best-bike-share-programs/) [websites](https://www.lyft.com/bikes/bay-wheels).


## Summary of Findings

In the exploration, I found that a majority of the users were male and aged between 20 to 40.
Most of the trips were fairly short in duration, although some extreme outliers were in the dataset.
The longest trip durations were mostly due to the youngest and oldest users in the dataset, and early start times.
I also found that there were two times of each day during which the number of trips taken increased.
These were around 8AM and 5PM respectively.
The trend did not extend to weekends (Saturdays and Sundays).
I guessed that the reason for this was due to users going to work early in the morning and leaving work late in the afternoon.
I found evidence for this by exploring the number of trips started at a given hour, for each weekday.
As predicted, Saturdays and Sundays showed only one highest peak in number of trips taken in the afternoon.
I also found that a majority of the users were Subscribers and did not enroll in the Bike-Share-for-All programme.

Finally, I checked a few start-station and end-station pairings and
was able to determine the start-destination pair with the longest average trip duration, and
also the one with the most usage, journey-wise.


## Key Insights for Presentation

For the presentation, I'll focus mostly on how the start hour influences the number
of trips taken, and how the number of trips ended at a given hour of the day lines up
almost neatly with the number of trips started.
I'll also focus on how the number of trips taken for each hour relates to the day of the week.
I'll explore the factors that correlate with long trip durations,
then briefly highlight the start-station and end-station pairs (aka routes) with the most usage
and the longest average trip duration.
