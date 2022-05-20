# Project - INX_Future_Inc_Employee_Performance_CDS_Project2_Data_V1.8.xls
## Project Summary
The project given here is about one of the leading data analytics and automation solutions provider. The aim of project is to find the main causes of performance issues in the company to take the right course of actions and penalize the non-performing employees without affecting the morale of all the employees in general. And likewise, attracting the best talents to join the company.

The insights expected from this project are:
1. Top 3 important factors effecting performance of the employees
2. Department wise performances
3. A trained model which can predict the performance of employees based on the factors that will be used to hire the employees
4. Recommendations to improve the employee performance based on insights from analysis

We follow the steps of lifecycle for this Data Science project:
1. Identifying the case and categorising the problem to be solved Ex: Regression, Classification, Time Series
2. Collection of data
3. Identifying the dependent and independent variables
4. Getting the insights from data and finding which variables are impacting the target variable with the help of domain knowledge (Exploratory Data Analysis)
5. Processing the data as required by the dataset 
   a) Removing unwanted columns like ID's and columns with most missing values 
   b) Checking the missing values 
   c) Checking for outliers 
   d) Describing the categorical data and numerical data 
   e) Feature scaling 
   f) Handling the imbalance dataset 
   g) Formatting and cleaning the data
7. Performing feature selection operation Ex: Pearson correlation, Extra tree classifier, Heat map, etc.
8. Model selection an building.
   There are 2 methods in selecting a model 
   a) Testing all the possible algorithms for the data to check which algorithm works the best 
   b) Trying to understand what the algorithm does before deciding if it is good fit for the scenario Understanding how the algorithm works and it's limitations.
   
The dataset "INX_Future_Inc_Employee_Performance_CDS_Project2_Data_V1.8.xls" given is in the excel format. The structured data of employees has 1200 data for performing the Machine Learning Algorithms. The shape of the data is 1200,28. And the total number of features present in the data are 28. Out of which, there are 19 nummeric columns, 8 categoric columns and 1 alpha-numeric column (The column which represents the ID of the employees).

## I. Identifying The Scenario
The aim is to analyse the current employee data and list out the core underlying causes of performance issues in the company. The important Feature Selection is the use of target variables by removing the irrelevent variables present in the dataset (Dimensionally Reduction).

Correlation technique is used to determine how one variable is positively correlated/ negatively correlated/ not correlated with the other variables in the dataset.

We use the Classification type of Supervised Machine Learning Algorithms and group the conditions accordingly. The classified Machine Learning Models used in this project are - Random Forest and Gradient Booster Classifier as they predict considerably higher accuracy.

Random Forest Algorithm creates decision trees on data samples and then gets the prediction from each of them and finally selects the best solution by means of voting i.e, an ensemble method, where it reduces the over-fitting by averaging the result.

XGBoost (Extreme Gradient Boosting) is an implementation of gradient boosted decision trees designed for speed and performance. As it is used for our training data as it as multiple features to predict a target variable.

## II. Collection Of Data
The source of the excel format dataset "INX_Future_Inc_Employee_Performance_CDS_Project2_Data_V1.8.xls" is given from IABAC. The dataset is the detailed information of the performance of employees in particular aspects of their work. The company and the employee details mentioned in the dataset is a fictional scenario.

## III. Identifying The Dependent and Independent Variables
The dataset has 28 features about the employees which tells the relation between dependent and independent variables. The features can be divided into 3 types - Categorical, Numerical, Alpha-Numeric.

Categorical Features:
1. Gender
2. Education Background
3. Marital Status
4. Emp Department
5. Emp Job Role
6. Business Travel Frequency
7. Over Time
8. Attrition

Numerical Features:
1. Age
2. Distance From Home
3. Emp Education Level
4. Emp Environment Satisfaction
5. Emp Hourly Rate
6. Emp Job Involvement
7. Emp Job Level
8. Emp Job Satisfaction
9. Num Companies Worked
10. Emp Last Salary Hike Percent
11. Emp Relationship Satisfaction
12. Total Work Experience In Years
13. Training Times Last Year
14. Emp Work Life Balance
15. Experience Years At This Company
16. Experience Years In Current Role
17. Years Since Last Promotion
18. Years With Curr Manager
19. Performance Rating

Alpha - Numeric Features:
1. EmpNumber

## IV. Getting Insights From The Data (EDA - Exploratory Data Analysis)
We get the insights by reading the dataset and finding which variables are impacting the target variable with the help of domain knowledge. Finding the Shape, Description, Identifying relationship in the dataset and Organising the dataset.

## V. Processing The Data
We remove the unwanted column i.e, EmpNumber (which indicates the ID of the employee). Then check for NAN and NULL values if any, but there are none. We made a list of categorical and numerical data and perform feature scaling to check the type of data present in it. As there are none NAN and Null values, there is no requirement of cleaning the data.

## VI. Feature Selection
1. Reduce the number of input variables to develop a predictive model
2. Checking for the features with high correlation that are more linearly dependent on each other
3. Thereby performing analysis by visualising the heat map of correlation between all the numerical features present in the dataset
4. The pandas dataframe conviniently provides the Pearson Correlation values of all the columns of numerical data in the form of pairs. Therefore, only the numerical features are going to be used
5. The heat map indicates the level of numerical data correlating between 0 to 1

Here, Age is an important criteria for the Total number of work experience an employee has.

## VII. Model Selection and Building
After checking for all the possible algorithms on the dataset the best 2 algorithms that are suitable are Random Forest and Gradient Boosted Algorithm. The dataset is divided into Training set and Test set before implementing into the Machine Learning Models.

