#An Analysis of Kickstarter Campaigns#![Musicals in Great Britain](https://user-images.githubusercontent.com/89410157/130494548-60c4a18b-a7b7-4b91-abae-bec16f1b49d8.png)

![Parent Category Outcomes](https://user-images.githubusercontent.com/89410157/130493769-a37f9741-17ca-45ce-ab0c-2639f0c8b436.png)


## Overview of Project
The project is studying out outcomes of the crowdfunding base on the goal and pledge. 

### Purpose
The purpose of this analysis is to help Louise to know the outcomes of the different campaigns in relation to their launch dates and their funding goals.

## Analysis and Challenges
The analysis was performed by using tables and graphs in order to build relationships and show the result in an easy way to understand and comment. the results are filterable and sortable (by parent categories and year...) in order to help Louise to navigate between the category and year.

The challenge faced in this analysis is the used of the COUNTIFS () function. The function is complex and long, so I spend time to build it, but at the end I was able to control the result by searching all the goal Greater than 50000 and compare the result with the sum of the result displayed by range.  
  
### Analysis of Outcomes Based on Launch Date

In general, the campaigns are successful. If we focus on the Theater, May is a good month to launch a campaign as it counts the large number of success (111). December is a month to avoid while launching a campaign because there is a small number of success as well as February and April.![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/89410157/130670038-3b6747c8-c5dd-4b33-8847-0b6449a4596d.png)

### Analysis of Outcomes Based on Goals

If we focus on the Theater, the outcomes base on goal charts shows that the result between the failed and the successful campaign have an exact inverse result. When the goal is increasing the percentage of success decrease, in contrary the number of fail increase.
Except for the goal between $35000 to $49999 but the number of projects is very small in this range. 
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/89410157/130670099-8aa4fef2-2358-4ba2-b182-d2493f725dc3.png)

### Challenges and Difficulties Encountered

## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?

We can conclude that between May and August is the best period to launch campaigns and May is the pick.
Decembre is not a good month to launch a campaign  

- What can you conclude about the Outcomes based on Goals?
We can conclude that the more the goal is high the less successful the campaigns are. 

- What are some limitations of this dataset?
The dataset may have some outlier that can affect our result and analysis.   
- What are some other possible tables and/or graphs that we could create?

We could create table to compare the goal and pledge base on the launch date, the outcomes base on the duration of the campaign to see if by giving more time the failed campaign will have another outcome with the associated graph. 

We could also build table and graphs base on the outcomes by country compare the goal.

A box & Whisker graphs could also help us see the possible outliers by comparing the mean and the distribution of the goal or pledge.


