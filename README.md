# ELECTRIC-VEHICLE-POPULATION-PREDICTION
![image](https://github.com/user-attachments/assets/493c1ebb-7967-496d-96c4-b1cc391bfe9c)

A thorough data analysis on electric vehicles is part of this research. A variety of visualisations are used to complement the analysed data, which includes a detailed examination of the attributes of various car types, their electric ranges, beginning pricing, and regional distributions.
### Project Summary
•	This dataset provides detailed information on Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs) registered through the Washington State Department of Licensing (DOL). 

•	It includes 235,693 rows and 17 columns, covering aspects such as geographic location, vehicle specifications, and eligibility for clean alternative fuel vehicle incentives. 

•	The project aims to use supervised machine learning techniques to analyze and predict trends in EV populations, offering valuable insights for promoting sustainable transportation.

### General Structure of Data

 Column Name      | Non-Null Values | Data Type |
 |--------------------------|-----------------|-----------|
 | VIN (1-10)               | 20543 | object |
 | County                   | 20543 | object |
 | City                     | 20543 | object |
 | State                    | 20543 | object |
 | Postal Code              | 20543 | float64|
 | Model Year               | 20543 | int64  |
 | Make                     | 20543 | object |
 | Model                    | 20543 | object |
 | Electric Vehcile Type    | 20543 | object |
 | CAFV                     | 20543 | object |
 | Electric Range           | 20543 | float64|
 | Base MSRP                | 20543 | float64|
 | Legislative District     | 20499 | float64|
 | DOL Vehicle ID           | 20543 | int64  |
 | Vehicle Location         | 20543 | object |
 | Electric Utility         | 20543 | object |
 | 2020 Census Tract        | 20543 | float64 |
 | VIN (1-10)               | 205439 | object |
 | County                   | 205436 | object |
 | City                     | 205436 | object |
 | State                    | 205439 | object |
 | Postal Code              | 205436 | float64|
 | Model Year               | 205439 | int64  |
 | Make                     | 205439 | object |
 | Model                    | 205438 | object |
 | Electric Vehicle Type    | 205439 | object |
 | CAFV                     | 205439 | object |
 | Electric Range           | 205431 | float64|
 | Base MSRP                | 205431 | float64|
 | Legislative District     | 204997 | float64|
 | DOL Vehicle ID           | 205439 | int64  |
 | Vehicle Location         | 205431 | object |
 | Electric Utility         | 205436 | object |
 | 2020 Census Tract        | 205436 | float64 |
 
 Data Type Distribution: float64(3), int64(3), object(1)
 Memory Usage: 26.6+ MB

 ### Tools and Technologies Used
•	Programming Language: Python

•	Data Analysis Tools: Pandas, NumPy

•	Visualization: Matplotlib, Seaborn

### Algorithms used
•	Linear Regression

•	Ridge Regression

•	Decision Tree Regressor

•	Random Forest Regressor

•	Support Vector Regressor

### Purpose of the Project
The purpose of this research is to compare and analyse electric car statistics. Exploratory data analysis (EDA) techniques were used to assess a number of variables, including the demographics, range, beginning price, and legal area of electric vehicles in various nations. Trends and variations in the electric car market across nations were brought to light during the data analysis process.

### Data Usage
https://catalog.data.gov/dataset/electric-vehicle-population-data

