# Credit Risk Classification Report

## Overview of the Analysis

* The purpose of this analysis is to help the nonprofit Alphabet Soup select applicants for funding with the best chance of success in their ventures.
* The column IS_SUCCESSFUL indicates whether or not the money was used sucessfully. 1 indicates success and 0 indicates failure.

## Results

* Data Preprocessing:
    * The IS_SUCCESSFUL variable is the target of the model.
    * The columns that remain except for NAME and EIN are the features. In the optimized version, the SPECIAL_CONSIDERATIONS column is also removed.
* Compiling, Training, Evaluating: 
    * Two hidden layers were used, the first with eight neurons and the second with 5. I used these because they were in the started code. I am having a lot of difficulty understanding these concepts.
    * I was not able to figure out hoe to improve the model performance. I changed the activation functions, the number of layers and the number of epochs.

## Summary

* The model works approximately the same accross all parameters. All-in-all, I need to do more research on these neural networks. A random forest model may be more appropriate.