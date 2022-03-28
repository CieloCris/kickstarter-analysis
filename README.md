# Analysis of Kickstarters Campaigns

## Overview

##### Louise, our client, provided us with a dataset about Kickstarters projects between 2009 to 2017. She wants to launch a successful theater play and needs to know when is the best month to be the launch date of her project. Also, Louise mentioned to us that she has a fundraising goal of around 12,000 USD dollars for her play "Fever".
##### Louise wants to know how campaigns perform concerning their funding goals and the launch date.

##### We examined a dataset about Kickstarters Projects. Initially, our dataset had a size of 4115 rows and 14 columns. The columns of the dataset were: _ID, Name, Blurb, Goal, Pledged, Outcomes, Country, Currency, Deadline, Launched_at, Staff_pick, Backers_count, Spotlight, Category, and Subcategory._

##### In the dataset, we seek for theater projects to find relationships between different variables, especially those related to fundraising goals, launch date, and outcomes.

## **Purpose**
#### This project seeks to analyze Kickstarters data to discover trends and visualize campaign outcomes based on their launch dates and funding goals. 

## Analysis and Challenges

### **Analysis**
##### The analysis was performed with Excel and followed the next steps:
##### 1) The first step was to examine the dataset to understand the data. 
##### 2) After examining the dataset, the "Percentage Funded" and "Average Donations" columns were created.
##### 3) The third step was to separate the "Category and Subcategory" column into the "Parent Category" and the "Subcategory" columns. This was done to improve the findings through the use of filters and pivot tables.
##### 4) To work with the plays' launch date, we convert the dates that were in Unix TimeStamp format to a more understandable form. After that, the Years column was created.
##### 5) In the fifth step, we calculate some descriptive statistics, such as the mean and the standard deviation of the "Goal" and the "Pledged" columns, to discover trends of our data.
##### 6) The next step was to create a pivot table and a chart where the successful, failed and canceled works were identified according to the premiere month.
##### 7) Finally, a new table was made to classify the fund goals in monetary ranges to facilitate the findings.

##### Throughout all the analysis, filters, pivot tables, charts, and functions were used to find the information that would allow Louise to have better information for decision making.

### **Challenges**
##### -Understand what we need to find in the dataset because the client didn't give us much information about what she wanted.
##### -Use critical thinking to acknowledge what data is important for the project.
##### -Implement functions and create Pivot Tables in Excel, because I'm not an advanced user.
##### -Understand and apply some topics of descriptive statistics, such as the variance and the standard deviation.
##### -Discover trends and find insights.

## Results

##### In total, 4,113 Kickstarters projects were studied and, of these, 1,066 theater plays were identified through the Category and Subcategory columns. According to their outcome, 65% of the plays were Successful, while 33% Failed and 2% were in Live status.
##### The following chart presents the category of Kickstarters projects and their outcome.

![Alt text](/CategoryOutcomes.png "imagen0")

##### From the information above, we can identify that Theater Kickstarters projects are more than other categories and mostly successful, which is good news for Louise.

##### Finally, to better describe the results, we sought to answer the following questions:

### **What are two conclusions you can draw about the Outcomes-based on Launch Date?**

##### First, we present a chart that shows the outcomes of the theater plays based on launch date:

![Alt text](/Theater_Outcomes_vs_Launch.png "imagen1")

##### According to its Launch Date, we can see which theater plays are successful and which are not. May, with 111 plays, is the month with the most successful premieres, followed by June (100) and July (87), that is, summer months. The worst months to launch a play are November, December, and January, as well as March, September, October, and March.

##### This means that summer is the most successful season to launch a play while the winter months are the least viable options to premiere a play and this may be due to the Christmas holidays.

##### Also, we can see that in May there are a lot of theater projects that have failed (52) followed by July (50), June (49), and October (50). Despite this, we consider that May or June are good months to launch "Fever" because those months have the major percentage of success in plays. 

#### **Conclusions about the Theater Outcomes by Launch Dates:**
##### 1) May and June are the best months to premiere a play because those months have the highest possibility of success. The worst months to premiere a work are from November to January, in the winter season.
##### 2) Even though May, June, and July had many failed theater plays, these were the months with the highest number of projects released, so it is still convenient to launch the play in those months. To be sure about this suggestion, we need to analyze fundraising goals and other variables.

### **What can you conclude about the Outcomes-based on Goals?**

##### The next chart presents the fundings goals of the plays by monetary ranges and their outcomes:

![Alt text](/Outcomes_vs_Goals.png "imagen2")

##### The chart shows fundraising ranges from less than $1,000 to more than $50,000. Also, the data presents the number of successful, failed, and canceled projects. Live plays are not included in this graph.

##### According to the chart, the higher the fundraising goal the more the percentage of failed plays increases. The highest percentage of failed theater plays are in the range of $45,000 to $49,999, and more than $50,000. The plays with less percentage of failure have goals under $5,000.

##### On the other hand, a play has a higher success rate when the fundraising goal is lower. For example, the plays with the goal range of "$1,000 to $4,999", have a 73% of being successful. 

#### **Conclusions about the Outcomes-based on Goal:**
##### We can conclude that the higher the funding goal is raised, the fewer plays are produced and the probability of failure increases.

##### Louise has commented that she has a fundraising goal close to $12,000, which leaves her in the range of $10,000 to $14,999, where the percentage of success is 54, and the percentage of failure is 46.

##### The plays with lower fundraising goals are more and have more chances of being successful. Therefore, it can be concluded that works with goals of less than $15,000 have more than a 50 percent chance of being successful.

### **What are some other possible tables and/or graphs that we could create?**

##### To improve the performance of the analysis we used filters and pivot tables in the dataset to look for successful and failed plays with the funding that Louise have to launch her play "Fever" ($12,000).

![Alt text](/Successful_plays.png "imagen4")

##### As we can see in the chart, June and August are the months with more successful plays with goals between $10,000 and $15,000. On the other hand, the next chat shows the failed plays with the same fundraiser. 

![Alt text](/Failed_plays.png "imagen5")

##### We can conclude, based on the analysis of the launch date and the fundraising goal, that June is the best month to premiere "Fever".

#### **Our results support the conclusion that:**
##### June is the best month to launch a play with a fundraising goal between $10,000 to $14,999 because that month has fewer failed projects and more successful plays.

### **What are some limitations of this dataset?**

##### -The dataset can improve by adding some columns, such as the genre of the play and the mass media used to promote the campaigns.
##### -The dataset in which we were working needs more information about specifics metrics that are needed to analyze Kickstarters campaigns.
##### -In the dataset, the currency was not homogenized.
##### -Also, we don't have enough information about our client, her background, and her final purpose. We require more data from her.
##### -Even though Excel is a great tool be working with, there are other options that we can use to improve the analysis.
