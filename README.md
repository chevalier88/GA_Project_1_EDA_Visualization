# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Testing, Statistical Summaries and Inference

## Problem Statement

We aim to provide The College Board with actionable recommendations to help them improve the success of the SAT Test. We define success as improved State participation rates in the SAT Test.

### Overview
The project seeks to identify trends or significant observations in SAT and ACT scores and participation rates across US between 2017-2018 through Exploratory Data Analysis and Data Visualizations. We will analyze these trends in order to identify any actionable insights from the data, and with support from external research, craft recommendations to The College Board to help them improve the success of the SAT Test.

### Contents:
- [2017-2018 Data Import & Cleaning](https://git.generalassemb.ly/chevalier88/DSI15-Clone/blob/master/project_1/code/1.2017_18_Import_Cleaning.ipynb)
- [Exploratory Data Analysis](https://git.generalassemb.ly/chevalier88/DSI15-Clone/blob/master/project_1/code/2.EDA.ipynb)
- [Data Visualization](https://git.generalassemb.ly/chevalier88/DSI15-Clone/blob/master/project_1/code/3.Data%20Visualization.ipynb)
- [Statistics, Outside Research, Findings & Recommendations](https://git.generalassemb.ly/chevalier88/DSI15-Clone/blob/master/project_1/code/4.Statistics%20and%20Findings.ipynb)

## Data Dictionary
|Feature|Type|Description|
|---|---|---|
|**title**|object|Original title of subreddit post|
|**link_flair_text**|object|Category of subreddit post|
|**all_words_clean**|object|Combined title and text of subreddit post after pre-processing|
|**selftext**|object|Original text of subreddit post|
|**score**|integer|Score of subreddit post at time of scraping|
|**url**|object|URL of subreddit post|
|**num_comments**|float|Total number of comments of subreddit post at time of scraping|
|**2017_act_math**|float|ACT|ACT Math mean score(range 1-36) per State in 2017|
|**2017_act_reading**|float|ACT|ACT Reading mean score(range 1-36) per State in 2017|


## Findings and Recommendations
Although initial data exploration shows that the ACT dominates in participation rates, our main conclusion is that participation percentage rates aren't everything. We must look at the absolute number of test takers too, which paint a better picure. External research indicates that in 2018, overall SAT test-taker numbers had already overtaken the ACT.

Our first recommendation is to continue to go after States that have very high ACT participation rates by pitching mandatory State SAT testing. This will convert ACT-dominant States into using the SAT, thereby boosting participation rates exponentially. This was already successfully achieved in Colorado and Illinois. Still, we assessed practically that government tendering contracts have high barriers to entry.

Thus, our second recommendation is to market the test directly to students in states who are 'on the fence' with participating in either test. We elaborate on the definition and data surrounding these 'swing' states and why this can help participation rates, with the idea being that it is better to stick to one test - the SAT.

Nevertheless, before funds are allocated to any campaign, there must be contextual research into whichever target state. States like Alaska, for example, completely eschew mandatory testing altogether. With this multi-pronged approach, we would have a higher probability of furthering the ongoing success of the SAT.


## Resources
https://www.chicagotribune.com/news/ct-illinois-chooses-sat-met-20160211-story.html
https://collegereadiness.collegeboard.org/state-partnerships/colorado
https://chicago.chalkbeat.org/2018/7/27/21105418/illinois-has-embraced-the-sat-and-the-act-is-mad-about-it
https://www.washingtonpost.com/education/2018/10/23/sat-reclaims-title-most-widely-used-college-admission-test/.
https://blog.prepscholar.com/act-vs-sat
https://en.wikipedia.org/wiki/List_of_United_States_cities_by_population.
https://www.adn.com/alaska-news/education/2016/06/30/students-no-longer-need-national-tests-to-graduate/
https://en.wikipedia.org/wiki/Alaska
https://blog.prepscholar.com/average-sat-and-act-scores-by-stated-adjusted-for-participation-rate