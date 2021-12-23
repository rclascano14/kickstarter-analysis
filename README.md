# kickstarter-analysis

# An Analysis of Kickstarter Campaigns!

# Deliverable 3 

# Kickstarting with Excel 

  

## Overview of Project/Purpose 

	The purpose of this project was primarily to showcase our understanding and prowess regarding the use of Excel. Furthermore, through this project, we are analyzing how the outcomes of various campaigns are influenced by launch dates and the goals themselves. All of this is with the goal of enlightening Louise, who is seeking this information due her fundraising experience with her own play. This project was broken down into three separate components. The first of these was “Outcomes Based on Launch Date Chart”, the second, “Outcomes Based on Goals Chart” and the third is this written analysis of the results.  

  

## Analysis and Challenges 

### Analysis of Outcomes Based on Launch Date 

  

### Analysis of Outcomes Based on Goals 

  

### Challenges and Difficulties Encountered 

 

	With the first component, I was asked to first create a new column with the title years. From here, I used the function YEAR(S2, etc). This converted the Data Created conversion from a time to a year. After this, I selected all my KickStarter Data by clicking the top left cell and from here I created a pivot table through the insert tab. With this done, I assigned all the values with Outcomes going to the columns and values, the filters being Years and Parent Category and the rows being Date Created Conversion. I filtered this pivot table to show only successful, failed and canceled outcomes and I filtered the Parent Category to only Theater. I then created a line chart by going to the insert tab and finding the list of charts. This chart visualizes the relationship between outcomes and launch month. As you will see Theater outcomes are best in the month of May and June.  

 
![image_name](Theater_Outcomes_vs_Launch.png)![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/95828604/147184000-c1c48ccd-fac7-41b3-9cf3-b446aab9af47.png)

Next was the second component and for this I needed to visualize the percentage of successful, failed and canceled plays based on the funding goal amount. This required the COUNTIF(S) function. To find the number of successful plays I put I in the function,  “=COUNTIFS(Kickstarter!$D:$D, ">=1000", Kickstarter!F:F, "successful", Kickstarter!R:R, "plays", Kickstarter!$D:$D, "<=4999")”. This gave me the number of successful plays, but I changed the function to say “canceled” or “failed” for those two variables as well. In this section, I ran into the difficulty of manually typing this function out to make sure that each range was correct and accounted for, such as 1000-4999, 5000-9999, etc. After ascertaining this data, it was easy to find the sum of the successful, the failed and the canceled plays through the SUM() function. This showed me that most of the plays had the goal of 1000-4999 and the least had the goal of 45000-49999. In addition, the range with the highest success rate for plays is Less than 1000 with a 75.8% success rate. The range with the least success rate is again 45000-49999 with 0% success for plays, followed by Greater than 50000 with a 12.5% success rate. To find these percentages I simply took the number of successful plays and divided them by the total of both successful, canceled and failed plays. After this I multiplied this number by 100 to find the success percentage and took this number away from 100 to find the failure percentage. There were no canceled plays. I next ran into another challenge as I attempted to create a line chart of the data. I selected all the data and when I created a line chart out of it, there were multiple unwanted lines, which showed aspects such as total numbers. I was able to clean this up adding series to the graph and deleting the unwanted lines.  

![image_name](Outcomes_vs_Goals.png)![Outcomes_vs_Goals](https://user-images.githubusercontent.com/95828604/147184012-3da81ac7-08e8-4922-ac14-359069ac590f.png)

## Results 

Two conclusions that can be drawn about the outcomes based on launch date is that theater outcomes are best in the months of May and June and that in December, you have about just as much of a chance of failing as you do in succeeding with your theater (37-35). Something that you can conclude about the outcomes based on goals is that the largest number by far of successful plays occurs in the goal range of 1000-4999. Another conclusion that can be drawn is that, as the goal range increases, there tends to be less plays overall. Additionally, with plays with a goal of over $50000, there were 14 failed plays as opposed to just 2 successful ones. In short, more plays are successful with a smaller goal. Some limitations of this data set are simple details which would allow for a deeper analysis. For example, the data can be broken down by country, but it doesn’t include smaller geographic locations such as Region, State or County. If they were included, you could find a far more detailed finding of where theaters are successful, and this would influence how many plays were successful at what goal range. Other possible tables or graphs that we could create are to see under what goal range, was more money pledged. Furthermore, instead of months, you could see under what years, you had more successful theaters. There are many tables and graphs that could be created.  
Performing analysis on Kickstarter data to uncover trends


