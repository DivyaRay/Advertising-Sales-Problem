# Advertising-Sales-Problem

## Project Overview

- Objective : To predict sales for given budget spend on TV, Radio and Newspaper in dollars. 
- Regression Problem
- Data cleaning and Data preprocessing
- Exploratory Data Analysis
- Multiple Linear Regression model training and prediction
- Statistical Analysis done from coefficients, p value, R² and Adj. R² value and F-statistic

### Data fields

Features:

* TV: advertising dollars spent on TV for a single product in a given market (in thousands of dollars)
* Radio: advertising dollars spent on Radio
* Newspaper: advertising dollars spent on Newspaper

Target:

* Sales budget in thousands of dollars


## Model Building

### Multiple Linear Regression

Simple linear regression can easily be extended to include multiple features. This is called multiple linear regression:

y=β0+β1x1+…+βnxn

Each x represents a different feature, and each feature has its own coefficient. In this case:

y=β0+β1×TV+β2×Radio+β3×Newspaper

##### Advantages:
* widely used
* runs fast
* easy to use (not a lot of tuning required)
* highly interpretable
* basis for many other methods


To summarise, we have performed a multiple linear regression and have covered some basic introductory statistics as well. This is by no means a comprehensive analysis of the marketing data set but simply an example of how to perform and interpret a mulitple linear regression. It’s a good starting point, especially when attempting to understand the relevance of important statistical concepts like t-statistic, p-value and standard error. 
