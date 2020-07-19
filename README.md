# Data Analysis for Louise 

## Overview of Project
In this project we broke down the data to provide better insight into more trends. First, we looked at correlations between the launch date and whether past campaigns were successful, failures, or outright canceled. We then put these values into a pivot table filterable by Years and Parent Category and represented it in a line graph. We used the YEAR function to make a year column for this. Then we used the COUNTIF function to find the percentage of successful, failed, and canceled campaigns that fell within the range of certain fundraising goals. This gave us a better understanding of how campaigns with particular fundraising goals fair historically. We then represented the perecentages in a line graph.

### Purpose
The purpose of this analysis was to provide Louise with additional visualizations and analysis of the data to help her better understand past Kickstarter campaigns. In particular, it broke down the data to glean insight into trends associated with both launch date and success and the percentage of campaigns that were successful in relation to their fundraising goals. By doing this, Lousie will better understand which times of year are best to launch a kickstarter campaign and what how likely her campaign is to succeed given different monetary goals.

## Analysis and Challenges
I had an incredibly difficult time transferring over time data into a pivot table for the first Deliverable. Eventually I figured out how to represent the table in the Date format followed by military time. The pivot table initially represented the rows to me organized by month, but I struggled quite a bit to figure out how to ungroup them. Eventually I watched a video and figured out that I just needed to right click. The largest issue I had was with graphing the Outcomes Based on Goals chart. I tried to do this initiallly without putting the data into a pivot chart. Excel would only plot the first column of data accurately, and then all other lines would be represented as straight lines at the 100% marker. This problem was resolved when I put the data into the pivot table and then made a pivot chart.

### Analysis of Outcomes Based on Launch Date
I was able to glean several trends from graphing the launch date. Campaigns launched in May, June, and July see the greatest success. There is a steady decline in success for campaigns started from May until December with only a little bump October.The end of the year and December in particular is the worst time to launch a campaign. I would recommend Louise launch her campaign in May. 



### Analysis of Outcomes Based on Goals
Lower campaign goals have a high degree of desirable outcomes. This tends to decrease as the goal gets higher hitting a lowpoint around goals of 25,000 to 35,000. However there seems to be a fundraising sweetspot between 35,000 and 45,000. However, this value is fairly high. For Lousies purposes, I would recommend she keep her fundraising goals below 15,000 and preferable below 5,000.

### Challenges and Difficulties Encountered
I had a very hard time manipulating the graph for Outcomes Based on Goals. Things like getting the y-asix to read as a percentage and have "5000 to 9999" in the right place on the x-axis was extremely difficult.

## Results
Louise should launch her Kickstarter in the Summer, preferably in May. Also, she should not launch her Kickstarter in December and around the end of the year.
Louise should keep her fundraising goals below $4,999 for the purposes of her project based on incremental modeling around the success of kickstarter campaigns based on goal amount. It should be noted that the data does not correct for differences in exchange rate between currencies. Therefore data is likely somewhat innaccurate since it does not account for this. The data set is limited. Many of the countries have very few Kickstarters, so the data is skewed heavily towards America and Britain, however this isnt really an issue for Louise. We don't have any data that tells us anything about the types of people that are pledging money. Therefore, there is not much that can be gleaned about who outreach should be directed towards. We also cant break down the plays by genre. A Sub-subcategory would allow us to further narrow down the data to those plays most relevant. We could create tables of central tendency and spread as well as quartiles. We could then represent these values in a Box and Whisker graph.
