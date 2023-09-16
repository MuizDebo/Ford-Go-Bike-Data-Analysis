# Ford Go-Bike Exploration Analysis
## Abdulmuiz Adebowale

## Dataset

> The data includes details of over 183,000 trips taken in a bike-sharing program that serves the larger San Francisco Bay area. In addition to duration (secs), the data features also include DateTime, Customer Type, Gender, and a few more variables.

## Summary of Findings

> In my research, I discovered that trips typically last 500 seconds on average and that Tuesdays and Thursdays are the busiest days. The fewest trips have occurred on weekends, while having higher durations than other weekdays. The higher trip records for the eighth and ninth hours of the morning and the seventeenth and eighteenth hours of the evening are something else I discovered to be fascinating. The bustle at the two times of the day may be responsible for this. Over 90% of the rides were taken by subscribers, while more than 70% of all rides were taken by men.

> I discovered that non-subscribers spend far longer on their excursions than regular customers do, and women typically ride for longer than men do. Bicycles can only be shared on excursions by subscribers, and these journeys make up roughly 10% of all rides. The number of rides on any given day does not appear to be impacted by user type. Additionally, compared to subscribers, customer user type tends to spend more time traveling on any given day.

## Key Insights for Presentation

> I exclude other factors from the display and concentrate on the frequency of rides per day, hour and some more. I began by using Seaborn Countplot to examine trip frequencies by day of the week and hour.

> Frequency of rides per day
>- Most rides were taken on Tuesdays and Thursdays. Saturday and Sunday have the lowest trip records.
> Trips taken per hour
>- The 8th, 9th, 17th, and 18th hours have the greatest trip records for the days as observed. This can be attributed to morning rush hour, so it is to be expected.
> Length of trip by customer type and weekdays
>- Both customers and subsribers had the most lengthy trips on weekends (i.e. Sturdays and Sundays)
> Rides per gender
>- Most of the rides(>70%) were taken by Men