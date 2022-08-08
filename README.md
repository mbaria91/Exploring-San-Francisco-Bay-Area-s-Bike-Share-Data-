# (Exploring San Francisco Bay Area’s Bike Share Data)
## by (George Mbaria)


## Dataset

> The dataset consisted of 183,412 rows with 16 columns. There were 9 variables that were numeric in nature and 7 that were categorical. Besides the start_time and end_time being categorized as strings instead the datetime dtypes, all the other categorical variables (start_station_name, end_station_name, member_gender, and bike_share_for_all_trips) were nominal variables.

## Summary of Findings

> In this exploration,the number of rides per start weekday were more on the weekends (Saturday and Sundays) than any other day of the week.
The daily subscribers had completed more than five times the number of rides compared to customers who held single-use or day-ride passes.
The male ratio to female users was definatly great but the duration time taken in the bikeshare is greater in females than in males.
The median age of users was at 20 years to 60 years old and more than 90% of the rides were under 30 minutes.

## Key Insights for Presentation

> In this investigation, I wanted to look at how the Ford GoBikes duration time related to the ages, member genders, weekdays , and the user_type in a manner that could be used to predict bigger profit margins, when could be the best days to set discounts, and who are the target client in the San Fransisco Bay Area.
>The main fetures I focused on was on the duration in seconds, the member genders, the ages that I generated from the members birth year, the start weekday, and the user type.
> After doing a little data wrangling, I started by checking the value count of the start weekday and the en_weekday to see which day seemed to be the busiest. According to the bargraph the weekdays seemed to be the busiest and Thursday being the most dominant. Looking at how the ages related to the gender the boxplot deduces that the genders both male and female together with the others are mostly 20-60 years old. The average minimum age of the member genders in both male and female is 20 years. The maximum ages are ranging at 56-60 years, and the median of the ages are ranging at 30-39 years.
> Introducing the duration in the pointplot, the females on Sunday have the highest average duration time of 1000 sec. followed by the females on Saturday as compared to the male gender. The males on Tuesday have the lowest duration time followed by the females.
> Finally, I intriduced a boxplot, where the female customers on Sunday had the highest duration with over 2000 seconds. The female customers also had the highest median and the highest 1st and 3rd quartiles. The subscribers seem to be maintaining the same medians across all genders with a slight rise on the male subscribers on Saturday.The female gender once again had the highest maximum duration in seconds on Sunday and the male gender on Saturday in the subscribers row.
