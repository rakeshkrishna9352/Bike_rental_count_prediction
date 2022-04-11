# Bike_rental_count_prediction

## Motivation
Ridesharing has grown substantially in India and around the globe. Parallel to this, Bike sharing and rentals is also in demand. Bike-sharing rental process is highly correlated to the environmental and seasonal settings such as weather, day of week etc. Predicting the rental counts in a setting helps to meet the demand and optimise costs.
## Methodology
- The Bike-Rental dataset is imported from kaggle. The dataset as following features: record index, date, season, year, month, holiday, working day, weather code, Normalised Temperature, Normalised feeling temperature, humidity, windspeed, casual users, registered users, count of total rental bikes
- Inspecting and Cleaning the dataset.
- Manipulating few columns and dropping few which are unnncessary for prediction.
- Data Visualisation using plots and drawing inferences from the data - Season vs Counts, Year vs Count, Correlation between numerical values and count etc.
- Dealing with categorical features for making it suitable for regression models
- Building Regression models using Linear Regression, Decision Tree and investigating the corresponding R2 score.
- Using Hyperparameter tuning to optimise the model by traning the model with training set using GridSearchCV.

## Model Report
