# Kickstarter Campaigns Analysis for Louise

## Overview of Project
Louise’s play **Fever** came close to its fundraising goal in a short amount of time. Louise wants to know how different campaigns fared in relation to their launch dates and their funding goals. 

## Purpose
The purpose of this project is to visualize campaign outcomes based on their launch dates and their funding goals. We are going to use the Kickstarter [dataset](https://github.com/vkbt/kickstarter-analysis/blob/main/Kickstarter_Challenge.xlsx) and will produce a written report based on our analysis and the visualizations and share our results below.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
1. Source Data: [Kickstarter_Challenge.xlsx](https://github.com/vkbt/kickstarter-analysis/blob/main/Kickstarter_Challenge.xlsx)
2. Launch Period: from 2009 to 2017
3. Category: theater
4. Group by: monthly

#### Conclusion:
Out of 1,369 examined campaigns launched between 2009 and 2017, we have observed that 839 campaignes succeeded, 493 failed and 37 were canceled. Given the low number of canceled campaigned overall we can concluded that canceled campaigns are irrelevant to our analysis. The most campaigns were launched in May, June and July, these three months also saw the most successful campaigns as well the most failed campaigns proving that there is a direct correlation between high number of launched campaigns and high success rate as well as increased failure rate. We also observed that despite low number of campaigns launched in October, the number of failed campaigns remained unusually high, therefore we would like to advise to exercise caution if launching campaign in October.

<img src="https://github.com/vkbt/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png" width="80%" height="80%">

### Analysis of Outcomes Based on Goals
1. Source Data: [Kickstarter_Challenge.xlsx](https://github.com/vkbt/kickstarter-analysis/blob/main/Kickstarter_Challenge.xlsx)
2. Launch Period: from 2009 to 2017
3. Subcategory: plays
4. Group by: Goal amount

#### Conclusion:
We have grouped campaigns for plays by goal amount and compared the number and percentage of successful, failed and canceled outcomes. There were no canceled campaigns for plays. Most successful campaigns had lower goals. Campaigns with the goal less than $1,000 had 76% success, campaigns with the goal from $1,000 to $4,999 had 73% success and campaigns with goal $5,000 to $9,999 had 55% success. We have also observed 2 outliers for campaigns with goals $35,000 to $39,999 and $40,000 to $44,999 respectively both with 67% successful outcome, however there were between 3-6 campaigns in these categories.

<img src="https://github.com/vkbt/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png" width="80%" height="80%">

### Challenges and Difficulties Encountered

## Results

- While examining campaign outcomes based on launch date we have observed that May, June and July are the most beneficial months to launch a campaign. We have also observed that October is when the most campaigns failed making it the worst possible month to launch a campaign.

- While examining campaign outcomes based on goals we have concluded that the most successful campaigns have lower goals, while there are successful campaign with higher goals, there are only a few and the sample amount is not enough to produce a conclusive opinion.

- As for dataset limitations, we could benefit from additional information such as geographic location of campaign backers as well as their age group and income levels.

- We can create various tables and graphs, for instance we can analyze the data by region and quickly sum up that the US and GB had the most number of campaigns in the world, 900 and 353 respectively. US had 38% fail rate and GB 25%.
	
					

![image](https://user-images.githubusercontent.com/114836744/194788785-b4c36d7b-245d-4ab1-92b7-93b05021e071.png)

