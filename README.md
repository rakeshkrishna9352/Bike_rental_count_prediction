# Bike_rental_count_prediction

## Objective
Predication of bike rental daily count based on the environmental and seasonal settings.

## Motivation
Ridesharing has grown substantially in India and around the globe. Parallel to this, Bike-sharing and rentals are also in demand. The Bike-sharing rental process is highly correlated to the environmental and seasonal settings such as weather, day of the week, etc. Predicting the rental counts in a setting helps to meet the demand and optimise costs.

## Libraries Used
*NumPy, Pandas, Seaborn, Matplotlib, Scikit-learn Machine Learning Libraries and Algorithms*

## Methodology
- Importing Bike-Rental dataset from Kaggle. The dataset has the following features: record index, date, season, year, month, holiday, working day, weather code, normalised temperature, normalised feeling temperature, humidity, wind speed, casual users, registered users, count of total rental bikes
- Inspecting and cleaning the dataset.
- Manipulating a few columns and dropping which are unnecessary for prediction.
- Data Visualisation using plots and drawing inferences from the data - Season vs Counts, Year vs Count, correlation between numerical values and count, etc.
- Dealing with categorical features for making it suitable for regression models
- Building Regression models using Linear Regression, Decision Tree and investigating the corresponding R<sup>2 </sup> score.
- Using Hyperparameter tuning to optimise the Random Forest Regression model by training the model with a training set using GridSearchCV.

## Model Report
- The  R<sup>2 </sup>for the model was improved from 0.83 to 0.89 using Hyperparameter Tuning.

### Author
**K Rakesh** [LinkedIn profile](https://www.linkedin.com/in/rakesh-k-34b48516b/)



