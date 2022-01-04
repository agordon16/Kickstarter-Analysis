# Kickstarter-Analysis
Analyze Kickstarter Data to determine trends
## Overview
Louise launched a fundraising campaign for her play ***Fever*** and came very close to meeting her goal. Analyzing the Kickstarter data set to compare other fundraising campaigns based on launch dates and funding goals can assist to see how other campaign outcomes were affected in relation to these two points. This analysis can provide Louise with information that will guide her, hopefully, to a better outcome in her next fundraising effort.
### Analysis
  Based on data about Louise's play (goal, outcome, country, launch date, and category) the dataset was filtered out by country, launch date, and outcome to provide insight as to   when the best time to launch a campaign might be as well as trends on the best potentially attainable goal figures.
  
![Outcomes Based on Launch](https://github.com/agordon16/Kickstarter-Analysis/blob/ae87344c91574416c0398e8797f7dfd1c3366011/Kickstarter%20Images/Theater_Outcomes_vs_Launch.png)

![Outcomes VS Goals](https://github.com/agordon16/Kickstarter-Analysis/blob/ae87344c91574416c0398e8797f7dfd1c3366011/Kickstarter%20Images/Outcomes_vs_Goals.png)

### Challenges
One of the primary challenges encountered when analyzing the data, in relation to launch dates, was the format for deadline and launched_at data. The original data shows in Unix timestamps which makes it very challenging to interpret. By adding an additional column formatted to convert these timestamps to more traditional style dates, we were better able to see start and end times for the campaigns and determine their lengths.

![Unix](https://github.com/agordon16/Kickstarter-Analysis/blob/ae87344c91574416c0398e8797f7dfd1c3366011/Kickstarter%20Images/Unixformat.png)
![DateFormat](https://github.com/agordon16/Kickstarter-Analysis/blob/ae87344c91574416c0398e8797f7dfd1c3366011/Kickstarter%20Images/Date%20format.png)

## Results
- ### Conclusions
1)	Based on the "Outcomes Based on Goals" chart, projects with a goal of $5000 or less were more likely to be successful. Looking at the graph there was also a high success rate in the $35,000 to $40,000 range but given the total number of projects in that range was low, one could conclude that the sample size in that range is too small to retain confidence in the conclusion that Louise's project would follow suit. We would need to review other points of data and compare them to Louise's campaign data to see if they align with each other.
2)	Looking at the “Theater Outcomes by Launch Date” chart we can make several conclusion:
    - 	May and June are good months to launch potentially successful fundraising campaigns. Surprisingly May also had the most failed campaigns. 
    - 	May appears to be the most popular month to launch campaigns overall.  December seems to be the least popular and most volatile, with about a 50/50 chance of being successful.
 
![PercentTable](https://github.com/agordon16/Kickstarter-Analysis/blob/ae87344c91574416c0398e8797f7dfd1c3366011/Kickstarter%20Images/PercentTable.png)
- ### Limitations
Despite a sizeable and varied data set, there were certainly limitations, and the data could have been enhanced and/or expanded to include more granular information that may provide Louise with even better visuals. For example:
   - Current analysis focused on primarily US based campaigns. Since the dataset contains data from other countries it would be beneficial to see the outcomes in other countries in relation to each other.
   - In addition, a comparison of successful/failed campaigns in relation to alternate categories could also provide insight.
   - Date created and date ended data could be utilized to create additional information that shows how length of campaign affected its outcome.
