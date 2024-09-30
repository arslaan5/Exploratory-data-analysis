# Layoffs Data Cleaning and Exploration using SQL

This project focuses on cleaning and exploring a dataset related to corporate layoffs. The primary objectives of this project were to clean the data using SQL and perform exploratory analysis to extract meaningful insights.

## Project Overview

The dataset contains information about layoffs across various companies, including details such as:
- Company Name
- Location
- Industry
- Total Employees Laid Off
- Percentage of Workforce Laid Off
- Date of Layoff
- Company Stage
- Country
- Funds Raised

### Key Steps in the Project:
1. **Data Cleaning:**
   - **Handling Duplicates:** Identified and removed duplicate rows using SQL partitioning and window functions.
   - **Standardization:** Standardized values such as industries, country names, and removed extra whitespace.
   - **Dealing with Missing Data:** Addressed missing and null values by filling in where possible and removing rows that could not be fixed.
   - **Data Formatting:** Corrected the format of date fields and changed column types to improve consistency.

2. **Exploratory Data Analysis (EDA):**
   - **Total Employees Laid Off:** Calculated the total number of employees laid off by company, industry, country, and year.
   - **Layoff Trends Over Time:** Identified trends in layoffs over months and years, including the rolling total of layoffs.
   - **Top Companies:** Listed the top companies by the number of layoffs in each year.
   - **Industry and Country Insights:** Explored layoffs by industry and country to understand which sectors and regions were most affected.

### Insights Gained:
- Layoffs are concentrated in specific industries and companies.
- Year-over-year and month-by-month trends indicate periods of increased layoffs.
- Certain companies repeatedly appear as top contributors to layoffs.

## Tools Used:
- **SQL**: For data cleaning, exploration, and analysis.
- **MySQL**: As the database management system for querying and handling the dataset.

---
