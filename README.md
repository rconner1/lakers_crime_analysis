# Lakers Crime Analysis HTML Report

This project analyzes the relationship between Los Angeles Lakers' game outcomes and Domestic Violence in LA. The main results are presented in an interactive HTML report created with R Markdown.

## Live Demo
[View the interactive HTML report](https://rconner1.github.io/lakers_crime_analysis/)



## Files
- `lakers_crime_analysis.html` — Main HTML report 
- `README.md` — Project description and usage instructions

## Methods & Data

Data Sources:
- Collected daily crime incident records from the Los Angeles Police Department’s open data portal (over 1,000,000 crime reports from 2020–present) and Lakers game results from Basketball-Reference for the 2021-22 NBA season.

Data Cleaning:
- Merged datasets by date, created variables such as game results, winning/losing streaks, weekend/weekday indicators, and calculated daily counts of domestic violence reports based on crime codes.

Analysis:
- Built and compared ten statistical models (Poisson, Negative Binomial, GAM, Random Forest, and others) to predict daily domestic violence count using Lakers game variables and temporal controls (month, weekday, etc.).

Evaluation:
- Used Root Mean Squared Error for prediction accuracy, and compared models on their ability to forecast high-violence days versus low-violence days.

Results:
- Calendar effects (weekdays and month) were far more important than Lakers game outcome for predicting daily domestic violence reports.



