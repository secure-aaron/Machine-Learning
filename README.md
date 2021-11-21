# Machine-Learning
This repository contains Machine Learning code using Pandas DataFrame objects.

## Dataset Analysis
Using the train.csv dataset file, the following Python Notebooks will be used.

### Calculate Missing Values
1. First, a calculation will be performed to add up the number of missing values in all of the variables in the dataset.
2. List itemThen, columns of dtype object are imputed with the most frequent value in the column to remove null values.
3. Next, string encoding will be performed to encode string values to integers.
4. Afterwards, the models will be split into training and testing sets using a ratio of 80 to 20.
5. Finally, the a predictive model will be created using the DecisionTreeClassifier and finally evaluated. 

### Testing Models
This notebook is very similar to the one above, however it performs the feature selection process using the chi^2 method. As a reault, the numpy arrays will be converted into Pandas DataFrame objects to compute the f and p values of the chi-squared test between each attribute and the target class in the dataset. Furthermore, it will use features with a p value less than 0.05 because this is the f value used in statistics and means the feature is significant. Although, sometimes 0.01 may be used instead.

Addditionally, multiple different models are trained and tested in this notebook including: 
- Decision Tree with features selected only
- Support Vector Machine with features selected only
- Naive Bayes with features selected only
- Decision Tree using all features
- Support Vector Machine using all features
- Naive Bayes using all features

## Employees
Using the employees.txt dataset file, the following Python Notebooks will be used.

### Calculate Gross Pay
This program will calculate the gross pay for employees. Any hours worked over 30 are paid at time and a half (1.5 times the regular hourly rate).

### Employees
PART A:
This program displays the records that are in the employees.txt file

PART B:
This program allows the user to search the employees.txt file for records matching an employee name.

## Project

This is the final project that I worked on which gives a good reason why machine learning is important, how to to extract and prepare the data to be used in the Data Analysis process, split the data, perform feature selection, build different predictive models, and finally test the data.
