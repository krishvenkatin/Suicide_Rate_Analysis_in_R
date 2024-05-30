# Suicide Rates Analysis

## Introduction
Suicide is a major public health concern and a leading cause of death worldwide. This project analyzes the suicide rate dataset, identifies trends, and explores the relationship between suicide rates and various predictors to develop prevention strategies.

## Problem Statement
The dataset includes information on suicide rates, population, and various predictors such as age, gender, and economic indicators. The goal is to understand the factors contributing to suicide rates and identify significant predictors to help in prevention.

## Data Sources
1. [Kaggle - Suicide Rates Overview 1985 to 2016](https://www.kaggle.com/datasets/russellyates88/suicide-rates-overview-1985-to-2016)
2. [UNDP - Human Development Index (HDI)](http://hdr.undp.org/en/indicators/137506)
3. [World Bank - World Development Indicators: GDP (current US$)](http://databank.worldbank.org/data/source/world-development-indicators#)
4. [WHO - Suicide Prevention](http://www.who.int/mental_health/suicide-prevention/en/)

## Approach
1. **Data Cleaning**: Ensure data validity and reliability.
2. **Descriptive Statistics and Visualization**: Describe trends and compare suicide rates.
3. **Correlation Analysis**: Investigate relationships between suicide rates and other factors.

## Required Packages
```r
# Loading the required libraries
library(tidyverse)
library(ggplot2)
library(scales)
library(gridExtra)
library(dplyr)
library(countrycode)
library(lmtest)
library(caret)
