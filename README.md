# Kickstarter Dataset Analysis.
## Overview of Project
### Purpose: 
I was given Kickstarter dataset that was provided by the client. They want to know how different theater campaigns fared in relation to their launch dates and their funding goals from the Kickstarter dataset in different countries. The client needs to see visualized campaign outcomes based on their launch dates and their funding goals from 2010 to 2017. 
## Analysis and Challenges
I went through the Kickstarter Dataset excel file that was provided to me by the client. I have identified certain columns with specific data that I will be using in my analysis. There is column D “Goal”, column F “Outcomes”, column Q “Parent category”, column R “Subcategory”, column S “Date Created Conversion”. 
<br>For the first part of project, I have created **a new column U “Year”** in order to extract the year from the “Date Created Conversion” column S.</br>
---Please see below the Kickstarter worksheet screen shot:---
![Kickstarter_Screen_Shot](Kickstarter_Screen_Shot.png);
I have used a pivot table method and graphing in Excel file to visualize campaign outcomes ("successful," "failed," and "canceled") based on launch date from 2010 to 2017. 
I have reviewed the data that was given me. I have created a new worksheet “Theater Outcomes by Launch Date”. Then, I filtered the pivot table based on "Parent Category" and "Years." Next, I placed the appropriate pivot table fields in the columns, rows, and values. Finally, I filtered the column labels to show only "successful," "failed," and "canceled."
Also, I filtered the "Parent Category" to show only the data for "theater” and sorted the campaign outcomes in descending order so "successful" is first.
As a result, I created a line chart from the pivot table to visualize the relationship between outcomes and launch month. 
Please see below the “Theater Outcomes by Launch Date” screen shot:
![Screen_Shot_Pivot_Table_and_Chart](Screen_Shot_Pivot_Table_and_Chart.png);
This chart shows grand total number of successful theater projects is 839;
grand total number of failed theater projects is 493;
grand total number of canceled theater projects is 37.
For the second part of the project, in order for me to analyze the outcomes based on goals, I have tried to visualize the percentage of successful, failed, and canceled plays based on the funding goal amount. I have used COUNTIFS() function in the excel worksheet to collect the outcome and goal data for the “plays” subcategory. 
In a new worksheet “Outcomes Based on Goals”, I have created the following columns to hold the data: goal, number successful, number failed, number canceled, total projects, percentage successful, percentage failed and percentage canceled.
In the “Goal” column, I created the following dollar-amount ranges so projects can be grouped based on their goal amount.
