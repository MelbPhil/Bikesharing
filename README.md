# Bikesharing

## Overview of Bikesharing
Today, I analysed the NYC CitiBike data from August 2019 and looked for trends regarding tripduration and bike use. To perform this analysis, I converted the 'tripduration' collumn datatype from integer to datetime using Pandas and Jupyter Notebook. I then used Tableau to sift through the data, and created a story that outlines my key findings. [Click here to view my Tableau dashboard](https://public.tableau.com/app/profile/mel.phillips/viz/NYCCitiBikeTripdurationAnalysis/CitiBikeDataAnalysis?publish=yes)

Here I will discuss my key findings:

## Results

### Peak CitiBike Hours

![Peak_CitiBike_Hours](https://user-images.githubusercontent.com/106599446/188337705-f568e6ec-6f6a-4c6a-9fd0-d2cdb3add250.png)

The chart above shows how many bikes are rented at each hour of the day throughout the month of August. What is perhaps most noteworthy here is that the majority of riders are using the bike around 7-9am and 4-7pm, which are generally considered prime communiting hours. On top of that, there are significanly more riders at the end of the workday as compared to the beginning; perhaps people do not have as much energy for riding in the morning?

### Tripduration

![Tripduration](https://user-images.githubusercontent.com/106599446/188337805-c21218de-9406-463c-93cd-1a97d4223672.png)

The chart above shows the number of rides vs. the duration of each trip. Most CitiBike rides are just 5 minutes long, and the vast majority are less than 45 minutes. This supports that bikes are predominantly used as a form of communiting, rather than as a means of exercise or for other long trips.

### Gender Breakdown

![Gender_Breakdown](https://user-images.githubusercontent.com/106599446/188337815-e0761537-97f6-499a-90d0-21ea8db7f4d6.png)

The pie chart above breaks down the users by gender. The vast majority of users are males (1.5 million), then female (588k), then unknown (225k).

### Tripduration by Gender

![Tripduration_by_Gender](https://user-images.githubusercontent.com/106599446/188337834-64c9705f-ee1f-435d-90ae-b1741c911af6.png)

When viewing the duration of trips by gender the trend holds across all generally that shorter trips are preferred as compared to longer trips. Whats interesting here, is that the unknown gender category peaks in duration from rought 5-29 minutes. It seems that for people that do not disclose their gender tend to ride for longer on average. Perhaps these people are not CitiBike subscribers? And thus are using the bikes for longer trips? More analysis needed.

### Starttime Heatmap

![Starttime_heatmap](https://user-images.githubusercontent.com/106599446/188337873-0ebfea65-28b1-4595-ad28-86cc9d6d37c8.png)

The heatmap above shows which days/times are most likely to see riders. The trend holds that the majority of users during the middle of the week use the bikes during "commuting hours". however, on the weekend, there is a more even distribution throughout the day. What is also worth noting here is that there are more riders earlier in the afternoon on Thursday and Friday, perhaps showing that people are leaving work earlier on those days? Finally, people seem to not ride home as much on Wednesdays as compared to the other days of the week..? Strange!

### Starttime by Gender Heatmap

![Starttime_Gender_Heatmap](https://user-images.githubusercontent.com/106599446/188337888-c510b040-4540-477c-bba4-a07d8b19baa5.png)

This heatmap breaks down the days/times that are most likely to see riders by gender. What was most intersting to learn here was that people in the 'unknown' category were much more likely to ride on the weekends (particularly saturday) as compared to any of the other standard times. This is perhaps further evidence that these are non-subscribers. 

### Subscribers vs. Non-Subscribers

![Subs_vs_nonSubs](https://user-images.githubusercontent.com/106599446/188337914-74d42ff8-6750-45f5-8bc7-a685983f6228.png)

This chart breaks down customers (non-subscribers) and subscribers by gender and which days they ride. This shows that most subscribers do indeed disclose their gender, and that the share of non-subscribers that do not disclose their gender is quite high. Most of these unknown non-subscribers do tend to ride on the weekend.

## Summary

There is much that can be learned from this data about peoples use of CitiBikes as a means of commuting. When setting up a biking service in another city, one should be careful to ensure that people can use this service as a means of public transportation to maximize users. Further analysis should be done on the location of bikes as compared to places that people work. Are work "hubs" stocked sufficiently to accommodate evening commuters? If not, this could be the source of profit loss!
