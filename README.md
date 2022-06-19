# 01 Excel Homework: Kickstart My Chart

## Background
Over $2 billion has been raised using the massively successful crowdfunding service, Kickstarter, but not every project has found success. Of the more than 300,000 projects launched on Kickstarter, only a third have made it through the funding process with a positive outcome.
Getting funded on Kickstarter requires meeting or exceeding the project's initial goal, so many organizations spend months looking through past projects in an attempt to discover some trick for finding success. 

Here, I have organized and analyzed a database of 4,000 past projects in order to uncover any hidden trends.

## Skills

excel pivot tables | conditional formatting | filters | stacked column pivot charts | pivot chart line graphs

## Analysis

In this exercise we have analysed a total of 4114 projects that have been launched in Kickstarter between the years 2009 and 2017 and have raised over 46 million dollars.

The majority of projects (53%) have been successful, followed by over 37% of failed projects, 8% canceled and 1% live.
First, the percent funded was calculated and conditional formatting was applied to visually see which projects were successful. A successful project is defined as having reached 100% of the targeted amount (percent funded in the green/blue zone). All failed projects had a percent funded below 100% (on average 9%, with 89% being the maximum). In some instances, the canceled or live projects reached 100% funded, but on average had a percent funded of 69% and 31% respectively, below 100%.

![image](https://user-images.githubusercontent.com/77761497/174500785-4ee9d927-7113-4ae3-afe3-44854284300b.png)

There wasn't a strong relationship between the average donation per backer and the success of a project. In fact, the average donation between failed or successful projects were not too different (1530 and 2185 respectively). This makes sense and probably speaks to the diversity of projects and goals that required different amounts of donation to reach the target.

<img width="362" alt="image" src="https://user-images.githubusercontent.com/77761497/174501339-288c147e-407d-432e-b6a2-a089bb67fd2a.png">

### Analysis by country and cantegories

The majority of the projects in Kickstarter come from the US (3038), followed by GB (604) and CA (146). The majority of successful, but also failed projects, are from the US, BG and CA.  This probably just refers to the fact that these countries had the highest project proposals.

In terms of categories, the majority of the projects belong to the theatre (1393), music (700), technology (600) and film&video (520). Theatre and music have the most success but music seems to have very little failures in proportion, so it seems like a good category.

This is readily visible in the following graph that shows a breakdown of the state of projects within the main countries and categories.

![image](https://user-images.githubusercontent.com/77761497/174501537-5aeff0f2-b846-4f5c-8e2e-6baf4403d740.png)

When analysing subcategories, 
•	within theatre: plays have the most successful and failed projects; 
•	within music: indie rock and rock have the most successful projects (remarkably rock hasn’t had failed projects); 
![image](https://user-images.githubusercontent.com/77761497/174502062-7156ed1d-dafd-4cd0-9a20-fa3b0e78b391.png)

•	within technology: hardware has the most success and wearables the most failures; 
•	and within film: documentaries have the most success, while animation and drama have the most failures.

### Analysis by year

Between the years 2009-2013 there was a steady increase of project proposals and the chances of getting it successful were high.
Between the years 2013-16 there was a sharp increase in project proposals and the number of failed projects also spiked up, indicating that it's harder to get projects funded in recent years.
![image](https://user-images.githubusercontent.com/77761497/174501934-b0390427-f82e-4f01-bc9b-8545103fed4d.png)

When looking at the most popular categories, it seems like music, followed by theatre, are the most popular sectors that have maintained a higher rate of success over failures throughout the years. 
![image](https://user-images.githubusercontent.com/77761497/174501956-3b6fa1dc-b6ee-4181-b159-a2b8c6d4ec35.png)

While technology and film have had a close number of failures to success in recent years.
![image](https://user-images.githubusercontent.com/77761497/174501985-254659d4-1614-4998-8f5c-5c07b11e5a95.png)

When looking at all the years and categories combined throughout Jan-Dec, it seems like there is an overall decline of successful projects as the year moves forward, so it might be recommended to launch the project early on.
![image](https://user-images.githubusercontent.com/77761497/174502009-91e9d2df-546a-46a0-9069-072a9493f916.png)

### Conclusions
•	Having a project within the music category, more specifically within indie rock or rock subcategory, has a high chance of being successful.
•	Do not have a project in wearables technology, since the failure rate is higher than successful projects.
•	It was easier to get a successful project when launching between 2009-13 but still music and theatre have maintained a higher success rate in recent years, this doesn’t happen within technology or film, so it’s not recommended to launch a project in the latter sectors.

## Limitations

The data sample represents only 1 and 2% of the amount of projects and total money raised within Kickstarted, thus its size is very small and might not be representative.
The data might also be skewed towards particular countries which used it more (US, GB, CA) during the period analysed (2009-2017), however in recent years it is possible that other countries have used the platform more and thus the data might not be representative for those.

## Other possible analysis

We could plot the outcomes per year according to countries to see whether in recent years there has been an increase of the “not so popular” countries.

We could also focus on a specific category of interest (despite this not being one of the main four), and plot the outcomes over time to see whether it has had recent high success rate.

## Bonus Analysis 

From this plot, it can be observed that there is an inverse correlation between goal amounts and success. 
Where the projects with the lowest target amounts ($1000 to $15000) reached the highest success and the least failures or cancelations. Whereas the highest targets (over $45000), reach the lowest success, and highest number of failures and cancellations.


