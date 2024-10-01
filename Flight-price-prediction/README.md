# Flight Price Prediction

This project involves predicting flight ticket prices using a dataset that includes various features such as journey date, departure time, arrival time, number of stops, and flight duration. The goal is to engineer meaningful features and prepare the dataset for machine learning models to accurately predict flight prices.

## Dataset

The dataset consists of the following features:
- **Airline**: The airline operating the flight.
- **Source**: The departure city.
- **Destination**: The arrival city.
- **Date_of_Journey**: The date of the flight (further split into day, month, and year).
- **Dep_Time**: Departure time of the flight (split into hours and minutes).
- **Arrival_Time**: Arrival time of the flight (split into hours and minutes).
- **Duration**: Flight duration (converted into total minutes).
- **Total_Stops**: Number of stops in the flight journey.
- **Additional_Info**: Miscellaneous information related to the flight.

## Data Preprocessing and Feature Engineering

The following preprocessing and feature engineering steps were performed:
1. **Date Splitting**: The `Date_of_Journey` feature was split into `Date`, `Month`, and `Year`.
2. **Time Conversion**: Both `Dep_Time` and `Arrival_Time` were split into hours and minutes for better granularity.
3. **Handling Categorical Features**: Categorical variables like `Airline`, `Source`, `Destination`, and `Additional_Info` were label-encoded to convert them into numerical form.
4. **Stops Mapping**: The `Total_Stops` feature was mapped to numerical values (e.g., non-stop = 0, 1 stop = 1, etc.).
5. **Duration Conversion**: The `Duration` feature was split into hours and minutes and then converted into total minutes for consistency.
6. **Handling Missing Values**: Missing or erroneous values in the `Duration` feature were addressed by removing invalid entries and filling missing minutes with zero.

## Technologies Used

- Python
- Pandas
- NumPy
- Seaborn, Matplotlib for data visualization
- Scikit-learn for preprocessing

## Insights

- The number of stops (non-stop vs. 1 stop, 2 stops, etc.) plays a significant role in the ticket price.
- Flight duration in minutes also has a clear impact on price.

## Acknowledgements

- **Kaggle** for providing the flight price dataset.
