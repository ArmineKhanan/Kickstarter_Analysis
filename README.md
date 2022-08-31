# Kickstarting with Excel

## Overview of Project
Louise wants to start a crowdfunding campaign for her play, 'Fever'. The estimated budget of this theatrical project is over $10,000. In order to help Louise to make data informed decisions we are going to explore Kickstarter data. The sourse contains information on different fundraising compaigns initiated from 2009 to 2017 for divrse projects, including ones falling into the same category as ours, 'theatry'. One can also find the blurb text, the set target and the actual pledge for each compaign in the dataset.

### Purpose
We aim at deriving meaningful information from Kickstarter data to help Louise plan her campaign and set it up for success. Particularly we will give data informed recommendations to the on the following:
* What dates are the most favourable for the theatrical project to launch
* What is the most realistic target range for successful outcome


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The line chart below showcases the count of projects with different outcomes for each month of different years. It's aim is to reveal the seasonality pattern of project success, and March seems to stand out among other months. It's also worth mentioning that summer is active in terms of number of successful projects as well as aposed to the end of the year.
![This is an image](https://github.com/ArmineKhanan/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)
*'live' campaigns are excluded

### Analysis of Outcomes Based on Goals
The folowing visual illustrates the success of campaigns factored by the set goal. The humbler is the goal the more successful is the project. Yet, that should be noticed that success chances of "$10,000 to $14,999" range is almost the same as for "$15,000 to "19,999" range.
![This is an image](https://github.com/ArmineKhanan/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
Due to the exhaustive manner of materials I completed tasks mostly trouble free. Though I got stuck two times: first when I had to the charts, and second time while working on the content markdown doc. For the first I inquired the internet. For the second one I booked Tutorial Session, and Khanya May helped me to overcome the difficulties I encountered. 



## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

First of all, late spring and summer months are the most favourable for the theatrical projects to be initiated. May is the most popular one, thus the competion during that month is going to be huge as well.

Yet, if opting for December, one has almost the same chances to succeed as to fail. Over the half of the compaigns launched that month went wrong: either failed or got canceled. 

- What can you conclude about the Outcomes based on Goals?

Louise`s estimation for the budjet was roughly $10,000. Though, in case os nesessity they can go for a higher target, up to $20,000 as that is proved to be realistic as well.

- What are some limitations of this dataset?

It would be nice to have more detailed geographical data, e.g. states for the US. Also the description of the genre of plays (Tragedy. Heroic Drama. Comedy. Tragicomedy. etc.) could be helpful.

- What are some other possible tables and/or graphs that we could create?

Comparing success rates by month would eliminate the influence of absolute numbers on the success estimation. The chart below proves that May is not just very popular in terms of launching campaigns, but also very favourable.
![This is an image](https://github.com/ArmineKhanan/kickstarter-analysis/blob/main/Success_Rate_by_Month.png)
Adding some context and looking at project success in other categories might hint what blurb text would work best.
![This is an image](https://github.com/ArmineKhanan/kickstarter-analysis/blob/main/Project_Outcomes_by_Category.png)
The content analysis of name and blurbs of failed and successful campaigns may add value to the analysis as well. E.g. there are at least 3 other projects in the database containing the word 'fever.' It would be insightful to look into the success of that projects ...
