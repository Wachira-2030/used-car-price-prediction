
# USED CAR PRICE PREDICTION USING MACHINE LEARNING
![image](https://user-images.githubusercontent.com/116062465/212169589-cd768617-111d-4470-92f7-8334dee9e861.png)


## 1. INTORDUCTION
Royal Car Dealers has a car yard. They primarily sell new cars but hope to expand into used car sales like other yards. There is a large market for used cars. Because of the large price difference between new and used cars, many people prefer to buy used.The car yard is hoping to expand and venture into sale of used cars. Information about the appropriate price to sell is not available so the management has requested for a model that could predict the price of a used car based on its features.

## 2. BUSINESS PROBLEM
### The Problem statement
Information about the appropriate price to sell is not available so the management has requested for a model that could predict the price of a used car based on its features.We identify the features that are significant in predicting the price of a usde car.We also identify how well those features describe the price of a used car.This will help the car yard to decide whether the used car is worth the posted price to the consumers.

### Main Objective
This project aims at solving the problem of predicting the price of a used car based on their features, using machine learning techniques.

## 3. NOTEBOOK STRUCTURE
The notebook is [here](https://github.com/Wachira-2030/used-car-price-prediction/blob/main/index1.ipynb)
The python notebook is structured as follows:
1. Data cleaning
2. Exploratory Data Analysis
3. Feature selection 
4. Data Modelling and evaluation

## 4. DATA UNDERSTANDING
### The Data
The data used in this project was downloaded from [Kaggle ](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho) 
and these are the features.
- The car name
- The year the car was manufactured
- The mileage(kmpl)
- The car selling Price(indian Rupee)
- The kms driven
- max power
- The type of fuel used(whether the car uses petrol,diesel CLG or PLG
- The seller type(Individual/Dealer)
- The transmission type of the car(Gear System is Automatic/Manual)
- The owners(first owner/Second Owner)
- Torque power in newtons meters
- Seats(No.of seats )
- Lastly, to validate this data reference was made to an article by [Data Bridge Market Research](https://www.databridgemarketresearch.com/reports/global-used-car-market)

### Data Preparation
The data was checked for missing values and some columns were found to have null values.The null values were handled by dropping all the rows with them.
Some columns were not in their appropriate data type so this was corrected to create a cleaner and easier to work with dataframe.
We also had duplicates in the data which we dropped.

### Exploratory Data Analysis
By carrying out EDA on the cleaned data as seen in this notebook, various patterns were discovered in the dependent and independent variables.. This analysis made it possible to understand how the value of the dependent variable changes as the value of any of the independent variables change.

![image](https://user-images.githubusercontent.com/116062465/212166267-f6765288-de1a-4d4d-a03b-2d92c201d2a0.png)

The lighter values indicate a high value of correlation while the darker values indicate low value of correlation
### Data Interpretation
In this Project, we are going to predict the Price of Used Cars using various features like  Selling_Price, Kms_Driven, Fuel_Type, Year etc. 

![image](https://user-images.githubusercontent.com/116062465/212165581-2cd03e5e-b4f7-459f-937f-2a64e808b325.png)



## 5.CONCLUSIONS 
- Selling Price of cars seems to have higher prices when sold by Dealers.
- Selling Price would be higher for cars that are Automatic. 
- Selling Price of cars with Fuel Type of Diesel is higher than Petrol, CNG  and LPG.
- The model explains 75% of the variation in the selling price of the cars.
- The top factors that affect the selling price are Maximum power,torque and seats.
- For each increase of 1 bhp in max_power , we see an associated increase of about 0.3769 Dollars.
- For each increase of 1 km in km_driven, we see an associated drop of about 0.1118 Dollars.
- 
## 6.RECOMMENDATIONS
- Royal Car Dealers should pursue the business as it is profitable (cars sold by dealers go for higher prices). 
- Royal car yard should consider selling automatic cars, those that have higher max_power and those that use diesel because most consumers prefer them as shown by the   increase in selling price
- When choosing which cars to purchase, they should consider the km that it has been driven since 1 km increase in km_driven leads to a decrease in selling price.


## 7.REPOSITORY GUIDE
- The data set used can be found [here](https://github.com/Wachira-2030/used-car-price-prediction/blob/main/Car%20details%20v3.csv)
- The data report can be found [here](https://docs.google.com/document/d/1B9I0-xRG8lxLWqaBFGVek-dTkqbagRHvYpjNrPdN8tU/edit#heading=h.k2dex7ijg0)
- The notebook can be found [here](https://github.com/Wachira-2030/used-car-price-prediction/blob/main/index.ipynb)
