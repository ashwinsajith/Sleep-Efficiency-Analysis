# Sleep Efficiency Analysis

## Overview

This project explores the factors influencing sleep efficiency using a real-world dataset,
with a particular focus on how lifestyle habits and gender interact to affect sleep quality.
The analysis applies data cleaning, exploratory data analysis (EDA), 
and visualisation techniques to uncover patterns and insights from observational data.
The project demonstrates core data analysis skills including data preprocessing, 
feature grouping, statistical summarisation, and insight-driven visualisation using Python.

## Research Question

*What factors affect sleep efficiency, and how does gender influence these 
relationships?*

The analysis investigates the impact of:
* Exercise frequency
* Caffeine consumption
* Alcohol intake
* REM sleep percentage
* Age (grouped into ranges)

## Dataset

* Source: Kaggle - Sleep Efficiency Dataset
* Observations: Individual sleep records with demographic and lifestyle features
* Key variables:
  * Sleep efficiency
  * REM, deep, and light sleep percentages 
  * Age, gender
  * Caffeine and alcohol consumption 
  * Exercise frequency
  * Number of awakenings

## Methodology 

1) Data Cleaning

* Identified and removed missing values using Pandas (isna, dropna)
* Ensured consistency across numerical and categorical features

2) Exploratory Data Analysis

* Descriptive statistics using describe()
* Multi-panel visualisations to compare trends across variables

3) Visualisation

* Line plots with confidence bands for behavioural factors
* Box plots to compare sleep efficiency distributions across age groups
* Scatter plots to assess variability and individual-level patterns

## Key Findings

* Exercise frequency is positively associated with sleep efficiency for both 
genders.
* Alcohol consumption shows a clear negative relationship with sleep efficiency.
* Caffeine consumption exhibits diminishing returns, with higher intake not 
  improving sleep quality.
* Gender differences:

    * Males show slightly higher median sleep efficiency in the 0–25 and 
  51–75 age groups. 
    * Females show higher median efficiency in the 26–50 age group. 
    * Older female groups exhibit greater variability, suggesting increased heterogeneity in sleep outcomes. 

## Notes

* The analysis is exploratory, and results indicate correlation rather than 
causation.
* Overleaf, the online LateX editor was used to generate the report.