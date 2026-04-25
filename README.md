# House-price-analysis

## Introduction

This project focuses on exploratory data analysis and outlier treatment using the Bangalore housing dataset. The main objective is to analyze the price_per_sqft column and identify abnormal values using different statistical methods.

Real estate datasets often contain extreme values due to data entry errors, luxury properties, or inconsistent records. These outliers can affect statistical analysis and machine learning models. In this project, multiple outlier detection techniques were applied and compared to determine the most suitable method for cleaning the data.

The project also includes data visualization, normality testing, transformation techniques, correlation analysis, and scatter plot relationships between important numerical variables.

## Dataset Information

The dataset contains housing property details from Bangalore city.

**Features Used**

* location
* size
* total_sqft
* bath
* price
* bhk
* price_per_sqft

## Project Objectives

* Perform basic exploratory data analysis
* Detect and remove duplicate records
* Identify outliers in price_per_sqft using multiple methods
* Compare outlier treatment methods using boxplots
* Check normality using histogram
* Apply transformation techniques
* Measure skewness and kurtosis before and after transformation
* Analyze correlations using heatmap
* Visualize relationships using scatter plots

## Outlier Detection Methods Used

* Mean and Standard Deviation Method
* Percentile Method
* IQR Method
* Z Score Method

## Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy

## Key Insights

* Duplicate rows were removed before analysis
* price_per_sqft contained strong outliers
* The data was positively skewed
* Log transformation improved normality
* IQR method gave balanced outlier removal
* Numerical relationships were examined using heatmap and scatter plots

## Conclusion

This project showed the importance of data cleaning and outlier treatment in housing datasets. Different methods were applied and compared to improve the price_per_sqft column.

Among all techniques, the IQR method was found to be the most suitable because it handled skewed data effectively while preserving useful observations. Overall, this project demonstrates practical skills in EDA, visualization, and preprocessing for real-world data analysis.

A detailed explanation video is provided below. Please refer to it to understand the project workflow and results
