# Image completetion using deep convolutional neural networks
Mårten Nilsson, Axel Demborg, Patrik Barkman

## Description
In many applications it is desirable to restore distorted images or to remove disruptive elements in the image. In this project we will test a deep learning approach for solving this problem inspired by the procedure in http://bamos.github.io/2016/08/09/deep-completion/ where generative adversarial networks have been used to reconstruct images of faces. 

## Training data
To keep our work comparable with the results in the blog post, we will use the LFW dataset. If we have time we may try out working with ImageNet.

## Software packages
The project is to be implemented in TensorFlow.

## Initial set of experiments
We will start by evaluating the image completition on images where the center of the images have been blacked out, as well as images where a random set of pixels have been blacked out.

## How we will measure the success of the project
We will compare the distances between the real images and the distorted images for different implementations. We will use a simple averaging model as a baseline for comparison. The distances will probably be pixel-distance with some degree of smoothing. 

