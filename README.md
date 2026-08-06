# COVID-19 Exploratory Data Analysis (EDA) in Python

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a COVID-19 dataset using Python in Google Colab. The objective is to analyze the dataset through statistical summaries, data preprocessing, data transformation, and visualizations to gain meaningful insights into COVID-19 trends.

## Dataset

**Dataset Source:**

https://raw.githubusercontent.com/salemprakash/EDA/main/Data/covid-data.csv

The dataset contains COVID-19 information for different countries, including:

- Country
- Continent
- Date
- Total Cases
- New Cases
- Total Deaths
- Population
- Other COVID-19 related statistics

## Project Objectives

- Load the COVID-19 dataset
- Perform basic statistical analysis
- Identify and handle missing values
- Clean the dataset by removing duplicates and invalid data
- Transform data for better analysis
- Perform univariate analysis using visualizations
- Perform bivariate analysis using visualizations
- Perform multivariate analysis using visualizations

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Analysis Performed

### Data Preprocessing

- Loaded the dataset from GitHub
- Explored dataset structure and summary statistics
- Handled missing values
- Removed duplicate records
- Converted date columns to appropriate format
- Created transformed features such as logarithmic values and mortality rate

### Univariate Analysis

- Histogram of Total Cases
- Boxplot of Total Deaths
- Bar Chart of Countries by Continent

### Bivariate Analysis

- Scatter Plot of Total Cases vs Total Deaths
- Boxplot of New Cases by Continent
- Bar Chart of Top 10 Countries by Total Cases

### Multivariate Analysis

- Correlation Heatmap
- Scatter Plot of Total Cases vs Total Deaths colored by Continent
- Pair Plot of selected numerical variables

## Conclusion

This project demonstrates the complete Exploratory Data Analysis (EDA) workflow using Python. It includes data loading, preprocessing, statistical analysis, data cleaning, transformation, and multiple visualization techniques to understand relationships and patterns within the COVID-19 dataset.
