# Kickstarting with Excel

## Overview of Project

### The purpose of this analysis was to discover how variation in time, goal amounts, donations, category, and other variables may effect the success of a Kickstarter project. Specifically, we would like to help Louise understand how our crowdfunding data demonstrates how various factors can help set her project up for success.

## Analysis and Challenges

### **Analysis of Outcomes Based on Launch Date**

### The data shows that there are almost always more successful projects than failed ones at any time of year in the theater category. However, as you can see in the image below, during December there are almost as many failed results as successful ones. This indicates that the holidays are not a good time to launch the campaign. May is the launch month where the most campaigns are ultimately successful, so we would recommend a lauch around the springtime.

![Theater Outcomes Based on Launch Date](\Resources\Theater_Outcomes_vs_Launch.png)

### **Analysis of Outcomes Based on Goals**

### Looking at the outcome data based on the campaigns goals likewise reveals some interesting results. Any campaign with a goal over $45,000 seems to be very likely to fail. Projects with less than a $5,000 goal seem to be the most likely to succeed. The data also gives some indication that projects in the range of $35,000 to $45,000 are likely to succeed. However, there are so few data points for this category that this result should not be relied upon. Louise's stated goal of $10,000 falls into the data where about half of the projects succeed and the other half fail.

![Theater Outcomes Based on Goals](\Resources\Outcomes_vs_Goals.png)

### **Challenges and Difficulties Encountered**

### The basic Excel skills required for this analysis made the project quite straighforward. The most difficulty I encountered was while attemping to make the Outcomes Based on Goals data. Excel's COUNTIFS() function can be tedious when trying to specify ranges for a variable. Additionally, the autofill was not capable of filling out the data automatically, so each COUNTIFS() statement needs to be edited individually. Automating this would have saved a lot of time, but I just ended up entering the lines manually.

## Results

- First, launching during the holidays is inadvisable. These projects seem to be the least likely to succeed. Second, the highest percentage of successful projects is clustered around the springtime, especially May. If possible, I would advise a May launch date.

- Goals under $10,000 are the most successful. I would recommend that Louise attempt to bring down the budget of her play if possible. If not, she still seems to have about a 50% chance of success based solely on her goal amount.

- Our data is limited by what is available specifically on Kickstarter. We have no data on other online or in person funding campaign methods which may show different results.

- We have data on launch dates and the dates campaigns ended. It would be useful to know if there is relevant variation in the success of projects based on the length of the window between these two dates. A line graph showing the length of campaign on the x-axis and the percent successful on the y-axis could help Louise better gauge the likelihood of success for her project.