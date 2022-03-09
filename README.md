# Kickstarting with Excel

## Overview of Project

### Purpose
Louise Would like to compare the outcome of other Kickstarter campaigns compared to the outcome of her campaign.
The purpose of this analysis is to determine the outcomes of the theater Kickstarter campaigns for each month of the year in order to provide insight into the time of year campaigns generally succeed 
along with the outcome success/failure rate based on the Kickstarter goal.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

![Theater_Outcomes_vs_Launch_Image](/resources/Theater_Outcomes_vs_Launch.png)

From the [Kickstarter campaigns dataset](/Kickstarter_Challenge.xlsx) and using the provided graph [Theater outcomes Based on Launch Date](/resources/Theater_Outcomes_vs_Launch.png) it was found 
that starting from the month of March the number of successful campaigns increased sharply until the Month of May where 
it was found the number of successful campaigns went into a decline.

Looking at the same period the number of failed campaigns did not have a sharp increases and stayed consistent 
which would indicate the drop in successful campaigns would most likely not be due to campaigns 
not meeting the campaign goals but just a general decrease in the number of campaigns running during those periods.

This could also indicate a period during the year there is an increased willingness to pledge to Kickstarter campaigns.
It may be best to consider that running a campaign during the increased amount of campaigns during the months of March to May would result in higher competition
against other campaigns but running the campaign during other times of the year may result in decreased interest to pledge to campaigns.

### Analysis of Outcomes Based on Goals

From the [Outcomes based on goals graph](/resources/Outcomes_vs_Goals.png) it is clear the higher the funding the goal the more likely it is for the campaign to fail.
The majority of campaigns that are successful have a funding goal up to 20,000 but there is a funding goal range of between 35,000 and 40,000
that the number of successful campaigns increases again.

It is advised against running a campaign for anything above 40,000 as the graph indicates the majority of campaigns asking for amounts of funding above 40,000 fail.

![Outcomes_vs_Goals_Image](/resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

There were no major challenges found in the dataset but if the dataset indicated some outliers from campaigns running with very high funding goals
it would have skewed the data and presented the graphs in a less accurate manner.
There were some outliers in the percentage funded data which may have resulted in difficulty running an analysis of the average funding goal 
compared to how much was pledged.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?<br/>
	From the analysis of the outcomes based on launch date there are two conclusions:
	- There is an increase in the number of successful campaigns between the month of March and May which would conclude the best time to run the campaign is between the months of March and May.
	- During the decline of successful campaigns after the month of May the number of failed campaigns does not sharply increase which would indicate the decline is not a result
	  of more campaigns failing but there are less campaigns running during that period.

- What can you conclude about the Outcomes based on Goals?<br/>
	From the analysis of the outcomes based on goals it is clear it would be safest to keep the funding goal below 15,000 but the data indicates an increase in successful campaigns between 35,000 and 40,000.
	Depending on the required goal of the campaign it would be safest to set the goal below 15,000.

- What are some limitations of this dataset?<br/>
	The dataset shows multiple currencies but does not indicate any exchange rates at the time of the campaign making it difficult to analyze on an international level or to compare multiple countries.

- What are some other possible tables and/or graphs that we could create?<br/>
	Additional tables and graphs could be made to show the outcomes compared to the duration of the campaign to see if the duration of the campaign would result in a higher success/failure rate.

