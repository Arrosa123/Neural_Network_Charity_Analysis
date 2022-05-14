# Neural_Network_Charity_Analysis

## Overview of the loan prediction risk analysis:

With knowledge of machine learning and neural networks, use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, we received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

1) EIN and NAME—Identification columns
2) APPLICATION_TYPE—Alphabet Soup application type
3) AFFILIATION—Affiliated sector of industry
4) CLASSIFICATION—Government organization classification
5) USE_CASE—Use case for funding
6) ORGANIZATION—Organization type
7) STATUS—Active status
8) INCOME_AMT—Income classification
9) SPECIAL_CONSIDERATIONS—Special consideration for application
10) ASK_AMT—Funding amount requested
11) IS_SUCCESSFUL—Was the money used effectively

## Results:

### Data Preprocessing

                                                                                                   
- What variable(s) are considered the target(s) for your model?

"IS_SUCCESSFUL" category is the target variable for the model.

![2022-05-13](https://user-images.githubusercontent.com/96403349/168413386-a94df0a5-d6cb-43e1-891c-4cd91a6a12a5.png)

- What variable(s) are considered to be the features for your model?

 EIN, NAME, APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT, IS_SUCCESSFUL are considered to be the features of the model. 

- What variable(s) are neither targets nor features, and should be removed from the input data?

We removed the EIN and NAME columns from this model. 

![2022-05-13 (1)](https://user-images.githubusercontent.com/96403349/168413586-80f1b0ba-a53e-4a99-9bb0-c07a95d5b246.png)

### Compiling, Training, and Evaluating the Model

- How many neurons, layers, and activation functions did you select for your neural network model, and why?

There are two hidden node layers with 80 input//neurons in the first layer with the second smaller layer containing 30 input/neurons. The neural network model contains 2 hidden layers and an output layer each with activation functions: "relu" ,"relu" and "sigmoid".

![2022-05-13 (2)](https://user-images.githubusercontent.com/96403349/168413675-3b270c1e-687c-4c73-9274-40314e563672.png)

- Were you able to achieve the target model performance?

The accuracy recorded was 72.5% with a loss of 56.7%. 

![2022-05-13 (3)](https://user-images.githubusercontent.com/96403349/168413787-e6e408a8-1082-4f95-a4b1-af6576246df9.png)

- What steps did you take to try and increase model performance?
 
 To increase model performance I increased the number of neurons and layers with each attempt. With each additional attempt the accuracy rating went down.
 
 ## Summary: 
 The results of the analysis show that deep learning can be instrumental in helping with the decision making process. The attempts to optimize the model also failed to reach the target of 75%. The goal is to get to 75% accuracy, I would try to go down in the number of neurons, layers, and activation functions instead of going in the other direction. In this way, this would decrease the amount of unique values and may improve the overall accuracy of the model as well.
 





