# Readmission-Prediction-for-Diabetic-Patients
Hospital readmission rates are a significant contributor to hospital inpatient services spending, readmission of patients is also an indicator to care quality. Diabetes is one of the leading causes of death worldwide and also one of the most expensive chronic diseases in the United States. Patients with diabetes who are hospitalized are at a higher risk of readmission than those without the disease. Reducing readmission rates for diabetic patients has the potential to significantly reduce medical costs.


The primary objective of the project is to be able to predict if a diabetic patient will be readmitted to the hospital. In the context of this dataset readmission is in three categories: greater than 30 days, less than 30 days, and “No”. The dataset contains variables related to diagnosis, secondary diagnosis, and variables containing information about medication prescribed to the patients while admitted to the Hospital . The Target variable categories "<30 days", and "No" were combined to form the categories "Yes", "No".

* The data set was obtained from the UCI Machine Learning Repo,https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008

There are three Steps to the Project 

* Data Pre Processing - The file contains the code chunks which were to clean the dataset (remove NULL values, data type mismatches)
* Exploratory Data Analysis - Univariate, Bivariate Analysis , Distributions and Boxplots and important patterns and trends were observed in the dataset 
* Modelling and Performance Evualtion - Hypothesis Testing Using ANOVA, Chi-Square Tests , Classification Modelling(SVM,Logistic Regression,KNN,Naive Bayes) and Performance Evaluation using ROC-AUC Curves and classification matrix and other metrics 

The Modelling methods were able to provide the significant factors associated with readmission of patients, Increasing the Number of Lab tests performed could signficantly decrease the readmission rate 
