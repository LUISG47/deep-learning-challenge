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

### Compiling, Training, and Evaluating the Model 

_How many neurons, layers, and activation functions did you select for your neural network model, and why?_

In the first attempt the following architecture was followed:

+ **First Hidden Layer**: 80 neurons.

+ **Second Hidden Layer**: 30 neurons.

+ **Output Layer**: 1 neuron (for binary classification).

On the activation functions we have this:

+ **Hidden Layers**: Use the **ReLU (Rectified Linear Unit)** activation function
  
+ **Output Layer**: Uses the **Sigmoid** activation function wich is suitable for binary classifications
  
+ **100 epochs** were chosen to allow adequate training time for the network to converge-

<img width="1013" alt="Screenshot 2025-03-19 at 6 41 08 p m" src="https://github.com/user-attachments/assets/e5384c10-57db-4b85-a875-1255060db9e6" />

<img width="769" alt="Screenshot 2025-03-19 at 6 41 16 p m" src="https://github.com/user-attachments/assets/8c93fb7c-1dcd-4e56-a9bc-841c07b68126" />


_Were you able to achieve the target model performance?_

With this first attempt we didn't make the target model performance as we obtained a 72.65% of accuracy and the minimum asked was 75%

<img width="757" alt="Screenshot 2025-03-19 at 6 26 06 p m" src="https://github.com/user-attachments/assets/7cd0e913-eee2-426e-af58-9e24eb672b74" />


So we will try 2 more attempts in order to try to get a better performance number


_What steps did you take in your attempts to increase model performance?_

Summary: 



Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
