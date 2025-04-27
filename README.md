# Flight-price-Prediction
Predicting the flight prices on different seasons and months

# Problem Statement
Predict flight ticket prices based on flight-related details (like airline, source, destination, duration, etc.) using machine learning models, especially focusing on Random Forest Regressor.

# Objective
* To build machine learning models that can accurately predict flight prices.
* Special emphasis is on using the Random Forest Regressor for the best performance.

# Dataset Information:

* flight (Flight number or ID)

* airline (Name of the airline)

* source_city (City where flight takes off)

* departure_time (Time of departure)

* stops (Number of stops)

* arrival_time (Time of arrival)

* destination_city (City where flight lands)

* class (Economy/Business class)

* duration (Duration of flight in hours as a float)

* days_left (Days left for the flight)

* price (Target variable - ticket price)

# Data Cleaning Done:

* Checked for null values and duplicates.

* Dropped unnecessary columns like Unnamed: 0.

* Feature Engineering:

   * Extracted Hours and Minutes separately from the duration.

   * Encoded categorical variables using Label Encoding.

   * Dropped duration after splitting it.

 # Algorithms and Techniques Used
1 Exploratory Data Analysis (EDA):

* Boxplots for outlier detection.

* Line plots to visualize price trends by airline.

2 Preprocessing:

* Label Encoding of categorical variables.

* Standardization using StandardScaler.

* Checking multicollinearity using Variance Inflation Factor (VIF).

3 Models Applied:

* Linear Regression

* Decision Tree Regressor

* Random Forest Regressor (Main Model)

4 Evaluation Metrics:

* R² Score

* MAE (Mean Absolute Error)

* MAPE (Mean Absolute Percentage Error)

* MSE (Mean Squared Error)

* RMSE (Root Mean Squared Error)

# Model Performance

* Random Forest gave the best results among the three models.

* The predictions were visualized using distribution plots to compare actual vs predicted prices.

# Conclusion

*  Random Forest Regressor is a strong model choice for flight price prediction in this case.
*  It can help customers plan better by giving good estimates and help airlines in dynamic pricing strategies.



  

    



