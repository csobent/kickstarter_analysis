# kickstarter_analysis
Analyzing data to uncover trends in various Kickstarters

# Kickstarting with Excel

## Overview of Project
In this project, we are focusing on the data showing campaigns, specifically plays, that either succeed, fail, or cancel their funding goals in comparison to their launch dates, i.e., when the campaign began.

### Purpose
There are a few purposes of this project: one of them is to determine what the maximum amount, or cutoff, of money is before a campaign plummets, leading it to either fail or cancel its funding. Another purpose of this project is to determine the best time to launch a campaign; basically, determine which month is best. 

## Analysis and Challenges
At a glance, the data based on Launch Date shows that many theater campaigns succeeded in their goal if they launched in May. If any campaigns launched after May, you can see there is a steep decline in how many accomplished their goal. There is a slight increase in successful campaigns in October, but afterwards, the decline becomes more prominent dipping to a significant drop in December. 

When we dive into the data of Outcomes Based on Goals, we are taking more of a microscopic look into which types of campaigns succeed versus the ones that fail, or are canceled. According to the data, campaigns needing only less than $1000 achieved their goals more than any other demographic presented. After that, there is a steady decline in the amount of campaigns succeeding as higher goals are posted.

![Outcomes_vs_Goals_with_text](https://user-images.githubusercontent.com/98721891/155868995-9290ff8c-ede3-4905-b2b7-76723359f31b.png)

There were some challenges encountered while compiling the data. One of which involved creating the pivot table. There was some confusion as to which table the labels go into for the pvivot table. After some experimenting, I managed to create the pivot table and, in turn, created the line graph needed to provide an analysis. Another challenge was learning how to change the years and break them down into months through the pivot table. At first, it seemed a little tricky, but between using Google and trial and error, I also managed to figure out how to group them.

### Analysis of Outcomes Based on Launch Date
Let's dissect more of the data and analyze it further based on what was stated earlier. Starting with January, there is about a 55% rate of successful outcomes versus about 35% of failed outcomes and about 10% of canceled outcomes. There seems to be a slight trend of more successful campaigns following until March hits and it returns to rates similar to January. This is where we see an increase in April, which in turn builds into a very significant increase in successful campaigns. May appears to be the month in which to begin new campaigns.

 After that, the outcomes decline rather rapidly. The successful and failed outcomes follow a positive correlation; when the successful campaigns increase, failed campaigns increase and vice-versa with the decreases. This correlation changes when we hit May, as well, and the failed campaigns begin to level off. From this information, we can also see that in December, the successful and failed campaigns are almost equal to each other. Taking the canceled campaigns into account, it seems to not affect the outcomes significantly; they seem to be level over the months, except in October, where the campaigns either succeeded or failed.

 If we view the table only, we can also see that May has higher numbers than the rest of the other months having a total of 166 campaigns that started. June is the second best month to start campaign according to the graph and also to the table with a total of 153 campaigns that started. We can also say that it's best to start campaigns in the beginning of the year versus the end of the year. December had the least amount of campaigns started with an approximately 50% success rate.

### Analysis of Outcomes Based on Goals
If we take a cursory look at the data, we can see most projects which required $1000-4999 had a 73% success rate. Looking at campaigns ranging from the 1000 to 4999 category to the 25000 to 29999 category, they show a decrease in the amount of successful campaigns, whereas the amount of failed campaigns increase; this shows us a negative correlation between the two. Once we look at the campaigns in the 30000 to 34999 category, we can see that there is a slight increase in success, which eventually leads a to jump in success from 27% to 67% before plateuing. After the plateau, there is a sharp decrease in success which shows a 0% success rate for campaigns in the 45000 to 49999 category. However, if we look at the table, there is only one campaign being ran from this category giving it a 50% chance to either succeed or fail.

![Outcomes_vs_Goals.png](https://github.com/csobent/kickstarter_analysis/blob/main/Resources/Outcomes_vs_Goals.png?raw=true)

Also, as we take a look at the table, with the exception of the less than 1000 campaigns, there is a decline in how many campaigns are launched. If look at the total projects, you can clearly see starting with the 1000 to 4999 category, it has a total of 534 projects. From there, the total amount of projects drops significantly to 169 to 72 to 24 and so on. 

In comparison to the Outcomes Based on Launch Date, this set of data does not show any canceled campaigns; either they succeeded or failed. However, in both scenarios, it appears as if the canceled campaigns do not affect the data significantly.

### Challenges and Difficulties Encountered
Other challenges encountered with gathering the correct data was applying the COUNTIFS formula. There are many different elements to account for in the formula, which can make it easy for error. Also, if you don't include the right filters into the formula, it could cause the formula not to work. After watching the video on how to use the formula and making sure all of the appropriate filters were entered, the formula finally began to work. From this, I learned to take my time when inputting any information into any of these formulas in order to sort the right data.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
One of the conclusions we can draw from the Outcomes based on Launch Date is that the best month to begin a campaign would be May. Viewing the graph, there is a huge spike in successful campaigns and, while viewing the table, there is a total of 111 successful campaigns, which, at a glance, is the most compared to the other months. We can also conclude that December is the worst time to begin campaigns, since the success and failure rate are almost equal to each other. 

![Theater_Outcomes_vs_Launch.png](https://github.com/csobent/kickstarter_analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png?raw=true)

- What can you conclude about the Outcomes based on Goals?
Based on goals, one conclusion we can draw is that most campaigns not needing as much funding will usually succeed in reaching their goals. The exceptions are the 35000 to 34999 and 40000 to 44999 categories, but they don't have as many projects within these categories. Another conclusion we can draw is that projects needing more funding are most likely going to fail. As mentioned earlier, if we follow the data on the graph, there is that negative correlation between success and failure; as the successful campaigns dwindle, the failed campaigns climbs.

- What are some limitations of this dataset?
Some of the limitations include not being able to see the success of theater/play campaigns on a year-by-year basis. Expanding from only a cumulative outlook to a more sectionalized view, i.e. breaking it down monthly, could improve our analysis and we can probably analyze the reasons behind why campaigns suceed more in one month versus another month. I think another limitation is not accounting for outliers.
 
- What are some other possible tables and/or graphs that we could create?
Other tables we could include are sections for the mean and standard deviations to apply other concepts we learned in this module. This information could be created to define outliers, which don't seem to be accounted for in this outcome analysis. Other information we could include is the IQR and median, which is another method for determining outliers. Outliers could be important in this analysis to help determine to what degree the data is skewed.
