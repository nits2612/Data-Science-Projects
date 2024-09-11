
# Employee Turnover Analytics

## Project statement:

Portobello Tech is an app innovator who has devised an intelligent way of 
predicting employee turnover within the company. It periodically evaluates 
employees' work details, including the number of projects they worked on, 
average monthly working hours, time spent in the company, promotions in the 
last five years, and salary level.
Data from prior evaluations shows the employees’ satisfaction in the workplace. 
The data could be used to identify patterns in work style and their interest in 
continuing to work for the company. 
The HR Department owns the data and uses it to predict employee turnover. 
Employee turnover refers to the total number of workers who leave a company 
over time.

## Task at Hand:
My job is to analyze the employee turnover data of the company and select and build a Machine Learning model choosing across different evaluation
metrics to predict the turnover and suggest a retention strtaegies based on different categories.

## Approach to the problem:
I performed the following steps as part of ML approach to come up with conclusions to help company make an informed decision:

1) EDA: Utilized the EDA techniques to deal with the null values, duplicates and data pre processing as part of EDA and understood what
factors contributed to most in turnover.

2) Data Clustering: Used K-Means clustering on data based on training and evaluation performance to identify the trends.

3) Class Imbalance: Used SMOTE analysis to handle the class Imbalancein training and test data.

4) ML Model: Used various ML models like logistic regression, Random forest, Gradient Boosting classifier and applied 5-fold CV. Identified the
best ML model based on F1 score and AUC graph.

5) Categorization: Categorize the predicted turnover of employees into various zones like High Risk, Medium Risk, Low Risk and Safe zone so that various retention strategies can be preapared.


## Tech Stack

Python, Pandas, Numpy, Matplotlib, Seaborn, Sklearn, Jupyter Notebook.

