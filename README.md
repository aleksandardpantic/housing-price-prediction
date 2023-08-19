# housing-price-prediction
## Features
+ ***Price***: The price of the house.
+ ***Area***: The total area of the house in square feet.
+ ***Bedrooms***: The number of bedrooms in the house.
+ ***Bathrooms***: The number of bathrooms in the house.
+ ***Stories***: The number of stories in the house.
+ ***Mainroad***: Whether the house is connected to the main road (Yes/No).
+ ***Guestroom***: Whether the house has a guest room (Yes/No).
+ ***Basement***: Whether the house has a basement (Yes/No).
+ ***Hot water heating***: Whether the house has a hot water heating system (Yes/No).
+ ***Airconditioning***: Whether the house has an air conditioning system (Yes/No).
+ ***Parking***: The number of parking spaces available within the house.
+ ***Prefarea***: Whether the house is located in a preferred area (Yes/No).
+ ***Furnishing status***: The furnishing status of the house (Fully Furnished, Semi-Furnished, Unfurnished).

**Using Bayesian Ridge regressor on 12 variables to predict the Price of the house.**<br>


## Metrics

Adjusted R squared **(a-R<sup>2</sup>)** and Root Mean Squared Error **(RMSE)**

## Results

Model explains approx. `64.3%` of variability of the target variable with Root Mean Squared Error of `0.57`

## Note

*Model was tuned by Grid Search and 5-fold cross-validated.*<br>

