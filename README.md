# March Madness Classification
### By Jackson Gasperack and Sawan Pandita

This repository is exploring different staistics of Men's Basketball Division I teams from the years 2013 to 2025. The data files include information on 12 individual years of statistics and how the teams panned out for those years. There is a larger datatset that includes all teams from all years and those statistics as well, just a binded version of all the individual files.

## Overview

The main file, cbb.csv, contains information on every Division I basketball team from 2013-2025. A single team in any given year has the following variables:
**TEAM** - College name
**CONF** - Athletic conference the team plays in
**G** - Games played
**W** - Games won
**ADJOE/ADJDE** - Adjusted Offensive/Defensive Efficiency (Points for/against per 100 poss.)
**BARTHAG** - Power rating (Chance of beating the average DI team)
**EFG_O/EFG_D** - Effective FG rate for/against
**TOR** - Turnover rate
**TORD** - Steal rate
**ORB/DRB** - Offensive rebound rate for/against
**FTR/FTRD** - Free throw rate for/against
**2P_O/2P_D** - 2-point FG rate for/against
**3P_O/3P_D** - 3-point FG rate for/against
**ADJ_T** - Adjusted tempo (possessions per 40 minutes)
**WAB** - Wins above bubble (wins after postseason cutoff)
**POSTSEASON** - Round of elimination
**SEED** - Playoff seeding
**YEAR** - Year

We used subset selection to see which group of these variables would be the best feature set to predict a postseason of F4. 

## Works Cited

Dataset from Andrew Sundberg on Kaggle: https://www.kaggle.com/datasets/andrewsundberg/college-basketball-dataset

## Authors

Jackson Gasperack - Computational Data Science Major, Math Minor at Penn State University - Contact: jpg6383@psu.edu - LinkedIn: https://www.linkedin.com/in/jackson-gasperack/
