# An Analysis of Kickstarter Campaigns
UofT Data Analytics - Analysis on Kickstarter data  
The kickstarter data has revealed a number of interesting insights to pass on to Louise:

*Play Kickstarters in Great Britain were significantly more successful in reaching their goal than the other subcategories in the Theater Category as indicated below:

![TheaterCatOutcomesGB](https://github.com/blocrunx/kickstarter-analysis/tree/master/img/TheaterCatOutcomesGB.png)

*Here is a visualization of the outcomes of just the Play Kickstarters in Great Britain: 

![PlaysInGBStats](https://github.com/blocrunx/kickstarter-analysis/tree/master/img/PlaysInGBStats.png)

*The data indicate the success of a British kickstarter campaign may be correlated to the time of year in which the campaign is launched. The following graph shows campaigns launched in May and June to have a higher probability of success:

![OutcomesBasedOnLaunchDate](https://github.com/blocrunx/kickstarter-analysis/tree/master/img/OutcomesBasedOnLaunchDateA.png)

### Challenge

*The analysis showed a relationship between the sucess of a campaign and the funding goal. Failed campaigns were found to have a mean goal of 10 554 pounds, where successful campaigns had a mean goal of just 5049 pounds. That said upon further analysis the most succesful campaigns had goals less than 5000 dollars. The visualization of the relationship between the campaign goal and success:

![Mod1Goals](https://github.com/blocrunx/kickstarter-analysis/tree/master/img/Mod1Goals.png)

*The data indicate the success of a play Kickstarter campaign may be correlated to the time of year in which the campaign is launched. The following visualization shows campaigns launched in May and June to have a higher probability of success:

![Mod1Launch](https://github.com/blocrunx/kickstarter-analysis/tree/master/img/Mod1Launch.png)

*Analysis of the start and end dates of a campaign also showed a correlation between the length of a campaign and the success:

![Mod1Length](https://github.com/blocrunx/kickstarter-analysis/tree/master/img/Mod1Length.png)

*At first glance it appears that kickstarters with a 30 day campaign length are the most successful, however, when we look at the ratio of success, it becomes clear that the best length is between 6 and 40 days as shown here:

![Mod1LengthRatio](https://github.com/blocrunx/kickstarter-analysis/tree/master/img/Mod1LengthRatio.png)

*Its important to keep in mind the limitations of this dataset. First, the dataset only contains dates upto and including the first quarter of 2017, therefore any trends after that date will not be accounted for. Additionally, there appears to be some  incorrect data included as part of the set which needs to be taken into consideration when producing visualizations. For example, dates prior to April 28, 2009 should be excluded since this is the date Kickstarted was founded. 

*In addition to the extra Mod1Length and Mod1LengthRatio charts included above, one might also include a filtered table of funding outcomes based on Country to identify industry gaps in different markets. It would also be beneficial to have a box chart to visualize distributions of campaign goals and amounts pledged.

