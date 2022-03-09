# Kickstarting with Excel

## Overview of Project

### Purpose
Louise Would like to compare the outcome of other kickstarter campaigns compared to the outcome of her campaign.
The purpose of this analysis is to determine the outcomes of the theater kickstarter campaigns for each month of the year in order to provide insight into the time of year campaigns generally succeed 
along with the outcome succes/failure rate based on the kickstarter goal.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

![Theater_Outcomes_vs_Launch_Image](/resources/Theater_Outcomes_vs_Launch.png)

From the [kickstarter campaigns dataset](/Kickstarter_Challenge.xlsx) and using the provided graph labeled [Theater outcomes Based on Launch Date](/resources/Theater_Outcomes_vs_Launch.png) it was found 
that starting from the month of March the number of successful campaigns increased sharply until the Month of May where 
it was found the number of succesful campaigns went into a decline.

Looking at the same period the number of failed campaigns did not have a sharp increases and stayed consistent 
which would indicate the drop in successful campaigns would most likely not be due to campaigns 
not meeting the campain goals but just a general decrease in the number fo campaigns running during those periods.

This could also indicate a period during the year there is an increased willingness to pledge to kickstarter campaigns.
It may be best to consider that running a campaign during the increased amount of campaigns during the Months of March to May may result in higher competition
against other campaigns but running the campaign during other times of the year there may result in decresed interest to pledge to campaigns.

### Analysis of Outcomes Based on Goals

From the [Outcomes based on goals graph](/resources/Outcomes_vs_Goals.png) it is clear the higher the funding the goal the more likely it is for the campaign to fail.
The majority campaigns that are successful have a funding goal up to 20,000 but there is a funding goal range of betwwen 35,000 and 40,000
that the number of succeful campaigns increases again.

It is advised against running a campaign for anything above 45,000 as the graph indicates the majority of campaigns asking for amounts of funding above 40,000 fail.

![Outcomes_vs_Goals_Image](/resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

There were no major challenges found in the dataset but if the dataset indicated asome outliers from campaigns running with very high funding goals
it would have skewed the data and presented the graphs in a less accurate manner.
There were some outliers in the percentage funded data which may have resulted in diffilculy running on an analysis of the average funding goal 
compared to how much was pledged.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?<br/>
	From the analysis of the outcomes based on launch date there are two conlusions:
	- There is an increase in the number of successful campaigns between the month of March and May which would conclude the best time to run the campaing is between the months of March and May.
	- During the decline of successful campaigns after the month of May the number of failed campaigns does not sharply increase which would indicate the decline is not a result
	  of more campaings failing but there are less campaigns running during that period.

- What can you conclude about the Outcomes based on Goals?<br/>
	From the analysis of the outcomes based on goals it is clear it would be safest to keep the funding goal below 15,000 but the data indicates an increase in successful campaigns between 35,000 and 40,000.
	Depedning on the required goal of the camapin it would be safest to set the goal below 15,000.

- What are some limitations of this dataset?<br/>
	The dataset shows multiple currencies but does not indicate any exchagne rates at the time of the campaign making it difficult to analysis on an international level or to compare multiple countries.

- What are some other possible tables and/or graphs that we could create?<br/>
	Additoanl tables and graphs could be made to show the outcomes compared to the duration of the campaign to see if the duration of the campaign would result in a higher success/failure rate.

