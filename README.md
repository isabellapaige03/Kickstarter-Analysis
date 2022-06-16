# Kickstarter Data Analysis

## Overview of Project
Louise met her campaign goal for her play and wants to see how other campaigns did based on their launch date and funding goals.
We will use the data in the Kickstarter spreadsheet to make charts that represent the different critera we want to analyze.

### Purpose
The purpose of this analysis is to uncover trends in the data to determine which campaigns were more successful and why.
## Analysis and Challenges
Louise wants to know how the launch date and goal amount of a campaign could affect how successful it is. According to the "Outcomes Based on Launch Date" chart, launch dates towards the beginning and end of the year have higher rates of failure than those that launched towards the middle of the year. The amount of a campaigns goal slightly affects the outcome of how successful the campaign is. We can see in the line graph "Outcomes Based on Goals", play campaigns with a lower goal amount turned out to be more successful than those with higher amounts.

### Analysis of Outcomes Based on Launch Date
I start the analysis by creating a pviot table for theater outcomes based on their launch date and filtering it by year and parent category. Then I filtered the parent category to only show data for theater campaigns and filtered the columns to display successful, failed, and canceled outcomes. Using the information from the pivot table I created a line graph to make it easier to understand the trends throughout the data. The more successful campaigns had launch dates in May, June, and July.  

### Analysis of Outcomes Based on Goals
For the analysis, "Outcomes Based on Goals", we used another line graph to vizualize the data. Before I could create a line graph I needed to create a new workheet. I added a Goal column to list different projects and grouped them based on their goal amount. I caculated the precentage of successful, failed, and cancelled based on the goal amount. The line graph provides a quick and easy way to see which goal amounts have higher rates of success compared to those with higher rates of failure.
### Challenges and Difficulties Encountered
 I faced some challenges while creating the worksheet for "Outcomes Based on Goals". It took me multiple tries to get the countif function to work correctly. After researching about my problem I was able to come up with a solution and continue with my analysis.

## Results 
The results for our analysis "Outcomes Based on Goals", reveal the campaigns with goal amounts of $4,999 or less had a higher success rate then those with larger funding goals. For the analysis on "Outcomes Based on Launch Date", the results showed that the campaigns that launched durring the months of May through August had higher success rates. We can conclude that the time of the launch date is a factor in how successful a campaign will be. 

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Based on the the chart "Outcomes Based on Launch Date", we can conclude that the time of a campaigns launch date matters. The more succesful campaigns launched between the months of May and August.

- What can you conclude about the Outcomes based on Goals?
Campaigns that had a goal between $1000-$4999, were more successful than those with higher goal ammounts.

- What are some limitations of this dataset? 
There are multiple factors that could effect the outcome of how successful one play was. For example, when looking at the "Outcomes based on goals" chart, we can clearly see that the plays with a goal amount of $4999 or less were more successful. However, the chart doesn't tell us about other reasons the play could have been successful for example, if storyline was intreseting.


- What are some other possible tables and/or graphs that we could create?
We could create a clustered column graph to show the precentages of successful or failed for each goal amount range.