# 📊 Layoffs Data Cleaning & Exploration Project

This SQL project focuses on cleaning and analyzing a dataset of layoffs from various companies during the COVID-19 era. It includes data cleaning steps like removing duplicates, handling nulls, fixing formats, and then performing exploratory analysis to uncover trends.

## 🧹 Steps Involved

### 🔧 Data Cleaning

- Removed duplicate entries  
- Standardized company and industry names  
- Converted string dates into proper `DATE` format  
- Handled blank and null values  
- Removed rows without meaningful layoff data  

### 📈 Exploratory Data Analysis

- Analyzed total layoffs by company, industry, country, and year  
- Identified companies with 100% layoffs (likely shutdowns)  
- Tracked monthly and cumulative layoffs  
- Found top 5 companies with most layoffs per year  

## 💡 Observations

- Layoffs peaked around the COVID-19 pandemic  
- USA experienced the highest number of layoffs  
- Industries like retail, consumer, and transportation were hit the hardest  
- Some companies shut down entirely  

## 🛠️ Tech Used

- MySQL Workbench  
- Basic SQL window functions (`ROW_NUMBER()`)  
- CTEs, aggregate functions, date formatting  
