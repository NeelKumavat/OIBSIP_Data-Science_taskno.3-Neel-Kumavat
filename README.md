# OIBSIP_Data-Science_taskno.3-Neel-Kumavat

Objective
The goal of this project is to build a machine learning model that can predict the selling price of a car based on features like its age, fuel type, transmission, seller type, and kilometers driven.
This helps in understanding the factors influencing car prices and assists both buyers and sellers in pricing decisions.

Dataset Used
car data.csv
It contains the following features:

Car_Name – Name of the car

Year – Manufacturing year

Selling_Price – The price the owner wants to sell

Present_Price – Ex-showroom price

Kms_Driven – Distance driven in kilometers

Fuel_Type – Petrol, Diesel, or CNG

Seller_Type – Dealer or Individual

Transmission – Manual or Automatic

Owner – Number of previous owners

 Tools & Technologies Used
Python

Pandas – Data loading and preprocessing

Seaborn & Matplotlib – Visualizations

scikit-learn – Model training and evaluation

RandomForestRegressor – Regression model

Steps Performed
1. Data Exploration & Cleaning
Loaded dataset with pandas.

Checked for missing values and data types.

Encoded categorical columns using LabelEncoder.

2. Visualizations
Boxplot: Selling_Price vs Year

Boxplot: Selling_Price vs Fuel_Type

3. Feature Selection & Preprocessing
Removed the Car_Name column (non-numeric).

Target variable: Selling_Price

Input features: Year, Present_Price, Kms_Driven, Fuel_Type, etc.

Data split into training and testing sets (80/20).

4. Model Training
Trained a Random Forest Regressor using scikit-learn.

Predicted car prices on the test set.

5. Model Evaluation
Calculated R² Score and Mean Absolute Error (MAE).

Compared actual vs predicted prices using a table and scatter plot.

6. Result Display
Displayed predicted prices alongside car names.

Compared predicted vs actual selling prices.

Outcome
The Random Forest model predicted car prices with good accuracy.

Factors like Present Price, Fuel Type, and Transmission significantly impacted price.

Visual comparison confirmed high correlation between predicted and actual values.

