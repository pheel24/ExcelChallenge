# Kickstarting with Excel
Philip Kirwan

## Overview of Project
Louise needs a visualization of the various metrics involved in kickstarter campaigns for
theatrical productions.These metrics entail the launch dates of the campaigns, the goal 
of the campaign, and the country of origin for the campaign. 

### Purpose
In order to accomplish her artistic goals, Louise needs to optimize when she begins her
campaign and the monetary goal. By launching at the correct time for the correct amount, 
Louise can maximize her chances of success on her campaign. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
A trend seemed to emerge in the data with respect to launch date and campaign success. 
If any correlation between these factors existed it could be critical to the success of 
Louises campaign. To visualize the relationship between these factors we started with a table
comparing the possible outcomes for a campaign (success, failure, cancellation) against 
the time of the year in which they were initiated. We then visualized that table as a 
line graph (see "Theatre_Outcomes_vs_Launch" in resources), with the month on the x axis
and the outcome on the y axis. 

### Analysis of Outcomes Based on Goals
The other potentially important trend under analysis was essentially the rate of success
in terms of launch date. We want to know if the time of year in which a campaign is launched
has a significant impact upon the success or failure of the campaign. To begin, we organized
the dollar value of the goals into our ranges for analysis, starting at less than 1000 and 
increasing by 4999 at each level, up to 50000 and greater. Next, we organized the metrics 
for outcomes into the respective percentages (percent succesful, percent failed, percent 
cancelled). We then used the two somewhat truncated metrics for visual comparison. We 
plotted the outcome rate on the y axis and the dollar range for goals on the x axis (see
"OutcomesBasedonGoal" in resources). 

### Challenges and Difficulties Encountered
The need to organize the goal values in useful buckets required many steps. Analysis with
many steps and minor changes to codeblocks can easily yield bugs. We were able to avoid 
these by moving through those steps carefully, which will more often than not save time
on the analysis in the long run. 

## Results

Rates of success and failure tend to move together; for most of the year the trendlines
echo each other in their rise and fall. Successes and failures seem to peak mid way through 
the year, while both seem to taper off near the beginning and end of the year. 

But while they do seem to move together, successes have more extreme values. Successes have 
a very high peak around May, much higher than either of the others at that time. However, 
successes also fall quite low near the end of the year, to become nearly equal with failures
by December. 

Based on goals, the outcome a campaign seems to follow the intuitive trend. Lower goals
tend to have higher success rates. This holds until around 20000, when the success rate 
takes a marked dip falling as low as 20% for 25k-29k. However, the trend rises quite 
precipitously around the 30k-35k range, before plateauing around 70% and falling again
quite sharply. In general, it seems that lower goal campaigns have a higher success rate
except for the midling range and very high range. One should avoid the 20k-35k range and 
aim on either side of this mark without exceeding 45k.

This conclusion could be much stronger with a better cross section of the campaigns in the 
aforementioned 'midling' range. Why is a campaign for 15k so much more successful than one
25k? A similar question could be asked about 25k and 35k only reversed. There seeems to 
be something about aiming in the middle of the range that yields worse results for 
campaigners, but given that we are missing many metrics for these midling campaigns we 
cannot make any strong conclusions as to why this is, only that the correlation appears to
exist. 
"Missing metrics" in this case could be the countries of origin, perhaps the genre of play,
marketing optics etc. Barring the addition of factors, this analysis could benefit from
combining what is already under analysis. A visualization of the dates of campaigns broken
down by the goal value of the campaigns could shed more light on why mid tier goals seem to 
fail more. 
