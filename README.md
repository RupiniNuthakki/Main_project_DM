# Main_project_DM
Language used: Python
Jupyter Notebook

Mango leaf  diseases dataset:
https://www.kaggle.com/datasets/aryashah2k/mango-leaf-disease-dataset

This is my attempt of implementing the image classifier of mango leaf disease dataset from kaggle using CNN and other Machine Learning models like Random Forest, KNN, Decision tree, Naive Bayes.
In this dataset there are total 8 types of diseases including healthy. I downloaded the dataset from kaggle and named the folder as 'leaf-diseases'.

1. Initially, imported all necessary libraries and splitted the dataset into 80% training and 20% test dataset.
2. Defined batch size and image size
3. Started applying CNN model , I had done four models where in each model, improvised the model by doing hyperparameters tuning like adding more layers and epochs to prevent overfitting.I finally managed to get the accuracy from 78 to 95%.
4. Then I used a predict function to test the model based on giving image as input.
5. After saving a model, I also tried this image classification dataset using Random forest, KNN, Decision tree and Naive bayes.
6. Below is the final conclusion where proved that CNN is best for image classification.
Accuracies:      
CNN- 94.49%
Random Forest- 87%
KNN- 67.5%
Decision tree- 69%
Naive Bayes- 54.25%
Hence CNN is best for image classification.

