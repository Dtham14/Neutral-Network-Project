# Neutral-Network-Project

This project was designed to build a neural network from scratch in Python.  A brain tumor dataset from Kaggle was used to train the neural network to make a multiple-output classification model.  This dataset contains 7023 human brain MRI images classified into 4 classes: glioma - meningioma - no tumor and pituitary.

To create the best model, I approached these experiments with a rapid-iteration methodology by changing individual hyperparameters manually and observing what changes made the largest impact. Dozens of hyperparameter configurations, activation functions, tuning learning rates, optimizers, and the number of nodes and layers were tested. The model with the best performance used 5 dense layers, each with a relu activation function, with the fifth layer using softmax, along with an adamax optimizer.  

