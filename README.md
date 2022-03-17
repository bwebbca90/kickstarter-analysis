# kickstarter-analysis
Module 1 Challenge 
# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this analysis is to provide information for a requestor on the results of different campaigns and how their outcomes correlated to their launch date and funding goals. The analysis can be found at the following link: https://github.com/bwebbca90/kickstarter-analysis/blob/main/Kickstarter_Challenge.xlsx 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![Image of Outcomes Based on Launch Date](<./resources/Theater_Outcomes_vs_Launch.png>) 

### Analysis of Outcomes Based on Goals
![Image of Outcomes Based on Goals](<./resources/Outcomes_vs_Goals.png>) 

### Challenges and Difficulties Encountered
During analysis, there was a challenge encountered in the Outcomes Based On Goals worksheet where creating a range for the goal numbers required more than one criteria range to be listed in the cell. Using the COUNTIFS function, the "successful" campaigns were pulled for all the campaigns under the "plays" subcategory. However, to pull the successful campaigns within a specific range of goals required two separate criteria ranges as "more than or equal to 5000" and then also "less than or equal to 9999". Once this was solved, the process was duplicated for all rows in the successful column, the failed column, and the canceled column. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date? One conclusion that can be drawn regarding the Outcomes Based on Launch Date analysis is that campaigns launched in the late spring to summer months (May through August) had a significantly higher rate of success than those launched in the winter. Another conclusion that can be drawn from this is that it is more popular to launch theater kickstarters during the summer months. This second conclusion is likely due to the average 40% chance of failure when launched between November and January, probably correlating to increased holiday expenditures.

- What can you conclude about the Outcomes based on Goals? A conclusion that can be made is that plays with goals set under $5000 have the highest success rate. 

- What are some limitations of this dataset? There are a few significant limitations of this dataset. One is that Kickstarter as a site was not founded until 2009 so there is not much significant historical data until 2014, which is the first year that plays, for example, had more than six campaigns over the course of the year. Another is that this dataset only covers one crowdfunding website and does not cover other websites noted for crowdfunding creative efforts like Indiegogo or Patreon. We are also not provided a time frame spanning from campaign to release, or how many campaigns ended up requiring a refund of their supporters. 

- What are some other possible tables and/or graphs that we could create? Other tables or graphs we could create are the popularity of theater or play crowdfunding in countries other than the United States as we know our requestor was possibly interested in such data for Great Britain as well at a later date. We could create a graph for the popularity of backers supporting theater or play crowdfunding to indicate whether we see a high amount of backers averaging small donations or a small amount of backers averaging large donations per donation group to generate marketing efforts targeting a specific demographic of backers.
