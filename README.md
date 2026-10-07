# Customer Churn Analysis & Data Preprocessing

## Overview

This project focuses on exploring and preprocessing a Telco Customer Churn dataset as part of a Machine Learning task.

The objective is to understand the dataset, identify patterns in customer churn, handle data quality issues, encode categorical variables, and prepare the data for machine learning model training.

## Dataset

The dataset contains information about **7,043 customers** and includes customer demographics, account information, subscribed services, billing details, and churn status.

* **Initial records:** 7,043
* **Initial columns:** 21
* **Target variable:** Churn

## Work Performed

The notebook covers the following steps:

* Loaded and inspected the dataset
* Performed exploratory data analysis (EDA)
* Checked data types and missing values
* Identified and handled blank values in `TotalCharges`
* Analyzed customer churn patterns
* Examined relationships between numerical variables
* Encoded categorical variables
* Split the data into training and testing sets
* Prepared the final features for machine learning

## Key Results

* **7,043** customer records analyzed
* **45** features obtained after categorical encoding
* **5,634** samples in the training set
* **1,409** samples in the testing set
* Dataset successfully cleaned and prepared for the next stage of machine learning

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Project Structure

```text
SWYNEX-Dataset-Exploration-Preprocessing/
│
├── Task_1_Customer_Churn.ipynb
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
└── README.md
```

## Conclusion

The dataset was successfully explored, cleaned, transformed, and prepared for machine learning. The completed preprocessing workflow provides a structured dataset that can be used for the subsequent model training and evaluation stage.
