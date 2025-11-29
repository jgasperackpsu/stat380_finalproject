# March Madness Classification
## By Jackson Gasperack and Sawan Pandita

<br>
This repository is exploring different statistics of Men's Basketball Division I teams from the years 2013 to 2025. The data files include information on 12 individual years of statistics and how the teams panned out for those years. There is a larger datatset that includes all teams from all years and those statistics as well, just a binded version of all the individual files.
<br>

## Overview

The main file, cbb.csv, contains information on every Division I basketball team from 2013-2025. A single team in any given year has the following variables:<br>
**TEAM** - College name<br>
**CONF** - Athletic conference the team plays in<br>
**G** - Games played<br>
**W** - Games won<br>
**ADJOE/ADJDE** - Adjusted Offensive/Defensive Efficiency (Points for/against per 100 poss.)<br>
**BARTHAG** - Power rating (Chance of beating the average DI team)<br>
**EFG_O/EFG_D** - Effective FG rate for/against<br>
**TOR** - Turnover rate<br>
**TORD** - Steal rate<br>
**ORB/DRB** - Offensive rebound rate for/against<br>
**FTR/FTRD** - Free throw rate for/against<br>
**2P_O/2P_D** - 2-point FG rate for/against<br>
**3P_O/3P_D** - 3-point FG rate for/against<br>
**ADJ_T** - Adjusted tempo (possessions per 40 minutes)<br>
**WAB** - Wins above bubble (wins after postseason cutoff)<br>
**POSTSEASON** - Round of elimination<br>
**SEED** - Playoff seeding<br>
**YEAR** - Year<br>
<br>
We used subset selection to see which group of these variables would be the best feature set to predict a postseason of F4. 

## Findings

![](xgb_25_preds.png)<br>
<br>
These are the teams that our model predicted would make the final four because their probability to make it is greater than our threshold. From the actual bracket, three of the top four teams are correctly predicted with the winner being the highest probability. Then, the actual fourth team was the 8th highest probability from our model and every other team predicted that didn't actually make the final four was beaten by another predicted team somewhere in the bracket. More about are findings is stored in our presentation and report PDF files.

## Works Cited

Dataset from Andrew Sundberg on Kaggle: https://www.kaggle.com/datasets/andrewsundberg/college-basketball-dataset

## Authors

Jackson Gasperack - Computational Data Science Major, Math Minor at Penn State University - Contact: jpg6383@psu.edu - LinkedIn: https://www.linkedin.com/in/jackson-gasperack/
