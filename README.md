## An Analysis of Kickstarter Campaigns
---
# Overview of Project: 
* Louise is an up and coming playwriter who wants to start a new crowdfunding campagin to help fund her new project called "Fever". In this project I have organized data from organized and sorted data to make this project successful. Data such as successful, failed, & canceled projects to help louise kickstart her production including an array of different categories of Data. 
---
# Analysis and Challenges: 
* Throughout this project we utlized **Pivot Tables**, **Pivot Charts** and, **COUNTIFS** to better present our data. At times creating the perfect COUNTIF formula for the "Outcome Based on Goals" became a tricky task. Although after throurough dedication and trial and error, this tool became very very helpful to learn. 

*For EXAMPLE: For this chart created below, we utilized **COUNTIFS** forumulas to create this data. 

*For this Code used below we figured out how many successful plays goals in beteween the ranges of $1000 and $4999. 

*Example Code **COUNTIFS* =COUNTIFS(Kickstarter!$F:$F,"=successful",Kickstarter!$D:$D,">=1000",Kickstarter!$D:$D,"<=4999",Kickstarter!$R:$R,"=plays")

![Outcomes vs Goals](https://github.com/ABorden23/Kickstarter-Analysis-Data-Analytics-Project/blob/main/Resources/Outcomes_vs_Goals.png)
---
# Results: Answer the following questions in complete and coherent sentences.
* What are two conclusions you can draw about the Theater Outcomes by Launch Date? After reviewing the Theater Outcomes by Launch Date Data, the first conclusion made from the data is that the top 3 months of Successful as well as Failed Theater Launch dates are during the summer months of: May, June, and July.  The other conclusion made is that the most canceled Theatre launches were dated in January. 
* What can you conclude about the Outcomes based on Goals? Goals in the $1000-$4999 ranges were the most popular goal trends. Goals in the $45,000-$50,000 were the least favored goal trend. 
* What are some other possible tables and/or graphs that we could create? One other Pivot Table we could create from the Yearly Data provided and see the trends of Yearly outcomes of performance. 
