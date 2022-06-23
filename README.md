# An Analysis of Kickstarter Campaigns

## Overview of Project

This project works with a dataset on Kickstarters across several different categories. The analysis of said dataset attempts to uncover different patterns, trends, and otherwise noteworthy conclusions. 

### Purpose

Specifically in the excel sheet, notated as the Kickstarter_Challenge, we will be delving into two distinctive deliverables: <Theater Outcomes by Launch Date> and <Outcome Based on Goals>. This narrows down the scope of the dataset to a handful of factors to draw generalized conclusions about specific trends in the outcomes of theater and plays, respectively. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
  
  A Pivot table and an accompanying pivot chart was created with these fields active:
  - Filters: parent category, years*
  - Columns: Outcomes
  - Rows: Date Created Conversion
  - Values: Count of Outcomes
 *  years is an =YEAR() column added on the original Kickstarter dataset sheet. 
  
  This format of pivot table & chart enables us to see the general trernd of theatre outcomes based on their launch dates, sorted by year and month on the table-- as well as visually represented by month on the chart, out of a grand total of 1369 theater kickstarters. Of the total, 839 were successful, 493 failed, and 37 were canceled. 
  ![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/107447038/175249001-c7ac3c95-44c8-4962-8e6c-cb4c35979910.png)
 
### Analysis of Outcomes Based on Goals
  
 After establishing a range of goals (from 0 to 50000+) with increments of 5000, the number of successful/failed/canceled plays were counted. The total number of these projects were calculated by finding the sum; as well as the percentage of each outcomes.  A line chart was made alongside the data, which shows shows the relationship of outcomes based on goals.
  
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/107447038/175249061-4e5f4a23-6e23-47d4-a513-b71d3967e4d8.png)

### Challenges and Difficulties Encountered
  
  I found a lot of functions, especially for the second deliverable, to be quite redundant and therefore prone to typos and 'oops' errors. Most of the time was spent troubleshooting and doublechecking lines to ensure that no miscalculations were being done. Even then, I realized that the Deliverable 2's analysis of mine differs from the one shown at the end of the module 1.5s. I am unsure where I have gotten something wrong, and would appreciate help on the matter.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  
  1. Summer months (late April - early July) are the best times to launch a theater kickstarter, regardless of  year. 
  2. Late fall / winter months (late October - January) are the worst times to launch a theater kickstarter, regardless of year.

- What can you conclude about the Outcomes based on Goals?
  
  The majority of plays that set its goal above the 1000-4999 range had an overwhelming tendency to fail, as reflected by the percentage fail coasting at 80%+ and percentage successful at 20%. Not play kickstarters were ever canceled.

- What are some limitations of this dataset?
  
  This dataset does not show the potential sociological trends between countries. For example, can Deliverable 1's analysis be deepened by juxtaposing it with trends of summer vacations, holidays, etc? Furthermore, this dataset only shows a certain number of kickstarter categories from a limited number of nations. Expanding this further may allow for a more comprehensive, international understanding of kickstarter trends. 

- What are some other possible tables and/or graphs that we could create?
  
  A table/graph that compares the outcomes based on parent categories, as well as subcategories, may allow an insight into the current trends and population preferences towards specific interests. This would potentially allow prospective kickstarters to consider the viability of their project. This could be further enhanced by providing insight on goals, which would assist in kickstarters to actualize the maximum goal they could have without juxtaposing the percentage of their success. 
