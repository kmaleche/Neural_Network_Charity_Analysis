# Neural_Network_Charity_Analysis

## Overview of the analysis: 
Using machine learning and neural networks to create a binary classifier that is capable of predicting whether loan applicants will be successful if funded by Alphabet Soup.

    Dataset: CSV containing more than 34,000 organizations that have received funding from Alphabet Soup

## Results: 

#### Data Preprocessing
    1. What variable(s) are considered the target(s) for your model?
        The target variable is 'IS-SUCCESSFUL', which denotes the success of the loan application.
    2. What variable(s) are considered to be the features for your model?
        Features for our model included: APPLICATION_TYPE', 'AFFILIATION' 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION','INCOME_AMT', 'SPECIAL_CONSIDERATIONS'
    3. What variable(s) are neither targets nor features, and should be removed from the input data?
        Non-beneficial ID columns 'EIN' and 'NAME' have been dropped.
#### Compiling, Training, and Evaluating the Model
    1. How many neurons, layers, and activation functions did you select for your neural network model, and why?
        In optimizing the model, I increased the neurons to 8 and 
    2. Were you able to achieve the target model performance?
        I was not able to achieve target preformance (75%) and instead clocked in at 72.6% accuracy.
    3. What steps did you take to try and increase model performance?
        I increased the number of neurons used in the model, increased the number of eopchs, and removed additional variables in attempt to reduce noise and improve performance.


