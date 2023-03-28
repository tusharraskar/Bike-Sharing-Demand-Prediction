# Bike-Sharing-Demand-Prediction

Predicting the bike count required at each hour for the stable supply of rental bikes.

**Problem Statement:**

Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

**Aim of project:**

The goal of the company Seoul Bike is providing the city with a stable supply of rental bikes. It becomes a major concern to keep users satisfied. The crucial part is the prediction of bike count rents at each hour for a stable supply of rental bikes. We can suppose that this study could be reported to the company 'Seoul Bikes'. We think it could help them knowing if yes or not they have to supply bike stations in the city, in order to keep the customers.

**Attribute Information:**

●	Date : The day of the day, during 365 days, type : str

●	Rented Bike Count : Number of rented bikes per hour which is the target, type : int

●	Hour: The hour of the day, type : int

●	Temperature(°C): Temperature per hour, type : Float

●	Humidity(%): Humidity in the air in %, type : int

●	Wind speed (m/s) : Speed of the wind in m/s, type : Float

●	Visibility (10m): Visibility in m, type : int

●	Dew point temperature(°C): Temperature at the beginning of the day, type : Float

●	Solar Radiation (MJ/m2): Sun contribution, type : Float

●	Rainfall(mm): Amount of rain in mm, type : Float

●	Snowfall (cm): Amount of snow in cm, type : Float

●	Seasons: Season of the year, type : str

●	Holiday: If it is holiday period, type: str

●	Functioning Day: If it is a Functioning Day, type : str


**Model Implementation and Evaluation:**

Model Name                           | R2 Score | MAE       | MSE        | RMSE     | Adj R2  |
----------                           |----------|-----------|------------|----------|---------|
Logistic Regression                  | 0.76     | 4.656     | 36.91      | 6.075    | 0.75    | 
Lasso Regression                     | 0.76     | 4.66      | 37.09      | 6.09     | 0.75    | 
Ridge Regression                     | 0.76     | 4.596     | 36.794     | 6.065    | 0.75    |  
Decision Tree Regression             | 0.81     | 3.32      | 28.56      | 5.33     | 0.81    |
Random Forest Regressor              | 0.89     | 2.7       | 16.886     | 4.109    | 0.88    |
XGBoost Regressor                    | 0.91     | 2.432     | 13.189     | 3.631    | 0.91    | 



**Conclusion:**

**Hperparameter Tuning:**

After Hyperparameter tuning on XGBoost Regressor model using Random Search CV we can see the slight change in the accuracy i. e.

MAE is reduced from 2.432 to 2.166

MSE is reduced from 13.189 to 11.294

RMSE is reduced from 3.631 to 3.360

R2-Score is increased from 0.916 to 0.925

Adjusted R2-Score is increased from 0.913 to 0.925

This results can said to be good for this dataset.

