# drug_persistency
This repository contains the code and final project report for a project aimed at predicting drug persistence among patients.

## Team Members
Alireza Samadi
Email: alirezasamadii71@gmail.com
Country: Rome, Italy
College: Sapienza University of Rome, Computer Engineering
Justin Lee
Email: justindavinlee@gmail.com
Country: Ontario, Canada
College: Wilfrid Laurier University, Data Science Concentration Big Data

## Problem Description
One of the challenges for all Pharmaceutical companies is to understand the persistence of drugs as per the physician’s prescription. The persistency of a drug may be defined as “the extent to which a patient acts in accordance with the prescribed interval, and dose of a dosing regimen.” Medication persistence refers to the act of continuing the treatment for the prescribed duration.

## Data Understanding
The dataset used in this project was retrieved from https://drive.google.com/file/d/1P_oMc6gOBlhw6dY5PxaqxV2swdHMUooK/view. The dataset contains 69 features and 3423 entries. The unique row id (Patient ID) was dropped since using a unique row id as a feature in our models will result in overfitting the data. Most features are of the ‘object’ dtype, which are categorical, as well as strings. These features will have to be converted to numeric values or dummy variables. In terms of problems within the data, there are no missing values within the dataset, although the dataset was skewed and heavily unbalanced. To deal with the problem of the unbalanced data, we will perform sampling techniques such as RandomUnderSampler and SMOTE (Synthetic Minority Oversampling Technique).
Note: For more details, please see the final project report.
