# SalifortMotorCapstoneProject

## Predicting whether employees leave the company or not in Salifort Motor

## Overview 
Your goals in this project are to analyze the data collected by the HR department and to build a machine learning model to predict whether or not an employee will leave the company.
This project utilized employees' data in Salifort Motor collected by Human Resources. 
The final random forest model performed with 96% accuracy,  87% precision and 97% AUC determining what features were most important in affecting employees' churn. 
Based on the model, last evaluation, number of projects, tenure and overworked were most influential in determining whether employee would leave the company or not. 

## Business Understanding 
Salifort Motor experienced big churn rate in employees' retention. 
It is time-consuming and expensive to find, interview, and hire new employees, increasing employee retention will be beneficial to the Salifort Motor.

## Data Understanding
The data, collected by HR from employees, consisted of approximately 1500 unique trips and 9 features. 
The features included information on number of projects, satisfaction level, tenure, and working hours. 
The bar chart below shows the breakdown of how many left company versus how many didn't leave and you can see around 17% of employees quit.

<img width="212" alt="Screen Shot 2023-10-29 at 3 10 20 PM" src="https://github.com/DreamSkyMXDan/SalifortMotorCapstoneProject/assets/20774401/fafeaa79-36cb-49e7-a31f-ce88cb7d4ea4">

## Modeling and Evaluation 
A random forest model comprising 300 decision trees was used to determine feature importance in whom would likely to quit. 
The below plot shows that last evaluation, number of projects, tenure and overworked were the Top 4 most important factors that would make employees to leave the company. 
The overall model performed with 96% accuracy, 87% precision and 97% AUC.

<img width="919" alt="Screen Shot 2023-10-29 at 3 23 27 PM" src="https://github.com/DreamSkyMXDan/SalifortMotorCapstoneProject/assets/20774401/bd409689-2ed0-4067-bbf9-ddf087134d88">

## Conclusion
This model can benefit HR in Salifort Motor company in knowing if any employee could leave the company. 
In the future, building a K-means model could also be beneficial to cluster the employees with similarities.
