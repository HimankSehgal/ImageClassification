# Image Classification using Pytorch and Convolutional Neural Networks

## Table of Contents: 
* Overview of Project

* Data Description 
* Libraries used

* Structure of the Approach

* Conclusion



## Overview of Project:

We are given a dataset which contains images of Dogs and Cats . Our aim is to develop an algorithm  which will take an input image and based on parameters the algorithm has learned , it will predict whether the given input test image is a cat or dog

## Data Description:   
For this project , I will be using the data from a Kaggle Competition named <a href='https://www.kaggle.com/c/dogs-vs-cats'>Dogs v. Cats</a>.<br>
It has a varied collection of .jpg files which have been organized by me into separate train and test folders, and further divided the images into CAT and DOG subfolders.This helps to easily track files while writing the code .The data folders have been given in this repository

Total number of images in dataset : 24994<br>
Number of images in train set : 18743<br>
Number of images in test set : 


## Libraries used:
* Numpy

* Pandas
* Matplotlib

* torch
* torchvision<br>
  
* sklearn

* os module of python

## Structure of the Approach

* ### 5. Define a convolutional neural network
</t>
Define a CNN model that can be trained on the Fashion-MNIST dataset. The model should contain two convolutional layers, two pooling layers, and two fully connected layers. You can use any number of neurons per layer so long as the model takes in a 28x28 image and returns an output of 10. Portions of the definition have been filled in for convenience.
