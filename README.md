# Kickstarting with Excel

## Overview of Project
Using Kickstarter data on fundraising campaigns from 2009 through 2017, I sought to help a playwright understand how well past campaigns for theater projects had performed. 

### Purpose
The playwright Louise (who uses one name only) has recently undertaken her first Kickstarter campaign, to fund her new play, _Fever_. That campaign, which was planned using the results of analyses of a Kickstarter data set 2009-2017, performed well, coming close to its goal in a short amount of time. 

Louise requested further analysis of the same data set, to better understand:
    * the relationship between launch date and campaign outcome, for all theater-related campaigns (which include campaigns to support musicals, plays, and theater spaces)
    * the relationship between goal size and campaign outcome, for plays (as a subset of theater campaigns)

## Analysis and Challenges
All analyses were conducted using Microsoft Excel for Mac (version 16.64).

### Analysis of Outcomes Based on Launch Date
To better understand the effect of launch timing, I selected all theater-related campaign data. I then compared the month of campaign's launch and campaign outcome, as presented in the chart below.

![line chart comparing campaign outcome with month of campaign launch ](https://github.com/larabjork/kickstarter-challenge/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
To better understand the relationship between the campaign's goal and campaign outcome, I selected all play-related campaign data. To simplify the presentation, I grouped data about goal amounts in $5,000 increments, up to $50,000. I further broke up the lowest category into goals of less than $1,000 and goals of $1,000 to $4,999.

The analysis is summarized in the chart below.

![line chart comparing size of goal and campaign outcome](https://github.com/larabjork/kickstarter-challenge/blob/main/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
All data analysis efforts, including this one, require careful attention. Some of these analyses required Excel skills that were new to the analyst. Because these skills can be easily researched online, the challenges presented to the analyst should not be seen as challenges inherent in using the data set.

The quality of data can present difficulties or at least require extra steps prior to initiating analysis. However, this data set's quality facilitated analysis. For instance, the columns for "outcomes", "Parent Category", and "Subcategory" had standardized values and did not require any clean-up. Some columns in the data set were not examined and the quality of that data is unknown.

## Results

### Conclusions Regarding Outcomes Based on Launch Date
* May was the month with the highest number of launches that resulted in success, followed by June. Therefore, launching a campaign in May or June is recommended.
* December was the month with the lowest number of launches that resulted in success. Therefore, launching a campaign in December is not recommended.

### Conclusions Regarding Outcomes Based on Goals
* For all categories with goals of less than $20,000, at least 50% of the campaigns were successful. Therefore, setting a campaign goal of less than $20,000 is recommended.
* For all categories with goals of less than $5,000, at least 73% of the campaigns were successful. Therefore, setting a campaign goal of less than $5,000 may be desirable, assuming this amount would adequately cover project costs.

### Limitations of This Data Set
* Time period: The data set covers Kickstarters from 2009 through 2017. It is unknown whether patterns in fundraising have changed in the last five years. Given significant events like the COVID-19 pandemic, it is likely that a more recent set of data would generate more relevant results.

* Promotion: The data set does not include information on the efforts undertaken to publicize each Kickstarter, which would be helpful information to anyone planning a campaign. That is, we do not know whether promotional efforts (amount, quality, frequency, specific channels used, etc.) had an effect on campaign outcome.

* Rewards: The data set does not include information on what reward(s) were offered in each campaign. It would be helpful to understand whether theatrical productions (plays especially) had different outcomes based on rewards offered (e.g., free tickets to performances or dress rehearsals, behind-the-scenes events).

* Geography: Location information is presented only by country. With more granular information (i.e., for the United States, the city or at least the state), it would be possible to examine the effect of a more specific location's theater market.

### Additional Possible Analyses
Despite the above list of limitations, there are more questions that can be asked of this data set. For example, the following could be readily produced:

* a line chart with Outcomes for Plays Based on Launch Date, to isolate plays from musicals and theater spaces
* a line chart with Outcomes for Plays Based on Launch Year, to see whether outcomes have changed over time
* a table (if not further graphs) 


