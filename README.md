# Airbnb Open Data Analysis for Seattle and Boston 

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Files](#files)
* [Summary of the results](#summary-of-the-results)

## General info
This repository contains code and data for analysis of Boston and Seattle Airbnb market. 
Data used in this project comes from [kaggle](kaggle.com) (links to the datasets in Files section).

Code provides cleaning, analysis, modeling and visualizations of data. 

The analysis is focused on 4 questions about Airbnb markets in Seattle and Boston:
1. In which city: Seattle or Boston, is renting an apartment with Airbnb more expensive?
2. Are there any dependencies in rental price in relation to the distance from city center?
3. What are the busiest seasons to visit Seattle and Boston?
4. What are the most expensive seasons to visit Seattle and Boston?

## Technologies
* pandas 2.1.4
* numpy 1.26.2
* seaborn 0.13.0 
* matplotlib 3.8.2

## Files
 * Airbnb_Data_Analysis.ipynb - jupyter notebook with all the code for cleaning, analysis, modeling and visualizations of data
 * Data_Boston - [Boston Airbnb Open Data package](https://www.kaggle.com/datasets/airbnb/boston)
   * calendar.csv - Boston calendar, including listing id and the price and availability for that day
   * listings.csv - Boston listings, including full descriptions and average review score
   * reviews.csv - Boston reviews, including unique id for each reviewer and detailed comments
 * Data_Seattle - [Seattle Airbnb Open Data package](https://www.kaggle.com/datasets/airbnb/seattle/data)
   * calendar.csv - Seattle calendar, including listing id and the price and availability for that day
   * listings.csv - Seattle listings, including full descriptions and average review score
   * reviews.csv - Seattle reviews, including unique id for each reviewer and detailed comments
 * README.md

## Summary of the results
The answer for first two questions:
In which city: Seattle or Boston, is renting an apartment with Airbnb more expensive?
Are there any dependencies in rental price in relation to the distance from city center?

Was provided by fallowing visualization: 
![image](https://github.com/endrjugolota/airbnb-open-data-analysis/assets/30663501/b42614e5-84d0-49f1-b71b-d49bce293e2e)

Above chart shows average price of listings per guest in respect to distance to city center.

For third question:

What are the busiest seasons to visit Seattle and Boston?

Fallowing visualizations were provided:

![image](https://github.com/endrjugolota/airbnb-open-data-analysis/assets/30663501/bbb4190e-f6dd-40fb-b67b-552b2d7da718)
![image](https://github.com/endrjugolota/airbnb-open-data-analysis/assets/30663501/c9bdf3fb-7479-44fd-8d5d-dbd534558d21)

Last question:

What are the most expensive seasons to visit Seattle and Boston?

Is answered by fallowing distributions:

![image](https://github.com/endrjugolota/airbnb-open-data-analysis/assets/30663501/608a3a10-370b-4a90-a7cd-21845314053d)

![image](https://github.com/endrjugolota/airbnb-open-data-analysis/assets/30663501/7d51b206-eca9-43da-98e0-50ea915be8ba)

