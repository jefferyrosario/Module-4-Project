# Module 4 Final Project Pneumonia Classification

## Introduction

This repo contains a Pneumonia Classification on a dataset from Guanghzo.

### Problem Statement

A healthcare software company has found a target market in classifying pneumonia. The company wants to create a software with a GUI that can assist doctors, physician's assistants, and nurse practitioners in determining whether a patient has pneumonia.

We will use deep learning to classify the chest x-rays into normal or pneumonia.

## Contents

## Summary

1. Download dataset and divide dataset into train, validation, and test subdirectories

2. Visualize the data. Determine how many output variables there are. There were two, indicating a binary classification problem. There was also a class imbalance of 3:1, pneumonia to normal. 

3. Create a baseline model to determine baseline accuracy and loss. Use PCA to lower the dimensions.

4. Create a convolutional neural network model. CNN is best used for image classification. We created a baseline model to compare our following models with.

5. Determine accuracy, recall, precision of the model. Which metrics do we use to determine how well the model works? For cass were we would like to prevent false negatives, the recall score is most important.

The Confusion matrix below illustrates the true positive, false positive, true negative, and false negatives of the resulting predictions.

![alttext] 

## Conclusion 

CNN models yielded a 93% overall accuracy, with a 96% recall rate on positive cases. # Module-4-Project
