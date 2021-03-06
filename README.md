# Neural_Network_Charity_Analysis
## Overview of the analysis: 
The purpose of this analysis was to create a neural network using the dataset of Alphabet Soup's funded organizations (over 34,000 organizations) to be able to predict whether applicants will be successful if funded by Alphabet Soup. The dataset from the funded organizations was preprocessed using tools such as "one-hot encoding" and bucketing. Data was split into target and feature arrays, further split into training and test datasets and scaled. A neural network model was built using two hidden layers, the model resulted in 73% (0.7255) accuracy when being evaluated. Attempts to optimize the neural network model to achieve an accuracy of 75% and above were not successful.

## Results: 

### Data Preprocessing
- The column "IS SUCCESSFUL" in the dataset was considered the target for the model.
- All other columns in the dataset were considered features for the model.
- Noisy variables that are neither features or targets should be removed from the input dataset. In this exercise, identification columns such as "EIN" and "NAME" were removed from the input dataset.

### Compiling, Training, and Evaluating the Model
- The challenge required us to build a neural network with two hidden layers, the first hidden layer with 80 neurons, the second hidden layer with 30 neurons, using relu activation funtions within the hidden layers and a sigmoid activation function in the output layer. This model resulted in a 73% accuracy (0.7255). The model was considered a baseline and optimization attempts were used to optimize this neural network model. 
- ![Model_Structure_Baseline](https://github.com/AaraniSivasekaram/Neural_Network_Charity_Analysis/blob/main/Model_Structure_Baseline.png)
- ![Accuracy_Results_Baseline_Model](https://github.com/AaraniSivasekaram/Neural_Network_Charity_Analysis/blob/main/Accuracy_Results_Baseline_Model.png)
- My final neural network model consisted of three hidden layers, the first hidden layer had 120 neurons, the second hidden layer had 80 neurons and the third hidden layer had 40 neurons. Activation functions for the hidden layers included relu and sigmoid, and activation function of the output layer used tanh. 
- ![Model_Structure_Opt#3](https://github.com/AaraniSivasekaram/Neural_Network_Charity_Analysis/blob/main/Model_Structure_Opt%233.png)
- I was not able to achieve the target model performance of 75% or above. 
- ![Accuracy_Results_Opt#3](https://github.com/AaraniSivasekaram/Neural_Network_Charity_Analysis/blob/main/Accuracy_Results_Opt%233.png)
- Attempts to optimize the neural network model to achieve the target model performance included: increased the number of neurons in the hidden layers, increasing the number of hidden layers and changing the types of activation functions used in the hidden layers and output layer. These attempts at optimization were not successful.

## Summary: 
- Overall, all four deep learning models built in this challenge resulted in accuracy scores of 72% - 73%, the models were 73% accurate in classifying whether a charity applicant funded by Alphabet Soup would be successful.
- Given the needs of this dataset were to determine a binary classification, whether an applicant funded by Alphabet Soup would be successful or not successful, a logistic regression model could also be used. Logistic regression models are useful when predicting the probability of input data belonging to one of two groups, in this case, successful or not successful. However, given the size of this dataset (over 34,000 organizations' data) a neural network was probably the best way to go.
