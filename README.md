# Overview of project 
Louise would like to know how theater launch dates and fundraising goals impact campaign results. 
# Purpose
Performing analysis on Kickstarter data to compare Theater Outcomes based on Launch Date and Goals in order to achieve the optimal fundraising result in the future.  
# Analysis and challenges 
Analysis of outcomes Based on Launch Date: A pivot table was constructed by selecting outcomes in columns and values, date created conversion in rows, and parent category and year in filter. Then I created a line chart to perform an analysis between the successful, failed, canceled theatre outcomes in different launch months.   
<br />The number of successful outcome and Failure outcome for the theater is the highest during the month of May.  
![Theater_Outcomes_vs_Launch.png](Theater_Outcomes_vs_Launch.png) 

Analysis of Outcomes Based on Goals: A table was constructed to demonstrate the number and percentage of outcomes (successful, failed and cancelled) according to different goal. I performed the analysis by comparing the percentage of successful, failed and canceled rate to different fundraising goals. 

<br />The successful rate and failure rate has an inverse relationship.  Sucess rate is the highest when the goal is less than $1000 and is the lowest when the goal is around $45,000 to $49,999.
![Outcomes_vs_Goal.png](Outcomes_vs_Goal.png)
# Challenges 
Challenges of Outcomes Based on Launch Date: Possible challenges are selecting the right date in the pivot table
<br />Challenges of Outcomes Based on Goals: A possible challenge is to correctly use the countifs function and selecting the right column.  

# Results
What are two conclusions you can draw about the Theater Outcomes by Launch Date?
<br /> Based on the analysis May to August had the best outcome, therefore it may be a good time for Louise to start a fundarsing project during those peroids. In addition, the number of failed outcome is also the higest in this period which may due to the total number of outcomes. The number of failed outcome is the highest in December. Possible reason is that people have lower budget because most money is spent on holidays including gifts, vacation, and dinners. As a result, its not recommeded to launch a campaign in December.

<br />What can you conclude about the Outcomes based on Goals?
<br />The graph shows a adverse relationship between dollar goals and success rate. Louise is most likely to reach her goal if her goal amount is less than $1000, where the percent of success rate is the high and percent of failed rate is the low. On the other hand, she is least likely to reach her goal when her goal amount is between $45,000 to $49,999. As goal reach to $45,000 to $49,000 the percent of success is 0 and the percent of failed rate is 100. 

<br />What are some limitations of this dataset?
<br />We are not sure if we are using the right representative sample size since we don't know the population size.  

<br />What are some other possible tables and/or graphs that we could create?
<br />Other possible tables to look are the successful, failure, canceled rate by different country, currency and staff pick.  
