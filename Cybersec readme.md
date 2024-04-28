# Data Analysis and Visualisation Script

## Overview
This script demonstrates various data analysis and visualisation techniques using popular Python libraries such as Pandas, Seaborn, and Matplotlib. The data is loaded from a CSV file hosted on Google Drive and involves cyber security-related information, including attack types, severity levels, and alerts.

## Libraries Used
- `pandas`: For data manipulation and analysis
- `numpy`: For numerical operations
- `matplotlib.pyplot`: For creating static, animated, and interactive visualisations
- `seaborn`: For statistical data visualisation
- `WordCloud`: To create word clouds for text-based data visualisations

## Data Source
The data is sourced from a CSV file hosted on Google Drive. The URL for this dataset is:
- [CSV file on Google Drive](https://drive.google.com/file/d/1W4_6_Et46AUFy9kQoCsFv480Yg2_FVqK/view?usp=sharing)

## Data Cleaning and Analysis
The following data cleaning and analysis operations are performed on the dataset:
- Check for duplicates and count the total number of duplicates
- Identify the data type of each column, whether it's categorical or numeric
- Check for missing values and fill them with mode
- Drop irrelevant columns and columns with more than 90% of their data missing

## Visualisations
The script includes the following visualisations to analyse the data:
- Word Cloud: To represent the most frequent terms in selected columns
- Attack Analysis: Pie chart to represent the distribution of attack types
- Point Plot: Severity levels of the attack in a line chart
- Heatmap: Relationship between Attack Type and Severity Level
- Line Chart: Temporal analysis to identify attack patterns over time
- Box Plot: Distribution of Anomaly Scores by Attack Type
- Count Plot: Distribution of Attack Type by Action Taken
- Scatter Plot: Analysis of Anomaly Scores over time
- Horizontal Bar Chart: Users according to Alert count
- Line Plot: Alerts/Warnings for each attack type over time
- Stacked Bar Plot: For traffic type and protocol, packet types, and actions taken
- Heatmap: Relationship between Alerts/Warnings and Severity Level

## Instructions
- Ensure you have all the necessary libraries installed using `pip install pandas numpy matplotlib seaborn wordcloud`
- Execute the script to perform the data analysis and visualisations
- Examine the outputs to understand the patterns and trends in the data


