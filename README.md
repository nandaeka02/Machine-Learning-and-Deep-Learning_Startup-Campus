# Ch. 4: Machine Learning and Deep Learning
This is the assignment from Chapter 4: Machine Learning and Deep Learning.

In this chapter, I do:
- Data Segmentation using the Clustering method
- Comparing several Supervised Learning models
- Design and create a simple neural network (not a CNN, but with a perceptron model) for the MNIST Handwritten Digit Dataset

## Task 1
Creating the best prediction model to predict “Churn Status in Banking”.

**Scoring**
- Getting Best Accuracy > 86% : 100
- Getting Best Accuracy 85% - 86%: 85
- Getting Best Accuracy 84% - 85%: 70
- Getting Best Accuracy <84% : 55
- Any error in the code will become 0

## Task 2
Creating the best number of clusters for “Random Points”.

**Scoring**
- Getting Best Silhouette Score > 70: 100
- Getting Best Silhouette Score 65-70: 85
- Getting Best Silhouette Score 60-65: 70
- Getting Best Silhouette Score <65: 55
- Any error in the code will become 0

## Task 3
Deep Learning for MNIST Handwritten Digit Classification using PyTorch. This is an exploration task. Develop your end-to-end workflow for solving a Handwritten Digit Classification task using Neural Network architecture (**not Convolutional Neural Network**). These are the criteria for scoring:
- Loading your MNIST dataset for the data loader
- Visualize several MNIST datasets
- Design your Neural Network model
- Setup your hyperparameter such as Loss Function, Optimizer, Learning Rate, etc
- Develop a training loop and run a training model
- Evaluate the Model using several performance metrics such as accuracy, confusion matrix, F1 Score, Precision, Recall, etc
- Describe and explain your Result

## Bonus Task
This problem description is the same as Task 3. But there are some technical challenges that you have to choose one.
1. Compare 3 different configurations while your model is wider/deeper. Show and explain the performance result.
2. Compare 3 configurations for different Loss Function. Show and explain your performance result.
3. Compare 3 configurations for the activation function. Show and explain your performance result.
