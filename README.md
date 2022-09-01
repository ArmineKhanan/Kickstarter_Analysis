# Kickstarting with Excel

## Overview of Project
Louise wants to start a crowdfunding campaign for her play, 'Fever'. The estimated budget of this theatrical project is over $10,000. To help Louise to make informed decisions, we are going to explore Kickstarter data. The source contains information on different fundraising campaigns initiated from 2009 to 2017 for diverse projects, including ones falling into the same category as ours, 'theatre'. One can also find the blurb text, the set target, and the actual pledged amount for each campaign in the dataset.

### Purpose
Our goal is to derive meaningful information from Kickstarter data to help Louise plan her campaign and set it up for success. Particularly, we will give data-based recommendations on the following:
* What dates are the most favorable for the theatrical project to launch
* What is the most realistic target range for the successful outcome


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The line chart below showcases the count of projects with different outcomes for each month of different years. It aims to reveal the seasonality pattern of project success, and March seems to stand out among other months. It's also worth mentioning that summer is active in terms of several successful projects as well as opposed to the end of the year.
![This is an image](https://github.com/ArmineKhanan/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)
*'live' campaigns are excluded from the analysis

### Analysis of Outcomes Based on Goals
The following visual illustrates the success of campaigns factored by the set goal. The humbler the goal, the more successful the project. Yet, that should be noticed that the success chances in the "$10,000 to $14,999" range are almost the same as in the "$15,000 to "19,999" range.
![This is an image](https://github.com/ArmineKhanan/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
Due to the completeness and quality of materials/resources, I mainly completed tasks trouble-free. Though, I floundered twice: the first time, when I had to add a title to the charts, and, a second time, while working on the text of the markdown doc. For the first, I turned to the Internet. For the second one, I booked Tutorial Session, and Khanya May helped me to overcome the difficulties I encountered.



## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

First and foremost, the late spring and summer months are the most favorable for theatrical projects to be initiated. May is the most popular one. Consequently, the competition during that month.

Yet, if opting for December, one has almost the same chances to succeed as to fail. Over half of the campaigns launched that month went wrong: they either failed or got canceled.

- What can you conclude about the Outcomes based on Goals?

Louise`s estimation for the budget was roughly $10,000. Though, in case of os necessity, they can go for a higher target, up to $20,000.

- What are some limitations of this dataset?

The data set was representative, complete and trust-worthy. If talking about limitations, it would be nice to have more detailed geographical data, e.g. states for the US. Withal, an extra field for the genres of theatrical plays (tragedy, heroic drama, comedy, tragicomedy. etc.) might enable insights.

- What are some other possible tables and/or graphs that we could create?

Comparing success rates by month would eliminate the influence of absolute numbers on the success estimation. The chart below proves that May is not just the most popular in terms of launching campaigns, but also the most advantageous.
![This is an image](https://github.com/ArmineKhanan/kickstarter-analysis/blob/main/Success_Rate_by_Month.png)
Adding some context and looking at the project success patterns among other categories might hint at what blurb text would work best, who are going to be competitors, and many other aspects.
![This is an image](https://github.com/ArmineKhanan/kickstarter-analysis/blob/main/Project_Outcomes_by_Category.png)
The content analysis of names and blurbs of failed and successful campaigns may add value to the analysis as well. For E.g. there are at least 3 other projects in the database containing the word 'fever.' It would be insightful to look into the success of that projects ...
