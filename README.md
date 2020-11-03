# Amazon_Vine_Analysis

## Overview
The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products.    

In this project we were tasked with performing the ETL process on a dataset provided by Amazon Web Services. The dataset consisted of various sports products reviews from Amazon Vine members and non Vine members. With the dataset we extracted, transformed, and connected to an AWS RDS instance where we loaded the transformed data into pgAdmin.

After transforming the data and loading them into SQL tables we used Pyspark to determine if there was any bias towards favorable views from Vine members in the dataset.

## Results



| paid reviews  | unpaid reviews| 5 Star Revies - Paid | 5 Star Reviews - Unpaid|Percentage of 5 Star Reviews - Paid|Percentage of 5 Star Reviews - Paid| 
| ------------- |:-------------:| --------------------:|-----------------------:|----------------------------------:| ---------------------------------:|
|        4,140  |     1,442,261 |               1,853  |                829,020 |                  44.75845410628019|                  57.48058083800366|
