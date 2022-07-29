# Crowdfunding Analysis for Louise

## Overview of Project

### Louise is an up and coming playwright who wants to start a Crowdfunding campaign to fund her own play, Fever. She has never done a fundraiser through Crowdfunding and is hesistant of where to start. This is where the data analysts' job comes in; to analyze data of past Crowdfunding campaigns to glean from the data which factors of a campaign are often successful and give Louise recommendations of what to consider in her future campaign.

### The purpose of this analysis was to look closely into the relationship of the outcomes (failed, successful, or canceled) based on the launch dates of the campaigns and then again based on the goals of the campaigns. This deep dive and analysis of the data will provide Louise with relevant information to help her move forward more productively in her own Crowdfunding campaigns based off which past parameters were more and less successful. This project used Excel functions and Excel graphing techniques to organize, comb through, and analyze the data statistically and create visualization of the data in the form of graphs.

## Analysis and Challenges

### Outcomes Based on Launch Dates

#### First to analyze this data for outcomes based on launch dates, the year of each campaign was extracted from the Date Created Conversion column using the YEAR() Excel function to create a new column of data. A pivot table was then created from the worksheet and designed to show the canceled, failed, and successful campaigns as well as the grand total in columns. Parent category and years were set as the filters. The pivot table was filtered to show each month and how many campaigns were in each category for that month. The data was filtered to only show theater campaigns as these were the most successful overall and therefore the focus for Louise. A line chart was created from this chart to show a clear visualization and is shown below:

#### 
![Theatre_Outcomes_vs_Launch.png](/Theatre_Outcomes_vs_Launch.png)

