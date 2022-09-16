# Kickstarting with Excel

## Overview of Project
Using Kickstarter data on fundraising campaigns from 2009 through 2017, I sought to help a playwright understand how well past campaigns for other theater projects had performed, according to her specific questions. Setting an ambitious but realistic Kickstarter goal is important, because donors are only charged for their pledges if the campaign reaches its goal. Failure to receive the total goal amount by the campaign deadline means that the organizer receives no Kickstarter donations.

### Purpose
The playwright Louise (who uses one name only) recently used the results of other analyses of Kickstarter data to plan her first Kickstarter campaign, to fund her new play, _Fever_. That campaign performed well, coming close to its goal in a short amount of time. 

Louise requested further analysis of the same data set, to better understand:
* the relationship between launch date and campaign outcome, for all theater-related campaigns (which include campaigns to support musicals, plays, and theater spaces)
* the relationship between goal size and campaign outcome, for plays (as a subset of theater campaigns)

## Analysis and Challenges
All analyses were conducted using Microsoft Excel for Mac (version 16.64). The data set, which covers Kickstarters launched from 2009 through 2017, is available here: [Kickstarter_Challenge_final](https://github.com/larabjork/kickstarter-challenge/blob/main/Kickstarter_Challenge_final.xlsx)

### Analysis of Outcomes Based on Launch Date
To better understand the effect of launch timing, I selected all theater-related campaign data. I then compared campaign outcome (whether successful, failed, or canceled) to the month of campaign's launch, as summarized in the chart below.

![line chart comparing campaign outcome with month of campaign launch ](https://github.com/larabjork/kickstarter-challenge/blob/main/Resources/Outcomes_vs_Goals.png)

### Analysis of Outcomes Based on Goals
To better understand the relationship between the campaign outcome and the campaign's goal, I selected all play-related campaign data. To simplify the presentation, I grouped data about goal amounts in $5,000 intervals, up to $50,000. I further broke up the lowest category into two intervals: goals of less than $1,000 and goals of $1,000 to $4,999.

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
* For all categories with goals of less than $5,000, at least 73% of the campaigns were successful. Therefore, setting a campaign goal of less than $5,000 may be desirable, assuming this amount would adequately cover project costs or that other funding sources could be obtained.

### Limitations of This Data Set
* Time period: The data set covers Kickstarters from 2009 through 2017. It is unknown whether patterns in fundraising have changed in the last five years, but it seems likely. Given significant events like the COVID-19 pandemic, it is likely that a more recent set of data would generate more relevant results.

* Promotion: The data set does not include information on the efforts undertaken to publicize each Kickstarter, which would be helpful information to anyone planning a campaign. That is, we do not know whether promotional efforts (amount, quality, frequency, specific channels used, etc.) had an effect on campaign outcome. This data is unlikely to be available from Kickstarter and could require significant effort to obtain, however.

* Rewards: The data set does not include information on what reward(s) were offered in each campaign, which is a standard feature of Kickstarters. It would be helpful to understand whether theatrical productions (plays especially) had different outcomes based on rewards offered (e.g., free tickets to performances or dress rehearsals, behind-the-scenes events).

* Geography: Location information is presented only by country. With more granular information (i.e., for the United States, the city or at least the state), it would be possible to examine the effect of a more specific location's theater market.

* Average Donation Size Only: The data set includes the average pledge size and the number of backers, but not more detailed information about pledge patterns. For example, we don't know what the range of pledges was for each campaign; was there a single large pledge that tipped the balance in meeting the goal? Were pledges mostly within a narrow range? This information would be partiucalrly useful in conjunction with more information about rewards, to see if there are any patterns related to reward levels set by the campaign and pledge outcomes.

### Additional Possible Analyses
Despite the above list of limitations, there are more questions that can be asked of this data set. For example, the following could be readily produced:

* a line chart with Outcomes for Plays Based on Launch Date, to isolate plays from musicals and theater spaces
* a line chart with Outcomes for Plays Based on Launch Year, to see whether outcomes have changed over time
* a series of box-and-whisker plots with Goals versus Pledges for Plays in the United States, with a separate plot per year, to supplement the line chart mentioned above, but with better information on unusual outcomes (i.e., outliers) and overall variability within a single year and from year to year
* additional analyses based on the client's questions


