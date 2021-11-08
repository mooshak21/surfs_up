# Exploring Hawaii Temperature Data
## Overview

> In this project we conducting analysis on the weather in Oahu, Hawaii. Our goal is to open an ice cream shop and to gain the trust of our investor, we must provide him with the summary statistics on the temperatures in certain months to help him gain an understanding. We will mainly focus on the months of June and December. Using a SQLite DB linking it with Pandas, SQLalchemy, and Matplotlib we will be able to generate statistics and charts to analyze the data. We can use this information to see the trends on the data for these months to create a final report. 
---

## Results
### Deliverable 1 and 2: June/December Temperatures
![](https://github.com/mooshak21/surfs_up/blob/main/Resources/JuneTempStats.png)
![](https://github.com/mooshak21/surfs_up/blob/main/Resources/DecTempStats.png)
1. The average temperature for June and December respectively are ~75 and ~71 degrees fahreinheit. Based on this, both months seem like decent choices for an ice cream shop as people would probably be out surfing in these temperatures. 

2. Looking at the quartiles for June, 50% of the data is within the range of 73°F - 77°F. Looking at the same data for December, 50% of the data is within the range of 69°F - 74°F. Both months seem to have half of their data within a range of temperatures that would be perfect for the ice cream shop to run and have still have customers. 

3. Finally, we can look at the Max Temperature values for June and December being 85°F and 83°F respectively. These temperatures again show that it would be perfect for customers to come during those months because it doesn't get too hot that customers would be turned off to go surfing. 

### June/December Plots
![](https://github.com/mooshak21/surfs_up/blob/main/Resources/JuneTempPlotQuery.png)

![](https://github.com/mooshak21/surfs_up/blob/main/Resources/JuneTempPlot.png)

![](https://github.com/mooshak21/surfs_up/blob/main/Resources/DecTempPlotQuery.png)

![](https://github.com/mooshak21/surfs_up/blob/main/Resources/DecTempPlot.png)
1. For the June plot we can see more concentration of data points on the ends of chart meaning there are more points on the lower and higher ends of the data set.

2. For the December plot we can see less of a concentration of data points on the lower and higher ends of the chart. The peak of this chart is much higher than the surrounding area. 

3. The charts further clarify the summary statistics we went over showing the minimum, maximum, and averages.
---

## Summary
Based on our analysis, both June and December aren't much different in their temperature data in regards to attracting potential customers. The temperature data is definitely favorable to have consistent visitors to the shop whether surfing or just getting ice cream. With this data, our investor will most likely find it something he would want to invest in. 

Two additional queries that we can run are for the precipitation data for both months as that is also important to see if customers would show up. Surfers/visitors will not want to come that often if some months have high/consistent precipitation levels. Below we can see the summary stats for the precipitation for both months:

![](https://github.com/mooshak21/surfs_up/blob/main/Resources/JunePrecStats.png)
![](https://github.com/mooshak21/surfs_up/blob/main/Resources/DecPrecStats.png)
