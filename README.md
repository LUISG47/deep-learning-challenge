# Deep-learning-challenge

## Overview of the analysis: 


The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. In this assignment we will use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, there is a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

+ **EIN and NAME**—Identification columns
+ **APPLICATION_TYPE**—Alphabet Soup application type
+ **AFFILIATION**—Affiliated sector of industry
+ **CLASSIFICATION**—Government organization classification
+ **USE_CASE**—Use case for funding
+ **ORGANIZATION**—Organization type
+ **STATUS**—Active status
+ **INCOME_AMT**—Income classification
+ **SPECIAL_CONSIDERATIONS**—Special considerations for application
+ **ASK_AMT**—Funding amount requested
+ **IS_SUCCESSFUL**—Was the money used effectively

## Results: 

### Data Preprocessing
First the csv looks like this:

![Screenshot 2025-03-18 at 10 15 00 p m](https://github.com/user-attachments/assets/921b09ad-fadb-41d7-a954-70451ab26168)


_What variable(s) are the target(s) for your model?_

The target variable of the model is:

**IS_SUCCESSFUL**—Was the money used effectively

_What variable(s) are the features for your model?_

The features variables of the model are the other columns such as:

+ **APPLICATION_TYPE**—Alphabet Soup application type
+ **AFFILIATION**—Affiliated sector of industry
+ **CLASSIFICATION**—Government organization classification
+ **USE_CASE**—Use case for funding
+ **ORGANIZATION**—Organization type
+ **STATUS**—Active status
+ **INCOME_AMT**—Income classification
+ **SPECIAL_CONSIDERATIONS**—Special considerations for application
+ **ASK_AMT**—Funding amount requested


_What variable(s) should be removed from the input data because they are neither targets nor features?_

The variables that should be removed are the 
+ **EIN and NAME**—Identification columns

As they are not directly correlated to the success outcome desired

__Compiling, Training, and Evaluating the Model__

_How many neurons, layers, and activation functions did you select for your neural network model, and why?_

_Were you able to achieve the target model performance?_

_What steps did you take in your attempts to increase model performance?_

Summary: 



Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
