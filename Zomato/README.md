# Zomato Exploratory Data Analysis (EDA)

## Project Overview

This project involves performing Exploratory Data Analysis (EDA) on the Zomato dataset to extract insights about the restaurant ecosystem, customer preferences, ratings, and cuisine distribution. Through data manipulation and visualization, various trends were identified, such as popular cuisines, online delivery availability, and the geographical distribution of Zomato's services.

## Key Objectives

- Analyze the dataset to understand Zomato’s market distribution
- Investigate customer ratings, online delivery availability, and cuisines
- Visualize the most popular cities and countries for Zomato
- Uncover insights related to customer behavior and restaurant performance

## Dataset

1. **Zomato dataset**: Contains information about restaurants, including location, cuisine, ratings, and online delivery options.
2. **Country Code dataset**: Maps country codes to country names.

## Analysis and Visualizations

### 1. **Data Preparation and Cleaning**
   - Handled missing values, particularly in the 'Cuisines' column.
   - Merged the Zomato dataset with the country codes dataset on the 'Country Code' column to include country names.

### 2. **Exploratory Data Analysis**
   - **Country Distribution**: Identified that Zomato predominantly operates in India.
   - **Rating Analysis**: Grouped ratings by score, color, and text descriptions to analyze customer behavior. Most customers did not rate, and those who did primarily gave ratings between 2.5 and 3.4.
   - **Online Delivery Availability**: Found that online delivery is only available in India and the UAE.
   - **City and Cuisine Insights**: Identified the top 5 cities with the highest number of orders and the top 10 most popular cuisines.

### 3. **Visualizations**
   - **Pie Charts**: 
     - Top countries using Zomato, highlighting India as the dominant market.
     - Top 5 cities by number of orders and top 10 cuisines by popularity.
   - **Bar Plot**: Ratings grouped by aggregate score, rating color, and rating text to show customer behavior.
   - **Heatmap**: Displayed missing data for quick assessment.

## Key Insights

- **Zomato's primary market is India**, followed by smaller operations in the UAE and other countries.
- **Most customers do not provide ratings**, but those who do tend to rate restaurants between 2.5 and 3.4.
- **Online delivery is limited to India and the UAE**.
- The **top 5 cities for Zomato orders** and the **top 10 cuisines** highlight the preferences of Zomato users.

## Tools Used

- **Python**: For data manipulation, analysis, and visualization
- **Pandas**: To clean and process the datasets
- **Seaborn & Matplotlib**: For creating insightful and aesthetic visualizations
- **Jupyter Notebook**: For running the analysis interactively

## Contact

# Feel free to reach out with any questions or feedback
