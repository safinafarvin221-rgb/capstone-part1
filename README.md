# Capstone Project - Part 1: Data Acquisition, Cleaning and Exploratory Data Analysis

## Project Overview

This project focuses on cleaning and exploring the Telecom Customer Churn dataset. The goal is to prepare a high-quality dataset for machine learning by handling missing values, removing duplicates, correcting data types, identifying outliers, and performing exploratory data analysis (EDA).

## Dataset

* Dataset: Telecom Customer Churn Dataset
* Programming Language: Python
* Libraries Used:

  * pandas
  * numpy
  * matplotlib
  * seaborn

## Tasks Completed

### 1. Data Loading

* Loaded the dataset using pandas.
* Displayed the first five rows.
* Checked dataset shape and data types.

### 2. Missing Value Analysis

* Calculated missing value count and percentage for every column.
* Filled numeric columns having less than 20% missing values using the median.
* Median was selected because it is more robust to skewed data and outliers than the mean.

### 3. Duplicate Removal

* Identified duplicate rows.
* Removed duplicate records.
* Verified the cleaned dataset.

### 4. Data Type Conversion

* Converted incorrect numeric columns to the correct numeric data type.
* Converted repetitive string columns to the category data type.
* Compared memory usage before and after conversion.

### 5. Descriptive Statistics and Skewness

* Generated descriptive statistics for numeric columns.
* Calculated skewness for each numeric feature.
* Identified the most skewed column.
* Positive skew indicates a long right tail, while negative skew indicates a long left tail. Because skewed distributions are affected by extreme values, the median was chosen for imputation.

### 6. Outlier Detection

* Applied the IQR method to identify outliers.
* Outliers were documented and retained for future analysis instead of being removed.

## Visualizations

The following visualizations were created:

* Line Plot
* Bar Chart
* Histogram
* Scatter Plot
* Box Plot
* Correlation Heatmap

### Plot Interpretation

* The line plot shows the trend of a numeric feature.
* The bar chart compares average values across categories.
* The histogram illustrates the distribution of the most skewed feature.
* The scatter plot shows the relationship between two numeric variables.
* The box plot highlights the spread, median, and outliers across categories.
* The heatmap visualizes correlations between numeric features.

## Correlation Analysis

* Computed Pearson Correlation Matrix.
* Computed Spearman Correlation Matrix.
* Compared Pearson and Spearman correlations.
* Identified feature pairs with the largest differences.

## Grouped Aggregation

Performed grouped aggregation using:

* Mean
* Standard Deviation
* Count

The grouped statistics were analyzed to understand category-wise variation and potential predictive patterns.

## Output

The cleaned dataset was saved as:

`cleaned_data.csv`

## Repository Contents

* capstonep1.ipynb
* cleaned_data.csv
* telecom_churn.csv
* README.md

## Conclusion

The dataset was successfully cleaned, explored, and prepared for machine learning. Missing values were handled, duplicates removed, data types corrected, outliers identified, and exploratory data analysis was completed. The cleaned dataset is ready for use in the next stage of the capstone project.
