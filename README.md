# kickstarter-analysis
This analysis was performed for helping our client Louise understand trends towards a successful play based on historical data we have for kickstarter projects/shows. Per her request, we performed several analysis on how different campaigns' success, failure, and cancellation rates varied based on their launch dates and funding goals. Please see below for our findings, analysis, and suggestions to future approaches. 

## Analysis and Challenges
The first analysis we performed was to view the number of successful, failed, and cancelled shows based on the month in which they were launched. The purpose of this analysis was to determine whether or not campaigns in general were more likely succeed during certain seasons of the year. We performed a pivot table analysis on our database by filtering the parent category for theater campaigns first. We then placed the "Date Created" column against the campaign "Outcomes" within the pivot table and summed the count of outcomes based on launched months. Please note that we have removed the year and quarter as our analysis wanted to only view correlation between months versus the outcome. We further visualized our results with a line graph (please see below). 


