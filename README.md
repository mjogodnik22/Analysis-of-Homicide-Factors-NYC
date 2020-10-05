---
title: "Homicides in NYC: When are they domestic?"
subtitle: "An analysis of various factors associated with domestic homicide"
author: "R-Rated - Holly Ansel, Jiayi Liang, Matt Jogodnik, Kehan Zhang"
output: pdf_document
---

## Read Me

This repository features the analysis of homicide crime data in NYC. Overall,
it analyzes domestic homicides and evaluates which factors make a homicide more likely to be domestic/are associated with domestic homicides. The data is 
analyzed using visualizations, simulation based inference, hypothesis testing,
and logistic regression using AIC values. More information about the analysis
done and the conclusions can be found in project.Rmd.

Below is a codebook about the data used.

## Dimensions of the dataset 
	1,241 observations; 28 variables   
  
## Code book  
 Variables | Descriptions
 ------------- | -------------
 [1] "shooting_homicide_incident_id_anony" | the id number for the incident   
 [2] "date" | date of the incident   
 [3] "month" | month of the incident   
 [4] "precinct" | the precinct in which the incident happened   
 [5] "patrol_borough" | the patrol borough in which the incident happened   
 [6] "borough" | the borough in which the incident happened   
 [7] "victim_age" | age of the victim   
 [8] "victim_1" | whether the victim is under 1 years old   
 [9] "victim_sex" | sex of the victim (“M” for male, “F” for female)   
[10] "victim_race" | race of the victim   
[11] "victim_ethnic" | ethnic of the victim   
[12] "perp_status" | description of the perpetrator’s status   
[13] "perp_age" | age of the perpetrator   
[14] "perp_sex" | sex of the perpetrator   
[15] "perp_race" | race of the perpetrator   
[16] "perp_ethnic" | ethnic of the perpetrator   
[17] "relationship"|the relationship between the victim and perpetrator   
[18] "weapon"| weapon used by the perpetrator   
[19] "circumstance" | description of the circumstance of the incident   
[20] "other_circumstance" | other circumstance of the incident   
[21] "in_out" | whether the perpetrator was in or out of the state (“I” for in the state, “O” for out of the state)   
[22] "case_n" | number for the case   
[23] "record_n" | number of records for that incident   
[24] "victim_n" | number assigned to the victim for that year   
[25] "domestic" | whether it happened domestically (“YES” for domestic incident)   
[26] "year" | year of the incident   
[27] "day" | day of the incident in a month   
[28] "wday" | weekday of the incident (in short, ex. “Mon” for Monday)    
