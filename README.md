# Neural_Network_Charity_Analysis
## Overview
Alphabet Soup Charity provides money to charitable organization. The purpose of the analysis is to 

## Results

## Data Preprocessing
### What variable(s) are considered the target(s) for your model?
The target variable for the model is the IS_SUCCESSFUL variable that provides the success of the donation. 
### What variable(s) are considered to be the features for your model?
The feature variables for the model are all the variables other than the IS-SUCCESSFUL. 
### What variable(s) are neither targets nor features, and should be removed from the input data?
The 'EIN' and 'NAME' are not needed and should be removed from the input data. 

## Compiling, Training, and Evaluating the Model
### How many neurons, layers, and activation functions did you select for your neural network model, and why?
Used two hidden layers, the 1st layer has 80 neurons and the 2nd layer has 30 neurons. 
### Were you able to achieve the target model performance?
No.
### What steps did you take to try and increase model performance?
I added one hidden layer and increased the number of neurons in each layer. I also changed the activation functions in the hidden layers. 

## Summary

In summary most of the models have a greater than 70% accuracy. The neural networks are a good classification model. However, random forest regressors would possibly work better with the amount of data. 
