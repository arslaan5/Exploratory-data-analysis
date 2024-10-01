# Black Friday Sales Exploratory Data Analysis (EDA)

This project involves an Exploratory Data Analysis (EDA) on the Black Friday Sales dataset obtained from Kaggle. The dataset contains customer demographic information and their purchasing behavior during Black Friday sales. The goal is to analyze customer purchase patterns and prepare the data for machine learning models.

## Dataset

The dataset includes the following key features:
- **User_ID**: Unique customer identifier (dropped for analysis).
- **Gender**: Customer gender (mapped to 0 for Female, 1 for Male).
- **Age**: Age group of customers (converted to numerical values).
- **Occupation**: Profession of the customer.
- **City_Category**: City type (converted using one-hot encoding).
- **Stay_In_Current_City_Years**: Number of years a customer has lived in their current city (cleaned and converted to integer).
- **Product_ID**: Unique product identifier.
- **Product_Category_1**, **Product_Category_2**, **Product_Category_3**: Different categories of products purchased.
- **Purchase**: Purchase amount (target variable for training models).

## Data Cleaning and Preprocessing

The following preprocessing steps were performed on the dataset:
1. **Dropped irrelevant features**: `User_ID` was removed.
2. **Mapped categorical values**: Gender, Age, and City_Category were converted to numerical or one-hot encoded values.
3. **Handled missing values**: Missing values in `Product_Category_2` and `Product_Category_3` were filled using mode imputation.
4. **Formatted feature types**: Cleaned and converted `Stay_In_Current_City_Years` from string to integer.
5. **Data scaling**: Used `StandardScaler` to scale numerical features for model training.

## Data Visualization

Several visualizations were created to analyze customer purchasing behavior:
- **Purchase by Gender and Age**: Males generally have higher purchasing power across all age groups.
- **Purchase by Occupation**: Analysis of how different occupations impact purchasing behavior.
- **Product Categories**: Gender-wise purchase analysis across various product categories.

## Insights

- Males tend to have a higher purchasing power than females.
- Purchasing behavior varies across different occupations and product categories.

## Data Splitting and Preparation for Model Training

- The dataset was split into a **train** set and a **test** set based on the availability of the `Purchase` value.
- Feature scaling was applied to numerical columns to prepare the data for machine learning models.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Seaborn, Matplotlib for data visualization

## Acknowledgements

- **Kaggle** for providing the Black Friday Sales dataset.
