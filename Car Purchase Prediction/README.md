# Car Purchase Prediction
The main goal of this project is to predict the chance of buying a car given the following information about the car: model, year, price, transmission, fuel type, tax, miles per gallon, engine size, and mileage. <br><br>
Dataset: [_Ford.csv_](https://www.kaggle.com/datasets/adhurimquku/ford-car-price-prediction/data)

## Data Handling
The necessary outliers were dealt with. Then, based on different kinds of relationships, data were taken within a range to get an accurate representation of the data. The car models were also regrouped based on the type of car. 

## Feature Engineering
This was done twice in this project. The first time we used it was to find out the tax rate based on the tax and price of the car. Next time, when we did, we classified the cars into **3 different categories**: <br><br>
0 means the chances of buying the car are **High** <br>
1 means the chances of buying the car are **Moderate** <br>
2 means the chances of buying the car are **Poor** <br><br>

## Model Selection
The model used in this case is the KNN model. The value of n in the KNN model was 3.

## Result
The accuracy is really high, and it was mostly within [0.90-1.0].
