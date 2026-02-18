This repository features a comprehensive, multi-phase analysis of over 1,700 expert chocolate bar ratings. The project moves from exploratory data analysis to Supervised and Unsupervised Machine Learning, seeking to decode the "perfect bar" by analyzing cocoa percentages, bean origins, and manufacturer locations.

# Project Objective
The goal was to identify the drivers of "Elite" chocolate ratings. By analyzing the intersection of cacao genetics, terroir (geography), and processing (cocoa percentage), this project identifies high-performing regions and uses Regression and Clustering to predict quality and segment the global market.

# 1. Exploratory Data and Geospatial Analysis
The initial phase focused on understanding the landscape of the "Flavors of Cacao" rating system 
## Key Insights & Visualizations
A regression analysis exploring whether higher cocoa solids lead to higher ratings or simply increased bitterness.
A Choropleth Map identifying "Gold Zones" where bean origin consistently results in "Premium" ratings.
Analyzing review dates to see if the craft chocolate movement has improved in quality over the last decade.

## Technical Workflow
Programming Language: Python 3Core 
Libraries: pandas, NumPy, matplotlib, seaborn, sklearn, pylab.
Supervised Learning (Regression): Implemented linear regression to test the correlation between cocoa percentages and expert scores, evaluating model performance via Mean Squared Error (MSE) and R-squared.
Unsupervised Learning (Clustering): The Elbow Technique - Used to determine the optimal number of clusters for grouping chocolate bars.
Data Wrangling: Extensive cleaning including handling inconsistent bean origins, converting percentage strings to floats, and addressing missing values in bean variety columns.3. 

## Repository Structure
Chocolate-Ratings-ML/
|-- 01_Sourcing_and_Wrangling/       # Initial data cleaning and consistency checks
|-- 02_Exploratory_Relationships/   # Correlation matrices and scatterplots
|-- 03_Geographical_Visualizations/ # Choropleth maps for origin analysis
|-- 04_Supervised_Learning/         # Linear regression models
|-- 05_Unsupervised_Learning/       # k-means clustering and elbow plots

## Data Citation
Main Dataset: Chocolate Bar Ratings compiled by Brady Brelinski, Manhattan Chocolate Society.
License: CC0: Public Domain.
Context: The data focuses on plain dark chocolate, evaluating Texture, Aftermelt, and Overall Opinion to provide a holistic sensory score.
