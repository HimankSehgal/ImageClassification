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

* ### 1. Defining Transformations for train and test data
As different images have different sizes, it is important to define a tranform function which can take different images and return images which have similar aspect ratios and size. We will be using functions from <tt> torchvision.transforms </tt> like <tt>  transforms.Resize( )</tt> , <tt> transforms.CenterCrop() </tt> for this purpose. Also the pictures will be in form of pixels. We need to convert that to tensor values. For that we will use the function <tt> transforms.ToTensor() </tt><br>
Apart from these transformations which will be applicable for both train and test data ,  we will also apply certain transformations for loading train data like <tt> transforms.RandomRotation() </tt> and <tt> transforms.RandomHorizontalFlip() </tt> because the size of our training set is very smaall i.e 18743 , so these transformations will help to augment the size of data set 
 
* ### 2. Load the train and test data into notebook and applying the described transformations and divide them into minibatches

Defining <tt> train_data </tt> and <tt> test_data </tt> and loading images from the path where they were saved in the computer along with applying the transformations described above. Also, since it is a common practice to divide the data into mini batches , so we will be doing the same using the <tt> torch.utils.data.DataLoader()</tt>

* ### 3. Defining the model class

Define a CNN model that can be trained on the Fashion-MNIST dataset. The model should contain two convolutional layers, two pooling layers, and two fully connected layers. You can use any number of neurons per layer so long as the model takes in a 28x28 image and returns an output of 10. Portions of the definition have been filled in for convenience.

* ### 4. Define a convolutional neural network <br>

Define a CNN model that can be trained on the Fashion-MNIST dataset. The model should contain two convolutional layers, two pooling layers, and two fully connected layers. You can use any number of neurons per layer so long as the model takes in a 28x28 image and returns an output of 10. Portions of the definition have been filled in for convenience.

* ### 5. Define a convolutional neural network <br>

Define a CNN model that can be trained on the Fashion-MNIST dataset. The model should contain two convolutional layers, two pooling layers, and two fully connected layers. You can use any number of neurons per layer so long as the model takes in a 28x28 image and returns an output of 10. Portions of the definition have been filled in for convenience.
