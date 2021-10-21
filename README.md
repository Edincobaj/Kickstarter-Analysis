# Kickstarting with Excel

## Overview of Project

### This analysis is to provide information to the client on the best time to start a kickstarter fund, as well as find the best goal amount to be successful.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

#### In the analysis of outcomes based on launch date, a pivot table was used to create a line graph to better portray information. This started with pulling the relevant information from the master workbook that included filtering for parent/years, outcomes in the legend, count of outcomes in the sum and dates in the axis. With the pivot table created it was a simple line graph creation along with adding the title.

### Analysis of Outcomes Based on Goals

#### In the analysis of outcomes based on goals, after preparing the table on a new worksheet I used the countif function to fill out each column to show how many kickstarters succeded, failed and were cancelled at different goal amounts. From there I got the percentages of each so that a line graph can be made from the information to show what would be the ideal number to make a goal.


### Challenges and Difficulties Encountered

#### I found my biggest challenge to be keeping track of the countif formula's so that there are no errors when populating following cells. For example =COUNTIFS(Kickstarter!D:D,">=15000",Kickstarter!R:R,"plays",Kickstarter!D:D,"<=19999",Kickstarter!F:F,"Successful"). This certainly makes it easy to make a mistake or miss a zero which is exactly what happened to me! Another challenge I had was figuring out which category goes into which section of the pivot table, luckily it is pretty easy to play around and get the information to show what you want it to.

## Results

### - What are two conclusions you can draw about the Outcomes based on Launch Date?

#### According to the information it seems that the best time to launch campaigns is in May, while the worst time to launch a campaign would be in December. This can be shown on the following graph: [Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/41974323/138204105-4e66efac-b4e0-4b8f-a3dd-bff0118ceb8b.png)


### - What can you conclude about the Outcomes based on Goals?

#### Theres seems to be a couple goal amounts that are more successful then others. According to the information given, any goals less then $1000 and in between $35,000 to $44,999 have had the most success. In terms of poor performing goals anything $45,000 and up has the lowest success percentages followed by $25,000 to $35,000. This can be seen on the following graph: [Outcomes_vs_Goals](https://user-images.githubusercontent.com/41974323/138204061-c0fd79fe-ee30-484c-a94f-1efee34600f4.png)


### - What are some limitations of this dataset?

#### When dealing with these types of analysis theres always the limitation of data, having more data points would allow for a better picture. Another limitation of this dataset might be having more specific parameters, there are a lot of different variables that possibly affect the outcome of different kickstarter campaigns. I think having additional filters to really narrow down plays that are related to our client would help in the decision making.

### - What are some other possible tables and/or graphs that we could create? 

#### I believe another graph involving the length of the campaigns would serve the client well in this situation. Being able to see how successful longer campaigns are as opposed to shorter one would be important data.
