# Kickstarter-Anaylsis

## Overview of Project

### Purpose
The purpose of this analysis is to show how other kickstarter campaigns faired in relation to their launch dates and funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Using data fromt the Kickstarter Sheet as reference I created a pivot table filtered by Years and Parent Category. I set the columns for "Outcomes" and the value for "Count of Outcomes". The rows were set for "Date Created". Once this was created I filtered the "Parent Category" to "theater". This created a pivot table that filtered total successful theater kickstarters by month. Once the data was gathere in the pivotable - I used it to create line graph for Theater Outcomes Based on Launch Date.

![Pivot_Table_Based_On_Launch_Date.png](/resources/Pivot_Table_Based_On_Launch_Date.png)

![Theater_Outcomes_vs_Launch.png](/resources/Theater_Outcomes_vs_Launch.png)

Based on launch date we can conclude that the most succeessful "Theater" Kickstarters were launched in May, June, and July. May by far had the greatest number of successful theater kickstarters. May totaled 111 successful kickstarters, June 110, July 87. In contrast the lowest number of successful kickstarters were launched in December. October should aslo be noted as the month with the highest numbered of failed theater kickstaters. October had 50 failed kickstarters and only 65 successful.

### Analysis of Outcomes Based on Goals
Using data in from the Kickstarter Sheet as reference I created a table containing "Goal", "Number Successful", "Number Failed", and "Number Canceled". Using code I was able to filter the subcategory "plays" by either "successful", "failed", or canceled"
Code example: 
"=COUNTIFS('Kickstarter Sheet'!$D:$D,"<=1000",'Kickstarter Sheet'!$F:$F,"successful",'Kickstarter Sheet'!$R:$R,"plays")"

From here I calculated out the "total projects" and then calculated the "Percentage Successful", "The Percentage Failed", and "Percentage Canceled" columns. Once this were calculated I selected the following columns: "Goal", "Percentage Successful", "Percentage Failed", "Percentage Canceled" and used them to create the Outcomes_vs_Goals line graph.

![Grid_Outcomes_Based_On_Goals.png](/resources/Grid_Outcomes_Based_On_Goals.png)

![/Outcomes_vs_Goals.png](/resources/Outcomes_vs_Goals.png)


### Challenges and Difficulties Encountered
The only challenge I had was making sure I didn't have syntax errors causing miscalculations.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
The best time to launch a Theater Kickstarter would be in May. 
The least successful time to launch a kickstarter would be in October.

- What can you conclude about the Outcomes based on Goals?
Based on goals we have determined that the most successful kickstarters were launched with a goal of "less than 1000". Kickstarters in the "less than 1000" had a total project number of 251 with a 75% success rate. The second most successful goal range was "1000 to 4999" with 53 total proejcts and 73% success rate.

- What are some limitations of this dataset?
Some of the limitations of the data are the amount of kickstarters launched in goal ranges higher than 25,000. There have not been as many kickstarters launched in those ranges so failures account for more. 

- What are some other possible tables and/or graphs that we could create?
It would be best to filter the data out by specific country that way the data is more relevant to where Louise will be launching the kickstarter.
