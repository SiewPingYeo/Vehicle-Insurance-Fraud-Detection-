# Vehicle-Insurance-Fraud-Detection-
Vehicle insurance fraud is a real-life problem that most insurance companies face. It involves conspiring to make false or exaggerated claims involving property damage or personal injuries following an accident, staging accidents where fraudsters deliberately “arrange” for accidents to occur, using phantom passengers where people who were not even at the scene of the accident claim to have suffered grievous injury. They can also make false personal injury claims where personal injuries are grossly exaggerated.

Such fraud cases are intolerable as it can lead to significant losses for the company if the claim amount is large. It can also affect the victims (drivers) who are targeted in such fraud cases, as their future vehicle insurance premiums can be significantly higher and they will no longer be eligible for no-claim discount.

Therefore, such fraud cases must be treated seriously and companies will need to do their best to minimise such cases.

This dataset consists of vehicle and insurance-related details taken from Kaggle (https://www.kaggle.com/datasets/shivamb/vehicle-claim-fraud-detection) and is originally a real-life fraud machine learning case study used by Oracle. There are a total of 33 columns and 15420 rows. There are 8 continuous features and 24 categorical features. A label to indicate if it is a fraud case is also included – FraudFound_P (0,1)

## Problem Statement

In this project, we aim to help the insurance company to filter out potential fraud cases and minimise actual fraud cases.

## End Goal 

Create a machine learning model to predict if a specific vehicle insurance claim is a fraudulent one. Supervised classification model – predict if case is fraudulent or not (Binary Classification)

## Sub-goals: To uncover other patterns or trends for such fraud cases through exploratory data analysis

1. How do the features vary for fraud cases ?

2. How do the demographics (e.g. Age, Gender, Marital Status) vary with the features for fraud cases?

      - There was a decreasing trend for fraud occurences from 1994 to 1996. Why was that happening? Were there a difference in the demographics along the years?

      - As most of the vehicles involved in fraud were priced from 20000−29000 and mostly Sedan, what were the demographics for this group of fraudsters?

      - For the top 3 common car models in fraud cases, what were the demographics of this group of fraudsters?

## The workflow of this project is as follows:

1. Import relevant libraries and dataset
2. Initial data exploration
3. Initial data cleaning and wrangling
4. Exploratory data analysis
5. Data-preprocessing and Feature engineering (covered in Part 1 - Project Script - Exploratory Data Analysis and Data-Preprocessing 
6. Machine Learning (covered in Part 2 - Project script -Machine Learning)

## Outcome

Best model : Logistic Regression Model with class weights adjusted

Recall score: 0.92 

AUC score: 0.80

- True business costs will have to be considered before the model can be deployed. 

## Libraries Used 
1. Numpy 
2. Pandas
3. Matplotlib
4. Seaborn
5. sklearn
6. imblearn
7. MLxtend
8. Scipy
9. XGBoost
10. eli5 

## Feedback

If you have any feedback, please feel free to reach out to me at yeosiewping@gmail.com
