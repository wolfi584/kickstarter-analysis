# Kickstarting with Excel

## Overview of Project
This project organizes and presents information about different types of kickstarter campaigns for theatre plays.

### Purpose
The purpose of this analysis is to discover which pledge campaigns are most succcessful, so Louise can decide how to plan her kickstarter campaigns in the future. 

## Analysis and Challenges
The challenge is that there are many factors that contribute to the success/failure 
of a campaign including dates launched/ended, amount of backers, average donation, total donation, country of donation, and the type of play the pledge campaign is for. For
example - is the play a comedy or a drama? There are many important pieces of information that need to be organized and communicated, to properly conclude which types
of campaigns are most successful, and when those campaigns should occur.

### Analysis of Outcomes Based on Launch Date
![Analysis of Outcomes Based on Launch Date](https://github.com/wolfi584/kickstarter-analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png?raw=true)

### Analysis of Outcomes Based on Goals
![Analysis of Outcomes Based on Goals](https://github.com/wolfi584/kickstarter-analysis/blob/main/resources/Outcomes_vs_Goals.png?raw=true)'

### Challenges and Difficulties Encountered
When composing the pivot table for the 'Theatre Outcomes by Launch Date', it was challenging to figure out how to filter the information by month. 
Concerning the 'Oucomes Based on Goal' table, it took a few tries to properly compose the values in the countifs function.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  - There are more campaigns total launched in May than any other month.
  - There are not that many campaigns that have been canceled during the entire year.

- What can you conclude about the Outcomes based on Goals?
  - The most successful campaign goal ranges are between $35,000-$39,999 and $40,000-$44,999.
  - The most failed campaign goal range is $45,000-$49,999.

- What are some limitations of this dataset?
  - This dataset does not include country  of campaign.
  - It also does not show how many backers or average donation amount. 

- What are some other possible tables and/or graphs that we could create?
  - A pie chart could vizualize the 'outcomes based on goal' data more clearly.
  - I would also create tables involving different categories includeing 'time of pledge', and 'average donations' to see if there is a more specific day/time of year to run pledge campaigns. The average donation amount can guide the campaign to suggest a specific pledge amount. 
