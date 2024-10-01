# Sales-Prediction-Model-for-House-Prices
#Project Description


This project focuses on building predictive models to estimate house prices using a dataset of house sales. The primary goal is to explore the relationship between house features (such as area, bedrooms, bathrooms, etc.) and their corresponding prices, and to create predictive models using Linear Regression and Random Forest algorithms. The dataset includes various features like the number of bedrooms, area, number of bathrooms, availability of guest rooms, and whether the house is on the main road, among others.

Key Features of the Dataset:

Area (square feet)

Bedrooms

Bathrooms

Stories

Parking spaces

Guestroom availability

Air conditioning

Furnishing status (furnished, semi-furnished, unfurnished)

Proximity to main road, etc.



#Tools and Libraries





#The following libraries were used in this project:



Pandas for data manipulation
NumPy for numerical computations
Matplotlib and Seaborn for data visualization
scikit-learn for model building and evaluation



#Approach
1. Data Preprocessing


Missing Values: The dataset was checked for missing values and cleaned accordingly.
One-hot Encoding: Categorical features like guestroom availability, proximity to main roads, and air conditioning were transformed into numerical values using one-hot encoding.
Train-Test Split: The dataset was split into training and testing sets (80% for training and 20% for testing).


#2. Model Building


Two models were implemented:



Linear Regression: A simple and interpretable regression model.
Random Forest Regressor: A more complex and powerful ensemble learning model.


#3. Model Evaluation
Mean Squared Error (MSE) and R² Score were used to evaluate the performance of both models.
The models were compared based on their prediction accuracy and error metrics.


#Findings


The Linear Regression model yielded an R² score of 0.653, indicating moderate predictive power. The Mean Squared Error (MSE) was 1.75 trillion.
The Random Forest model performed slightly worse than Linear Regression, with an R² score of 0.612 and an MSE of 1.96 trillion.
Despite being a more sophisticated model, Random Forest did not outperform Linear Regression in this case, possibly due to the relatively small dataset or the nature of the features.


#Conclusion


The models demonstrated the ability to predict house prices based on the given features, though there is room for improvement.
Linear Regression was more effective in this particular dataset than the Random Forest model.
Future improvements could include feature engineering, scaling the data, hyperparameter tuning, and testing additional models to enhance predictive accuracy.
