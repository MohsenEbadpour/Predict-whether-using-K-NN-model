# Predict whether using K-NN model
This repository contains code for a problem related to predict whether using K-NN model in pattern recognition. The problem involves predicting whether task based on dataset of daily climate records.

## Course Information

This problem is related to a *Statistical Pattern Recognition* course taught by Professor Mohammad Rahmati (<rahmati@aut.ac.ir>) in the Computer Engineering department at Amirkabir University of Technology (AUT) in Tehran, Iran. The course was offered in the Fall of 2021.

## Problem Description

The given problem deals with a dataset of daily climate records collected from various weather stations of the Bureau of Meteorology (BOM) in Australia. The objective is to predict whether tomorrow will be rainy or not. First, some preprocessing steps are needed, such as removing samples with unassigned target values, replacing null values with the median of the same month, and partitioning the dataset into train, test, and validation sets.
a. To avoid overfitting, highly correlated features are identified using the correlation coefficient and one feature from each pair with a coefficient over 0.95 is removed.
b. The next step is to select the 10 best features using the sequential feature selection method.
c. The K-NN algorithm is applied to the modified dataset to predict tomorrow's weather condition. The best value of K is found using the validation set, and the accuracy of the model is reported on the test set.


![Output](/output.png)
![Output](/output-2.png)


## Repository Contents

The repository contains Python code for the problem described above, as well as a Jupyter notebook that explains the problem and provides a step-by-step cells for running the code.

## Feedback

If you have any feedback or suggestions for improving this code, please feel free to open an issue in the repository as well as send an email to Mohsen Ebadpour (<m.ebadpour@aut.ac.ir> , <mohsenebadpour@outlook.com>).
