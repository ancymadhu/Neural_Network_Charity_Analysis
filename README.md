# Neural_Network_Charity_Analysis

## Analysis Overview

With the knowledge of machine learning and neural networks, we used the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. 

The following technical analysis are done:

> 1. Preprocessing Data for a Neural Network Model
> 2. Compile, Train, and Evaluate the Model
> 3. Optimize the Model

## Resources

* Data Source: Alphabet Soup Charity dataset (charity_data.csv)
* Software: Anaconda Navigator 1.9.12, Conda 4.8.4, Jupyter Notebook 6.0.3

## Results

### I. Data Preprocessing

> * Variables that are considered the target for the model

   The variable that was considered is the IS_SUCCESSFUL column.

> * Variables that are considered the features for the model

   The columns other than the dropped ones became the features for the model.
 
> * Variables that are neither targets nor features, and should be removed from the input data

   Removed the "EIN" and "NAME" columns as they did not offer any relevant data that could help the model perform better.

### II. Compiling, Training, and Evaluating the Model

> * Number of neurons, layers, and activation functions selected for neural network model

This model is made with input features & FOUR hidden layers. The layers have respectively 12, 6, 80 and 40 neurons each. 

![1](https://user-images.githubusercontent.com/73450637/110085560-40f38b80-7d5f-11eb-8de1-2fe99e08f0ae.png)

Each layer has an activation function. All the four hidden layers have an activation function "relu" & the output layer is "sigmoid".

![2](https://user-images.githubusercontent.com/73450637/110085565-4224b880-7d5f-11eb-87b4-e77471191e93.png)

> * Reagrding the target to be achieved

The target of the model was to achieve 75% and above and I was able to acheieve 73.25%.

![3](https://user-images.githubusercontent.com/73450637/110086036-e0b11980-7d5f-11eb-8ad3-1df4f152b777.png)

> * Steps taken to try and increase model performance

Some of the steps I took to try and make the model more accurate were adding hidden layers, changing the activation type, changing the number of epochs and changing the number of neurons in each layer.

## Summary

The accuracy of the prediction achieved was ~74% after dropping two features from the dataset. Recommendation for achieveing better perfromance would be to drop more unncessary features from the dataset. Even after trying with various number of neurons and hidden levels, no much difference in accuracy was showing up. The best way to increase the accuracy of the model is to have more accurate data. If we have solid data added to this model, the accuracy of this model will be much more concrete.


