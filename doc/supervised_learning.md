# Supervised Learning
* Supervised learning is when we teach or train the machine using data that is well-labelled. 
* The model is trained until it can detect the underlying patterns and relationships between the input data and the output labels, enabling it to yield accurate labeling results when presented with never-before-seen data.
*  Supervised learning is good at classification and regression problems, such as determining what category a news article belongs to or predicting the volume of sales for a given future date.

Mapping Function -

$Y = f(x)$

* x is the input for the ML
* Y is the output from the ML
* f() is a mapping function discovered by the algorithm during training

The goal of supervised learning is to identify the mapping function using the labeled training dataset x and produce output Y.

## Classification
* Classification uses an algorithm to accurately assign test data into specific categories. 
* Classification algorithms are used for predicting discrete outcomes, if the outcome can take two possible values such as True or False, Default or No Default, Yes or No, it is known as **Binary Classification**. When the outcome contains more than two possible values, it is known as **Multiclass Classification**c.  
* Common classification algorithms are linear classifiers, support vector machines (SVM), decision trees, k-nearest neighbor, and random forest

## Regression
* Regression is used to understand the relationship between dependent and independent variables.
* A dataset containing features of the house such as lot size, number of bedrooms, number of baths, neighborhood, etc. and the price of the house, a Regression algorithm can be trained to learn the relationship between the features and the price of the house 


**Regression defination** -
* Regression is a statistical method for estimating the strength of the relation between a dependent variable and one or more independent variable 
* Types -
    * **Linear Regression** - 
        Linear regression analysis is used to predict the value of a variable based on the value of another variable. The variable you want to predict is called the dependent variable. The variable you are using to predict the other variable's value is called the independent variable

        $Y = F(x_{1},x_{2},...x_{3})$
        
        where -
        Y - is dependent(predicate),
        x... - independent(predictors),
        F - Linear Approximation

    * **Logistical Regression** -
        Logistic regression is a process of modeling the probability of a discrete outcome given an input variable. The most common logistic regression models a binary outcome
        
    * **Polynomial Regression** -
        Polynomial regression is a form of Linear regression where only due to the Non-linear relationship between dependent and independent variables, we add some polynomial terms to linear regression to convert it into Polynomial regression.

