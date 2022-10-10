# Kickstarting with Excel
Performing analysis on Kickstarter data to uncover trends
## Overview of Project
Visualization of data charts to show campaign outcomes based on their launch dates and their funding goals
### Purpose
Using Excel data analysis tools detect trends visualizing campaign outcomes based on their launch dates and their funding goals and deliver conclusions about the data
Create two charts to visualize trends on successful theater kickstarter over time and outcome goal percentage grouped by funding goal

## Analysis and Challenges
Presentation of the analysis and some chellenges faced during the excersice
### Analysis of Outcomes Based on Launch Date
![Outcomes Based on Launch Date](https://github.com/ggalguera/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch_small.png)

### Analysis of Outcomes Based on Goals
![Outcomes Based on Goals](https://github.com/ggalguera/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
For the Outcomes Based on Launch Date no Challeges detected but I am not sure if grouping all years by month can only detect season patterns and not yearly patterns.
For the Outcomes Based on Goals the countifs formula was very repetitive so I replaced the max and min with a value on the cell, then I blocked the columns so I can copy the formula for failed and canceled, also the word "successful", "failed" and "canceled" could have been used as part of cell value in the formulas to reduce typing time. A pivot table grouped by Goal was faster but needed an extra column to group the less than 1000 as it was the only group no meeting a range of 5000.

## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
For the Parent Category theater the best month to launch is May and the worst is December. Based on chart values we can observe that May has the 111 successful launches theaters that represents 66.87% of the total launched that month, the second-best month is June with 100 successful launches that represents 65.36% of the total. The worst month is December with only 37 successful launches that represent 49.33% of total theaters launches that month.
- What can you conclude about the Outcomes based on Goals?
For the Subcategory plays the smaller goal we set we have more chances of being successful. Maybe an outlier analysis is required to remove some values that skew the data and show that a 66.7% of Kickstarter with a goal between $35,000 and $45,000 are more likely to be successful when the rest of the data shows this is not a trend.
- What are some limitations of this dataset?
There are some outliers on the data that need to be removed. For certain categories and subcategories there not enough samples.
- What are some other possible tables and/or graphs that we could create?
For Outcomes Based on Goals we can use Stacked Column as the total is always 100% and shows all three values on the same bar.
For the Theater Outcomes Based on Launch Date Clustered Column is a way to see the data to compare every single month results and Stacked Column can be used to show totals visually without including an extra Serie.


Louise’s play Fever came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals. Using the Kickstarter dataset that you’ve already combed through, you’ll visualize campaign outcomes based on their launch dates and their funding goals. You’ll then submit a written report based on your analysis and the visualizations you create.

