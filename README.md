## An Analysis of Kickstarter Campaigns
---
# Overview of Project: 
* Louise is an up and coming playwriter who wants to start a new crowdfunding campagin to help fund her new project called "Fever". In this project I have organized data from organized and sorted data to make this project successful. Data such as successful, failed, & canceled projects to help louise kickstart her production including an array of different categories of Data. 
---
# Analysis and Challenges: 
* Throughout this project we utlized **Pivot Tables**, **Pivot Charts** and, **COUNTIFS** to better present our data. At times creating the perfect COUNTIF formula for the "Outcome Based on Goals" became a tricky task. Although after throurough dedication and trial and error, this tool became very very helpful to learn. 


*The chart below, utilized **COUNTIFS** forumulas to create this data, which translates to the successful outcomes based on goals for Plays in beteween the ranges of $1000 and $4999. 

![Outcomes vs Goals](https://github.com/ABorden23/Kickstarter-Analysis-Data-Analytics-Project/blob/main/Resources/Outcomes_vs_Goals.png)

*Example Code **COUNTIFS* =COUNTIFS(Kickstarter!$F:$F,"=successful",Kickstarter!$D:$D,">=1000",Kickstarter!$D:$D,"<=4999",Kickstarter!$R:$R,"=plays")


*This chart shows the results of successful, failed, and canceled theatre launches based on the month. 

Pivot Tables were used to create the Pivot Chart as seen below. 

![Theater Outcomes Based on Launch Date](https://github.com/ABorden23/Kickstarter-Analysis-Data-Analytics-Project/blob/main/Resources/Theater_Outcomes_vs_Launch.png)
---
# Results: 
* After reviewing the Theater Outcomes by Launch Date Data, the first conclusion made from the data is that the top 3 months of Successful as well as Failed Theater Launch dates are during the summer months of: May, June, and July.  The other conclusion made is that the most canceled Theatre launches were dated in January. 
* Goals in the $1000-$4999 ranges were the most popular goal trends. Goals in the $45,000-$50,000 were the least favored goal trend. 
* Another Pivot Table that could be created is to take the Yearly Data and compare the Yearly outcomes of performance metrics to see what could be improved for future campaigns. 
