# Individual Project README.md

## James Allen 

# Envrionmental Sustainability Measuring Annual CO2 Levels

# Executive Summary
### - Goal: 
   - Measure CO2 levels on an annual basis to predict new CO2 levels

### - Takeaways:

### - Recommendations:

## Deliverables

- Github Repo w/ Final Notebook and README
- Project summary and writeup for your resume or other professional portfolio pieces

# Carbon dioxide (CO2): 
- Fossil fuel use is the primary source of CO2. CO2 can also be emitted from direct human-induced impacts on forestry and other land use, such as through deforestation, land clearing for agriculture, and degradation of soils. Likewise, land can also remove CO2 from the atmosphere through reforestation, improvement of soils, and other activities.

Data Dictionary
Column Name	Renamed	Info
YYYYMM	date	Year, Month, Day
value	co2	Carbon dioxide emissions in million metric tons


## Initital Thoughts:
- I want to use the United States co2 data
- It looks like I can set a datetime index ?
- I will need to take care of null values and drop unneeded columns
- I have a population column that I can use in comparison / percantage
- I want to look at trends / impacts of co2 emmissions in the US
- I want to compare these trends / impacts to other values in my data to see if they are related / correlation
- I want to see if I can predict new trends /identifiers that contribute to increasing / decreasing co2 levels
- Impact of alternative fuel sources / wind / water / sun / electric ?


## What is my goal?
- Find annual co2 data
- Measure annual co2 emissions
- Increases / Decreases
- Relation or direct relation
- Use these drivers to predict future co2 emissions by country

# Data Science Pipeline

## Project Planning

Goal: leave this section with (at least the outline of) a plan for the project documented in your README.md file.

## Acquire

Goal: Get the US CO2 data from a local .csv and import into my notebook to use.

## Prepare

Goal: leave this section with a dataset that is split into train, validate, and test ready to be analyzed. Make sure data types are appropriate and missing values have been addressed, as have any data integrity issues.

## Data Exploration

Goal: The findings from your analysis should provide you with answers to the specific questions and summarize your takeaways and conclusions.

## Modeling

Goal: Forecasting using the following methods: Last observed value, Simple average, Moving average, Holt's Linear Trend, Previous cycle

## Key Findings and Takeaways
Not a large variation from baseline on all models, I went with polynomial regression to test data

Polynomial linear regression was close to baseline on train, but did a little better on validate / test

Selecting features helped performance on models

Would like to further adjust features to compare performance on models


# Conclusion


# Next steps
With more time I would like to:

a. Explore additional countries CO2 levels and compare them to the US CO2 levels

b. Look at different contributers of CO2 emissions and identifying relations

c. Take into account energy sources and how the relate to CO2 emissions

d. Create a dashboard on Tableau to express country CO2 emissions over time


## To Recreate my project
Download the U.S. CO2 Emission data from the sources listed below and save as a .csv on your local device.

Make a copy of my final notebook, run each cell, and adjust any parameters as desired.



## Sources:
- https://ourworldindata.org/co2-emissions
- https://www.eia.gov/totalenergy/data/browser/index.php?tbl=T11.01#/?f=M&start=200001