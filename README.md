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
So far we've only worked with toy datasets (MNIST, CIFAR-10) conveniently packaged by torchvision, where every image has the same size and shape. Now let's learn the real deal, and work from a varied collection of .jpg files.

For this section we'll be working with a version of the Cats vs. Dogs dataset inspired by a classic <a href='https://www.kaggle.com/c/dogs-vs-cats'>Kaggle competition</a>.<br>
A quick note - do <strong>not</strong> download the dataset from Kaggle! Ours is a cleaned version of the data without any 0by0 files, etc.<br>The images are similar to ones available from the <a href='http://www.image-net.org/'>ImageNet</a> database.

We have organized the files into train and test folders, and further divided the images into CAT and DOG subfolders. In this way the file path contains the label.
## References:
[Deep learning for stock prediction using numerical and textual information](https://www.researchgate.net/publication/306925671_Deep_learning_for_stock_prediction_using_numerical_and_textual_information)- Ryo Akita, Akira Yoshihara, Takashi Matsubara, Kuniaki Uehara
