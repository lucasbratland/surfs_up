# surfs_up
## Overview of Project
W. Avy likes your analysis, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

## Resources
- Data Suorce: hawaii.sqlite
- SoftwareL SQLite, Pythoin, Flask, Jupyter Notebook, VS Code

## Results
- Combined Summary Statistics for June and December Temperatures

![Chart](/Resources/stats-summary.PNG)

- June Temperatures Visual (Temperature and Frequency)

![Chart](/Resources/june_plot.PNG)

- December Temperatures Visual (Temperature and Frequency)

![Chart](/Resources/dec_plot.PNG)

### Key Differences in Weather in Oahu, Hawaii
- The average recorded temperature in June is 75 degrees, which is 4 degrees warmer than the December average of 71 degrees. 
- In June, the distribution of the temperatures is more of a normal distribution, with its bell curve shape. This is also backed up by the smaller standard deviation in June. 
- In December the minimum temperature recorded was 56 degrees whereas in June it was 64 degrees. This is an 8 degree difference which would explain why December has the higher standard deviation than June. 

### Summary of Findings
Overall the temperatures in the months of June and December are similiar. On average there is only 4 degrees of difference. Even though December has a wider range of temperatures, December's median temperature has a higher frequency than any other temperature by almost double. This would lead me to believe the lows are more outliers and shouldn't influence the decision to open the surf and ice cream shop. 

Before making a final decision I would want to look at a couple of other things. 
- I would want to look at the specific weather station data. This would allow us to see if one station has a greater temperature variance between June and December than another. This would help find out if one location is better than another. 
- I would also want to look at other information that would affect the surfing conditions, such as average wind speed, tide data, and cloud cover. These things could all affect teh beach goers experience and would have impact on sales. 