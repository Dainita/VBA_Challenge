# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends

## Overview 

### Purpose
After a successful Fever Kickstarter Campaign, additional analysis was conducted to determine the impact of the kickstarter campaign launch date and goal. A comparison of successful, failed, and canceled campaigns based on the corresponding launch dates and goals were compiled to visualize any patterns or trends. The intention is to provide information that explains the success rate of kickstarter campaigns based on the launch date and goal to help playwrights better determine and plan for anticipated campaigns.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Using the Kickstarter Challenge Data, I created pivot table of the outcomes by month and filtered the data on the table on parent category and year. I also filtered the outcomes column to only include successful, failed, and canceled campaigns. The resulting pivot table was used to create a line chart to visualize the data. 

![Outcomes Based on Launch Date](https://github.com/Dainita/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
A blank spreadsheet was added to the Kickstarter Challenge worksheet to compile the data to create the chart for Outcomes Based on Goals. The goal ranges were entered in the first column. The Countsif function (eg. =COUNTIFS(Kickstarter!$D:$D,"<1000",Kickstarter!$F:$F,"Successful",Kickstarter!$R:$R,"plays") in cell B2) was used to calculate the number of successful, failed and canceled campaigns. The ranges and outcome were changed for the Countsif function as needed to calculate accurately. The perenctage successful, failed and canceled were calculated in columns F through H by dividing respective outcome by the total outcomes. The Goal, Percentage Successful, Percentage Failed and Percentage Canceled columns were selected and a line graph was inserted. The Percentage Canceled data was removed from the chart.

![Outcomes Based on Goals](https://github.com/Dainita/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
Because Outcomes Based on Launch Date is compiled with number of campaigns rather than percentage of campaigns, it is difficult to determine if the result is based on the success of the campaigns or the number of campaigns started within the month. As playwrights determine that May is an optimal month to launch a campaign, the number of campaigns launched in May will continue to increase. Impact of that may result in the failure of campaigns because of the number of campaigns lauched during the same period.

## Results
Anticipated kickstarter campaigns are more likely to be successful if launched during the summer months. Campaigns launched during December and January have the lowest number of successful campaigns. It also holds true that May and October have the highest number of failed campaigns. 

Kickstarter campaigns with goals less than $5K have the highest success rate, followed by campaigns in the $35K to $45K range. For a successful campaign, the optimal goal range is less than $1K. More research and analysis is needed to determine the optimal goal range for larger project campaigns.

Additional information regarding the target audience would be helpful in determining the cause of the success or failure rate of these kickstarter campaigns. Often, the group you are marketing may provide an explanation about the outcome of your project. Suppose the "Another Brick In The Wall - Feature Film" was marketed to a group of individuals that are avid Pink Floyd fans. Would that change the outcome of the campaign?

Because Outcomes Based on Launch Date is compiled with number of campaigns rather than percentage of campaigns, it is difficult to determine if the result is based on the success of the campaigns or the number of campaigns started within the month. As playwrights determine that May is an optimal month to launch a campaign, the number of campaigns launched in May will continue to increase. Impact of that may result in the failure of campaigns because of the number of campaigns lauched during the same period.

To provide a more thorough analysis, percentages could be added to the Outcomes Based on Launch Date table and chart to provide a more accurate visualization of this measure. Based on this data, December and March have the lowest number of successful campaigns and October and December have the highest number of failed campaigns. This demonstrates the importance of ensuring that correct measures are analyzed based on the available data. 

An analysis of the outcomes based on the length of the campaign would also be helpful in determining how much time is need to complete a successful campaign. A comparison of the start date, length of campaign, goal, and outcome in one chart would provide the most informative visualization of the data. This would provide a full and informative picture but creating a chart of that magnitude seems 
