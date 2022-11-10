# Kickstarting with Excel

## Overview of Project
Use Excel to analyze "kickstarter' data for Louise's fundraising campaign.

### Purpose
The purpose of this project is to help Louise's play "Fever" reach its fundraising goal by analyzing the "Kickstarter" dataset. The dataset provides records of fundraising performances from other previous campaigns. By creating visualizations of campaign outcomes based on launch dates and funding goals, Louise will be better prepared to reach her goal.


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
A new worksheet("Theater Outcomes by Launch Date") was created to filter only one parent category of campaigns and organizing them by launch dates using a pivot table. By creating a pivot table, the data was contentedly summarized to focus only on "theater" campaigns and structuring columns showing the count of successful, failed, and canceled performances. Implementing a line chart improved the visualization of the data by highlighting the best performing months to launch a campaign. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/106359564/201217997-d19f661b-5199-4227-aecd-17891f3e13c4.png)

### Analysis of Outcomes Based on Goals
Another worksheet("Outcomes Based on Goals") was created to organize a table displaying the outcome count of successful, failed, and canceled campaigns based on different goal ranges. By using the "COUNTIFS" function, the data organized in the correct rows of goal amount and columns of outcome while also filtering campaigns with "plays" as a subcategory. The new table summarized the goal counts of each successful, failed, and canceled campaigns. Creating a line chart helped visualize the most successful range of goal amounts.

![Outcome_vs_Goals](https://user-images.githubusercontent.com/106359564/201218050-39f17f8e-2e34-4fc6-8237-3df9fe623356.png)

### Challenges and Difficulties Encountered
The biggest challenge came from the Outcomes based on Goal Analysis. Creating the table using "COUNTIFS" function was difficult because the statement was long using 3 to 4 different criteria’s and filling 12 rows and 3 columns. At first I didn't use the hint in the module to structure the function and I attempted to use only "COUNTIF" with multiple parenthesis to add more criteria. After a couple of failures, I realized I was using the incorrect function for the challenge by not including the "S" for "COUNTIFS". It was also time consuming to keep up with multiple ranges and criteria but I noticed a pattern to copy and paste each cell formula to only replace specific keywords for the columns and number ranges for the rows.


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    1. The most successful campaigns are launched in May.
    2. Campaigns launched in December are more likely to fail than other months.

- What can you conclude about the Outcomes based on Goals?
    Campaigns with goals under $5000 are more likely to succeed than goals over $5,000 through $35,000.

- What are some limitations of this dataset?
    Overall the dataset contained a lot of valuable information. Maybe could use specific addresses than just the countries. It could also use more data on donators like highest or lowest donation amount.
- What are some other possible tables and/or graphs that we could create?
    Implementing a chart using the "Average Donation" could help point out some useful trends. Adding the deadline column to the launch date analysis could have helped determine how long successful campaigns last. Also using a column chart for comparing goals and pledges could help visualize the campaign outcomes. 
