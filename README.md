
# USED CAR PRICE PREDICTION USING MACHINE LEARNING
![image](https://user-images.githubusercontent.com/116062465/211891180-cb6a6b67-fccd-4277-8267-db8ce06f4c31.png)

## 1. INTORDUCTION
Second hand cars have a huge market base and many people consider buying an used car instead of getting a new one.Considering that their so many frauds in the market who not only sale wrong but also mislead to wrong price.

## 2. BUSINESS PROBLEM
### The Problem statement
Royal car Dealers have a car yard.They mainly deal in selling new cars but want to make a shift to second hand dealership like other yards.There is a lack of information available to consumers about the relationship between used car prices and mileage. As a result, consumers may end uppaying more or less for a used car than it is actually worth, leading to financial losses or missed opportunities for savings.

### Main Objective
This project aims at solving the problem of predicting the price of a used car based on their features, using machine learning techniques..This will help people to decide whether the used car is worth the posted price by different online sites used as well as plan on when sell their cars.

## 3. NOTEBOOK STRUCTURE
The python notebook is structured as follows:
1. Data cleaning
2. Exploratory Data Analysis
3. Feature selection 
4. Data Modelling and evaluation

## 4. DATA UNDERSTANDING
### The Data
The data used in this project was downloaded from Kaggle and these are the features.
The car name
The year the car was manufactured
The mileage(kmpl)
The car selling Price(indian Rupee)
The kms driven
max power
The type of fuel used
The seller type
The transmission type of the car
The owners
torque
seats
Lastly, to validate this data reference was made to an article by Toptal which can be accessed using the this link https://www.toptal.com/data-science/improving-imdb-rating-system. To confirm the validity of the data a a Kernel Distribution Estimation (KDE) graph was plotted.

### Data Preparation
The data was checked for missing values and some columns were found to have null values.The null values were handled by dropping all the rows with them.
Some columns were not in their appropriate data type so this was corrected to create a cleaner and easier to work with dataframe
We also found duplicates in the data which we dropped.

### Exploratory Data Analysis
By carrying out EDA on the cleaned data as seen in this notebook, various patterns were discovered in the dependent and independent variables.. This analysis made it possible to understand how the value of the dependent variable changes as the value of any of the independent variables change.

### Data Interpretation
In this Project, we are going to predict the Price of Used Cars using various features like  Selling_Price, Kms_Driven, Fuel_Type, Year etc. The data used in this project was downloaded from Kaggle.

## 5.CONCLUSIONS AND RECOMMENDATIONS
1.Selling Price of cars seems to have higher prices when sold by Dealers.
2.Selling Price would be higher for cars that are Automatic. 
3.Selling Price of cars with Fuel Type of Diesel is higher than Petrol, CNG  and LPG.

