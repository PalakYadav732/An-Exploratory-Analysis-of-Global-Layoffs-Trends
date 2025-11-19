# An Exploratory Analysis of Global Layoffs Trends

### Project Overview

The project aims to provide analysis on the global layoffs dataset by fixing missing values, duplicates, and inconsistencies. Performed EDA to analyze top companies, yearly and monthly layoff trends, industry/stage patterns, and cumulative totals, using window functions for yearly company rankings. The data

### Data Source 

The project is based on the Layoffs Dataset from the Alex the Analyst's Data Analyst Bootcamp project. The dataset and original project concept belong to the creator, all cleaning, analysis, and SQL queries here are work of my own work.

### Tools

MYSQL server - for Data Cleaning and Data Analysis

### Data Cleaning

1- Creating staging tables and copying raw data for safe transformation.

2- Identifying and removing duplicate records using ROW_NUMBER() and partitioning.

3- Standardizing fields by trimming text, unifying industry names(eg- Crypto),
    correcting country names, and converting data strings into proper DATE format.
    
4- Handling null and blank values by replacing empty strings,filling missing industry
    values using self-joins, and removing records with insufficient information.
    
5- Finalizing the cleaned table by dropping helper columns and ensuring consistent,
    structured, and analysis-ready data.

### Exploratory Data Analysis

1- Checking maximum layoffs and identifying companies with 100% workforce reduction.

2- Aggregating total layoffs by company, stage, year, and month to spot trends.

3- Calculating time-based rolling totals to understand cumulative layoffs.

4- Ranking top companies with the highest layoffs each year using window functions.

5- Exploring industry and stage-level variations to identify sectors most impacted.

### Results

1- Successfully cleaned the layoffs dataset by removing duplicates, correcting inconsistent values, standardizing date forumats, and handling missing or blank fields.

2- Identified companies with the highest total layoffs, along with those that experienced 100% workforce reduction.

3- Revealed clear yearly trends, showing which years experienced the most layoffs.

4- Monthly layoff analysis and rolling cumulative totals highlighted periods of major spikes.

5- Stage -level analysis showed that post -IPO and Late -stage startups experienced the largest layoffs.

6- Company-by-year ranking helped identify the top 5 companies with the highest layoffs in each year, providing deeper insight into annual patterns.



