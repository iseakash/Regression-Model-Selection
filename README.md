# Regression-Model-Selection

Problem is to predict the dependent variable which is Energy Output based on the four features - engine temperature, exhaust vacuum, ambient pressure and relative humidity.

Apply different regression models and select the best model on the basic of "r2square" metric for this particular dataset.

Different Regression Models applied here are as follow :-
•	Multiple Linear regression
•	Polynomial Regression
•	Decision Tree Regression
•	Random Forest Regression
•	Support Vector Regression.

Data Description:-
The dataset is taken from UCI machine learning repository for Combined cycle power plant.
It contains almost 10000 observations with 4 numerical features and has no missing data nad no categorical data.

Steps:-
        1.	Importing the libraries
        2.	Importing the dataset
        3.	Splitting the dataset into the Training set and Test set
        5.      Feature Scaling (if required)
        4.	Training the Different Regression models on the Training set
        5.	Predicting the Test set results
        6.	Evaluating the Model Performance

Conclusion:-
The r2square obtained from these models are:
•	Multiple Linear regression - 0.93
•	Polynomial Regression - 0.94
•	Decision Tree Regression - 0.92
•	Random Forest Regression - 0.96
•	Support Vector Regression - 0.95.

Random Forest Regression with maximum r2square value of 0.96 beats all other regression models for this dataset.
