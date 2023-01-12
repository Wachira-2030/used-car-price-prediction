
# USED CAR PRICE PREDICTION USING MACHINE LEARNING
![image](https://user-images.githubusercontent.com/116062465/212169589-cd768617-111d-4470-92f7-8334dee9e861.png)


## 1. INTORDUCTION
Second hand cars have a huge market base and many people consider buying an used car instead of getting a new one.Considering that their so many frauds in the market who not only sale wrong but also mislead to wrong price.

## 2. BUSINESS PROBLEM
### The Problem statement
Royal car Dealers have a car yard.They mainly deal in selling new cars but want to make a shift to second hand dealership like other yards.There is a lack of information available to consumers about the relationship between used car prices and mileage. As a result, consumers may end up paying more or less for a used car than it is actually worth, leading to financial losses or missed opportunities for savings.

### Main Objective
This project aims at solving the problem of predicting the price of a used car based on their features, using machine learning techniques..This will help people to decide whether the used car is worth the posted price by different online sites used as well as plan on when sell their cars.

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
The car name
The year the car was manufactured
The mileage(kmpl)
The car selling Price(indian Rupee)
The kms driven
max power
The type of fuel used(whether the car uses petrol,diesel CLG or PLG
The seller type(Individual/Dealer)
The transmission type of the car(Gear System is Automatic/Manual)
The owners(first owner/Second Owner)
Torque power in newtons meters
Seats(No.of seats )
Lastly, to validate this data reference was made to an article by [Data Bridge Market Research](https://www.databridgemarketresearch.com/reports/global-used-car-market)

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



## 5.CONCLUSIONS AND RECOMMENDATIONS
- 1.Selling Price of cars seems to have higher prices when sold by Dealers.
- 2.Selling Price would be higher for cars that are Automatic. 
- 3.Selling Price of cars with Fuel Type of Diesel is higher than Petrol, CNG  and LPG.
- 4.The model explains 75% of the variation in the selling price of the cars.
- 5.The top factors that affect the selling price are Maximum power,torque and seats.
- 6.For each increase of 1 bhp in max_power , we see an associated increase of about 0.3769 Dollars.
- 7.For each increase of 1 km in km_driven, we see an associated drop of about 0.1118 Dollars.
- 8.Would highly recommend car buyers to buy  car from individuals rather than going to dealers.



## 6.REPOSITORY GUIDE
The data set used can be found [here](https://github.com/Wachira-2030/used-car-price-prediction/blob/main/Car%20details%20v3.csv)
The data report can be found [here](https://docs.google.com/document/d/1B9I0-xRG8lxLWqaBFGVek-dTkqbagRHvYpjNrPdN8tU/edit#heading=h.k2dex7ijg0)
The notebook can be found [here](https://github.com/Wachira-2030/used-car-price-prediction/blob/main/index.ipynb)
