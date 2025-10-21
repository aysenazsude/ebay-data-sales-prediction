# ebay_data

## Project Overview
The notebook performs the following steps:

# Data Loading: Loads ebay_mens_perfume.csv and ebay_womens_perfume.csv.

# Data Preparation:

Merges the two datasets, adding a 'gender' column.

Handles missing values (e.g., filling 'brand' with 'Unbranded', 'type' with 'Unknown', and imputing 'available'/'sold' with their means).

Cleans and standardizes data (e.g., dropping 'availableText', splitting 'lastUpdated' into date and time).

Removes duplicate entries.

# Exploratory Data Analysis (EDA):

Brand Analysis: Identifies and visualizes the top 10 selling brands for men, women, and overall.

Price Analysis: Analyzes price distributions using histograms and visualizes the relationship between total sales and average price using a bubble chart.

Sales vs. Stock: Uses a scatter plot to examine the relationship between 'available' stock and items 'sold', segmented by gender.

# Libraries Used
pandas

numpy

matplotlib.pyplot

seaborn
