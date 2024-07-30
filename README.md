# neural-network-challenge-2

# Neural Networks - Part 2

In this challenge we are tasked with creating a neural network that can be use to predict whether employees are likely to leave the company.

## Workflow
1. Prepare the data for the neural network model.
    - create target dataframe (y_df) based on the attrition and department columns
    - create feature dataframe (X_df) selecting 10 columns from original data, excluding the attrition and department columns
    - split the data into training and test dataframes
    - scale (X data) and encode (y data) both dataframes
2. Compile and evaluate the neural network model using tensor flow
    - create an input layer
    - create 2 shared hidden layers to the model
    - create a branch layer that includes another hidden layer and an output for layer the attrition data
    - create a branch layer that includes another hidden layer and an output layer for the department data
    - compile the model
    - fit the model
    - evaluate the models loss and accuracy
    - save and export the data to a keras file.
3. Summary
    - Determine if Accuracy is the best metric for this data.
    - What activation functions were used and why?
    - How could the model be improved?