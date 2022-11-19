<h1 align="center"> Car Dekho Used Car Prediction </h1>

# Table of Contents

- [Problem Statement](#1-problem-statement)
- [About The Dataset](#2-about-the-dataset)
- [Tools and Technology](#3-tools-and-technology)
- [Visualization](#4-visualizations)
    - [Most Selling Used Car](#41-most-selling-used-car)
    - [Most Selling Brand](#42-most-selling-brand)
    - [Costliest Brand vs Selling Price](#43-costliest-brand-vs-selling-price)
    - [Costliest Car vs Selling Price](#44-costliest-car-vs-selling-price)
    - [Most Mileage vs Brand Name](#45-most-mileage-vs-brand-name)
    - [Best Mileage vs Car Name](#46-best-mileage-vs-car-name)
    - [KM Driven vs Selling Price](#47-km-driven-vs-selling-price)
    - [Fuel Type Selling Price](#48-fuel-type-selling-price)
    - [Most Sold Fuel Type](#49-most-sold-fuel-type)
    - [Fuel Type vs Mileage](#410-fuel-type-vs-mileage)
    - [Mileage vs Selling Price](#411-mileage-vs-selling-price)
    - [Vehicle Age vs Selling Price](#412-vehicle-age-vs-selling-price)


## 1. Problem Statement
This dataset comprises used cars sold on cardehko.com in India as well as important features of these cars.
If user can predict the price of the car based on input features.
Prediction results can be used to give new seller the price suggestion based on market condition.

## 2. About The Dataset
- The Dataset is collected from scrapping from cardheko.com
- The data consists of 13 column and 15411 rows.

## 3. Tools and Technology

- Python with Jupter Notebook
- Numpy - It provides a fast numerical array structure and operating functions.
- Pandas - It provides tools for data storage, manipulation and analysis tasks.
- Matplotlib - It is the basic plotting library in Python. It provides tools for making plots.
- Seaborn - It is also used in visualization.
- Scikit learn - The required machine learning library in Python.

## 4. Visualizations

### 4.1 Most Selling Used Car

<div align="center"><img src="images/most_selling_used_cars.png" alt="seller type" height="450" width="800"></div>

### 4.2 Most Selling Brand

<div align="center"><img src="images/most_selling_brands.png" alt="seller type" height="450" width="600"></div>

### 4.3 Costliest Brand vs Selling Price

<div align="center"><img src="images/costliest_brand_vs_selling_price.png" alt="seller type" height="450" width="850"></div>

### 4.4 Costliest Car vs Selling Price

<div align="center"><img src="images/costliest_car_vs_selling_price.png" alt="seller type" height="400" width="500"></div>

### 4.5 Most Mileage vs Brand Name

<div align="center"><img src="images/mileage_vs_brand_name.png" alt="seller type" height="400" width="600"></div>

### 4.6 Best Mileage vs Car Name

<div align="center"><img src="images/best_mileage_vs_car_name.png" alt="seller type" height="400" width="600"></div>

### 4.7 KM Driven vs Selling Price

<div align="center"><img src="images/km_driven_vs_selling_price.png" alt="seller type" height="450" width="800"></div>

### 4.8 Fuel Type Selling Price

<div align="center"><img src="images/fuel_type_selling_price.png" alt="seller type" height="400" width="500"></div>

### 4.9 Most Sold Fuel Type

<div align="center"><img src="images/most_sold_fuel_type.png" alt="seller type" height="450" width="450"></div>

### 4.10 Fuel Type vs Mileage

<div align="center"><img src="images/fuel_type_vs_mileage_boxplot.png" alt="seller type" height="400" width="500"></div>

### 4.11 Mileage vs Selling Price

<div align="center"><img src="images/mileage_vs_selling_price.png" alt="seller type" height="450" width="800"></div>

### 4.12 Vehicle Age vs Selling Price

<div align="center"><img src="images/vehicle_age_vs_selling_price.png" alt="seller type" height="450" width="800"></div>

## 5. Conclusions

- The datatypes and Column names were right and there was 15411 rows and 13 columns
- The `selling_price` column is the target to predict. i.e Regression Problem.
- Dealers are the highest sellers of the used cars.
- Vehicle age has negative impact on the price.
- Manual cars are mostly sold and automatic has higher selling average than manual cars.
- Petrol is the most preffered choice of fuel in used car website, followed by diesel and LPG.
- We just need less data cleaning for this dataset.

