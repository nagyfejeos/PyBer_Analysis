# PyBer Analysis

## Overview of the analysis
The purpose of the new analysis to create visualizations of the ride-share data to aid 
decision-makers improve access to ride-sharing services for under served neighborhoods. 
Using pandas library and Matplotlib, a summary DataFrame was created by city type, then
a multiple-line graph that helps to visualize how the total weekly fares differ for each
city type.

## Results
From ![the summary DataFrame]( https://github.com/nagyfejeos/PyBer_Analysis/blob/main/pyber_summary_df.png )
we can see the in rural cities there were proportionally fewer rides than in suburban and urban
cities. Also,the number of drivers in rural cities is about 3% of the number of drivers in urban cities. 
On the other hand the average fare per driver in rural cities was over three times higher than 
the average fare per driver in urban cities. While, the average fare per ride did not show such a wide range 
of difference between rural, suburban, and urban cities.

From ![the Total Fare by City Type multiple-line chart] ( https://github.com/nagyfejeos/PyBer_Analysis/blob/main/PyBer_fare_summary.png )
it is evident that total fares differ by about $500 between the rural and suburban cities
with widening at the end of February and at the end of April. The gap in total fares between urban 
and suburban cities starts with about a $1,000 difference that widens to about $1,500 from
the end of February.

## Summary
#### Recommendations for addressing disparities among city types:
	- From the summary DataFrame and the chart, increasing the number of drivers in rural
	areas seems like a good target to focus on. However, in rural areas there might not be 
	a large enough market for more rides and drivers since maybe people tend to make fewer 
	and longer trips than in urban and suburban cities. 
	- Focus on more to decrease the gap between the suburban and urban cities by possibly
	increasing the number of drivers in suburban areas. 
	- The large  gap between urban and suburban cities indicates through March and April
	indicates that there is a seasonal component to the total fare differences that could 
	be addressed. 

	