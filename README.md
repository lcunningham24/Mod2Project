# College Graduation Rates in the US

Flatiron Module 2 Project
Contributors: Lauren Cunningham 

Dataset: US Department of Education's College Scorecard, Most Recent Level-Institutional Data
https://collegescorecard.ed.gov/data/

## Overview 
The objective of this project was to clean, explore and model a dataset of our choosing. I chose to explore what influences College Graduation Rates in the US. Using data from the US Department of Education, I was able to make several hypotheses and ultimately, model my data in a multivariate linear regression model. 


## Data Cleaning & Visualization 
My dataset was quite large (6806 rows, 1986 columns) so first, I scaled it down to only include 4-year predominantly bachelor-degree granting institutions. I then went through the College Scorecard's provided data dictionary, as well as correlation matrices to determine which features I thought had the most influence on graduation rates. Once my dataframe was narrowed down (my_dataframe.csv) I had (2058 rows, 33 columns). 

To start my exploratory analysis, I generated a heatmap of the top highly correlated variables in my dataframe. 

![Image](heatmap.png)

I was interested in seeing how SAT/ACT scores influenced graduation rates so I made 2 scatterplots and a grouped bar chart to display their positive relationship with graduation rates. 

![Image](testscores_barchart.png)

## Hypothesis Testing 


