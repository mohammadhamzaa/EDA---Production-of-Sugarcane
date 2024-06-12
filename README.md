# EDA---Production-of-Sugarcane

This analysis project was assigned as part of the GeeksforGeeks Data Science course.This repository features Notebook dedicated to analyzing sugarcane production data using Python, leveraging popular data analysis libraries such as Pandas, Seaborn, and Matplotlib. The dataset utilized in this analysis is titled "List of Countries by Sugarcane Production.csv." 

## Contents

### Dataset
The dataset contains information about sugarcane production in various countries and includes the following columns --

1> Country: The name of the country.<br />
2> Continent: The continent where the country is located.<br />
3> Production(Tons): Total sugarcane production in tons.<br />
4> Production_per_person(Kg): Sugarcane production per person in kilograms.<br />
5> Acreage(Hectare): Total acreage of land used for sugarcane cultivation in hectares.<br />
6> Yield(Kg/Hectare): Yield of sugarcane in kilograms per hectare.

### Data Cleaning
The initial data cleaning steps include removing unwanted characters (e.g., commas, dots) from numeric columns and dropping irrelevant columns.

### Univariate Analysis
The univariate analysis focuses on examining individual columns independently. This analysis incorporates visualizations like bar plots and distribution plots to comprehend the data distribution and detect any outliers.

### Bivariate Analysis
The bivariate analysis delves into the relationships between pairs of variables, such as land area versus total production and yield per hectare versus total production. Scatter plots and bar plots are employed to effectively illustrate these relationships.

### Correlation Analysis
The correlation analysis examines the interconnections between numerical variables. A heatmap is utilized to visualize the correlation matrix, highlighting any significant correlations.

### Analysis by Continent
Additionally, the analysis is conducted at the continent level to discern how production and other variables vary across different continents. Bar plots and line plots are used to visualize these comparisons comprehensively.

### Conclusion
This analysis offers valuable insights into sugarcane production across various countries and continents. It explores the relationships between different production-related metrics, uncovering patterns and trends within the dataset
