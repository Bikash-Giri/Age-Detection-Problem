# Age-Detection-Problem
Disclaimer:
If u are unknown about CNN please consider reading about CNN in details first.This project consists of simple example of 
how CNN can be used and it doesn't explain the idea of the algorithm.I have written comment in every step
to make it look easier and understandable.

Description:
This repository consists of a project where the idea is to classify the age from the given dataset.For training our model,
inside the train dataset there is a train.csv file.This file consist of image name under the id column and category of age
under the Class column.The age of the picture is divided into three categories.They are as follows:
Young
Middle
Old
Convulutional Neural Network is used here to train our model and classify the images from the dataset

Idea :
1-Read the images from dataset
2-store the images in array 
3-Resize the images 
4-Prepare our data to CNN
  4.1-The steps in Convolutional Neural  Network are:
    *CONVOLUTION
    *SUBSAMPLING
    *ACTIVATION
    * FULLY CONNECTED(During Training)
5-Appy CNN
6-Check accuracy
7-Optional:
  7.1 Try changing the parameter like increasing or decreasing epochs of CNN,add validation steps etc
  7.2 Try adding more convulutional layers
   
