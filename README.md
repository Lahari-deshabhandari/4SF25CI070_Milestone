 # 🛒 Retail Sales Analysis Using Python

## Project Overview

Retail Sales Analysis is a data analysis project that uses Python to examine customer and order information. It focuses on cleaning, processing, analysing, and visualising retail sales data to understand sales patterns and customer information.

## Objectives

- Understand and analyse retail sales data.
- Identify missing and duplicate values.
- Perform data cleaning and preprocessing.
- Extract useful information from datasets.
- Analyse shipping fees and total amounts.
- Represent data using graphs and charts.

## Dataset Description

The project uses two CSV datasets, each containing approximately 1,000 records.

### Customer dataset (`customer.csv`)

`CustomerID`, `FirstName`, `LastName`, `Email`, `PhoneNumber`, `Address`, `Country`, `DateOfBirth`, `Gender`

### Order dataset (`order.csv`)

`OrderID`, `CustomerID`, `OrderDate`, `OrderStatus`, `ShippedDate`, `ShipAddress`, `ShipCountry`, `ShippingFee`, `PaymentMethod`, `TotalAmount`

## Technologies and Libraries

- Python and Jupyter Notebook
- Pandas — data manipulation and analysis
- NumPy — numerical operations
- Matplotlib — data visualisation
- Seaborn — statistical visualisation

## Data Loading and Inspection

Load the datasets with Pandas:

```python
import numpy as np
import pandas as pd

df = pd.read_csv("customer.csv")
pf = pd.read_csv("order.csv")
```

Useful inspection methods and properties:

- `head()` and `tail()` — display the first and last five records.
- `info()` — display dataset information.
- `describe()` — provide a statistical summary.
- `shape` — display the number of rows and columns.

## Data Cleaning and Preprocessing

- Identify missing values using `isnull()` and check dataset information.
- Remove unnecessary columns and handle missing values using the mean where appropriate.
- Create a `FullName` column by combining first and last names.
- Select specific rows and columns using `loc` and `iloc`.
- Convert columns to appropriate data types where required.

## Data Analysis

- Analyse customer details and country-wise information.
- Examine order statuses.
- Analyse shipping fees and total order amounts.
- Calculate average values.

## Data Visualisation

- **Scatter plot — Shipping Fee vs Total Amount:** represent the relationship between shipping fees and total order amounts.
- **Histogram — Distribution of Total Amount:** explore the distribution and frequency of total order amounts.

## Results and Observations

- Customer and order datasets were loaded, and their structure and statistics were examined.
- Missing values and unnecessary columns were identified.
- A `FullName` column was created.
- Numerical analysis was performed on shipping fees and total amounts.
- Scatter plots and histograms were generated to explore the data.

## Conclusion

This project uses Python to clean, preprocess, analyse, and visualise customer and order information, extracting meaningful insights from retail sales datasets. It provides practical experience with Pandas, NumPy, Matplotlib, and Seaborn.

## Future Scope

- Predict future sales using machine learning.
- Identify customer purchasing patterns.
- Analyse monthly and yearly sales trends.
- Develop an interactive sales dashboard.
- Improve business decision-making using data insights.

---

**Project:** Retail Sales Analysis Using Python  
**Tools:** Python, Jupyter Notebook  
**Domain:** Data Analytics
