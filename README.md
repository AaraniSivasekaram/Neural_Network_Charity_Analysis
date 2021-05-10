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
- My final neural network model consisted of three hidden layers, the first hidden layer had 120 neurons, the second hidden layer had 80 neurons and the third hidden layer had 40 neurons. Activation functions for the hidden layers included relu and sigmoid, and activation function of the output layer used tanh. 
- I was not able to achieve the target model performance of 75% or above. 
- Attempts to optimize the neural network model to achieve the target model performance included: increased the number of neurons in the hidden layers, increasing the number of hidden layers and changing the types of activation functions used in the hidden layers and output layer. These attempts at optimization were not successful.

## Summary: 
- The deep learning models
- Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
