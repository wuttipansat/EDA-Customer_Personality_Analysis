# Customer Behavior EDA and Visualization

## Overview

This project explores customer behavior using basic exploratory data analysis (EDA) and visualization techniques. The goal is to understand patterns in the data rather than build predictive models.

## Dataset

The dataset contains information such as age, income, and spending behavior. It was sourced from Kaggle and used for analysis purposes only.

## Questions explored

Some of the questions I looked into during this analysis:

* How are customers distributed by age?
* Is there any relationship between income and spending?
* Do different groups of customers behave differently?

## Data preparation

Before starting the analysis, the data was cleaned by:

* Removing missing values
* Checking for obvious outliers
* Making sure data types were consistent

The cleaned dataset is stored in the `data/processed` folder.

## Analysis approach

The analysis focuses on understanding the data step by step:

* Looking at distributions of key variables
* Comparing groups (such as gender or age segments)
* Checking correlations between numerical features

## Visualizations

Several types of plots are used to make the data easier to understand:

* Histograms for distributions
* Boxplots for comparisons
* Heatmaps for correlations
* Bar charts for grouped data

All generated figures are saved in the `outputs/figures` directory.

## Key observations

A few patterns stood out during the analysis:

* Most active customers fall within the 25–40 age range
* Higher income does not always mean higher spending
* There are small differences in spending behavior across groups

