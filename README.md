# deep-learning-challenge

## Overview
The purpose of this analysis is to develop a neural network to predict the likelihood of success for applicants seeking funding from Alphabet Soup using a dataset containing more than 34,000 organizations that have received funding from Alphabet Soup over the years.

## Results

### Data Preprocessing 
- The target variable is the "IS_SUCCESSFUL" column.
- The feature variables are the APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT columns.
- the NAME and EIN columns were removed from the input data because they are neither targets nor features.

### Compiling, Training, and Evaluating the Model 

#### Model 1 <br>
- 3 hidden layers<br>
    - first layer = 80 units <br>
    - second layer = 50 units <br>
    - third layer = 30 units <br>
- activation function = relu <br>
<br>

#### Model 2
- 4 hidden layers<br>
    - first layer = 200 units <br>
    - second layer = 150 units <br>
    - third layer = 100 units <br>
    - fourth layer = 50 units <br>
- activation function = relu <br>
<br>

#### Model 3 
- 2 hidden layers<br>
    - first layer = 70 units <br>
    - second layer = 30 units <br>
- activation function = tanh <br>
<br>
- None of the models achieved the target model performance of higher than 75% accuracy. <br>
- In an attempt to increase model performance, I modifid the number of layers and units for the model. <br>
- Random forest is another model that could solve this classification problem. <br>