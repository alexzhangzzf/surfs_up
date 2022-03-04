# Surf n' Shake Weather Analysis
## Overview
### This weather analysis shows the weather data in Oahu, Hawaii to provide beneficial information for the business plan for investing in the Surf n' Shake Shop that provides surfing equiment and ice cream for locals and tourists. In this analysis, we used SQLAlchemy to analyze weather data for the months of June and December in Oahu in order to determine if the surf and ice cream shop business is sustainable all year round.

## Results 
### We extracted temperature data for June and December from 2010 to 2017 from Oahu and performed statistical analysis to compare temperature between June and December. Summary of statistics is shown in figure 1. Box and whisker plot is shown in figure 2 for visual comparison. Based on the summary data, we found three major differences between June and December.<br/>

Figure 1. Statistical summary for June and December temperature.<br/>
![temp_summary](/Resources/temp_stats.png)<br/>

Figure 2. June and December temp comparison<br/>
![temp_boxplot](/Resources/Fig1.png)<br/>

- Temperature data for both months are roughly symmetric with little variance, where mean is very close to median. Overall mean temperatures for June and December are roughly close, 75°F for June and 71°F for December. Even thought the average temperature for June is slightly higher by 3 degrees.
- Overall temperatures from June and December are closer at higher temperatures but difference becames bigger when temperature drops from 3rd quartiles to 1st quartiles. The highest temperatures are roughly similar with 2 degrees difference; but for the lowest temperatre,it is 8 degrees. 
- There are more outliers for December temperature in lower quartile than June, indicating there are some relatively colder days in December than June.

## Summary 
- Based on the statistical analysis of the temprature from June and December over seven years, the overall temperature from both months is very close with little variations. Although in December the tempearture is cooler than June but the lowest temperature range (55°F-60°F) is still suitable. It suggests all year round the weather is warm and comfortable in Hawaii, ideal for surfing and ice cream business. 
- In addition to temperature, precipitation is a key factor that can affect surfing or ice cream. So precipitation data for June and December is also analyzed, shown below:

Figure 3. Statistical summary for June and December precipitation.<br/>
![prcp_summary](/Resources/prcp_stats.png)<br/>

Figure 4. June and December prcp comparison<br/>
![prcp_boxplot](/Resources/Fig2.png)<br/>

- Compared to June, December has higher precipitation in average and highest precipitation but overall daily precipitations from both months are as low as to less than 0.3 mm. Low precipitation suggests that rainfall is rare in these two months in Oahu so ideal for surfing. 

In conclusion, the weather analysis for temperature and precipitation in June and December indicates that Oahu has the ideal and weather and environment for surfing and ice cream store, and business will be sustainable all year round.
