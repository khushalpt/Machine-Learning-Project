# Machine-Learning-Project
Using CUDA C and Extreme Learning Machine to implement a Machine Learning Model on Cifar 10 and Cifar 100 datasets

Project Task:

Classification Task:
Object-centric Small Image recognition task with medium datasets (Datasets of Task 2)

Dataset
CIFAR10, CIFAR100 (you can use build-in function to load the datasets in Keras/Tensorflow)

Steps to follow to get best accuracy for given dataset:
Step1: Getting deep feature(s) from any pretrained deep convolutional neural network(s). Please make sure the end to end training IS NOT used in the project. Furthermore, data augmentation methods CAN NOT be used for performance improvement.
Step 2: Any feature combination methods are allowed to use to boost the performance such as PCA,
autoencoder, deep believe networks, etc. Students could use combined deep features from different deep convolutional neural networks as their final feature, and then send it to the classifier which have been mentioned in the Step 3.
Step 3: ELM-based classifier (CUDA code) should be used to get the final performance. The ELM classifier should be programed by CUDA C language.

