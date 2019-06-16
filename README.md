# Secure-and-Private-AI
Learning Different Privacy Techniques in Deep Learning using Python

### Lesson 1

`` torch Library is the part of python packages ''

### Functions Used  

1. randn(a,b)  -- for generating random numbers of shape (a,b)
2. randn_like(input) -- to generate random numbers of shape like input
3. torch.sum(a,b) -- performs summation of a  and b just like numpy
4. torch.mm(a,b) -- performs multiplication of a and b 
5. k.reshape(a,b) -- creates a new tensor with same data of k and size (a,b) . The cloning operation is done in different part of memeory 
6. k.resize_ -- returns the same tensor of different shape but there will be be some loss of data in tensor the memory hold the original data
7. k.view -- returns a new tensor with same data of k and size (a,b)
8. torch.from_numpy(vector_name) -- converts numpy array into torch

## Learning Gradient Descent, Forward Propogation, BackPropogation

In MNIST dataset we pass images through Neural Network and enable it to predict images with higher probability

## GradientDescent

Goal: Minimize the Loss so as to make better prediction of numbers better (i.e, maximizing the propbability)

### *How?*

We adjust these network parameters and minimize the loss which is done by using **Gradient Descent**. We have to minimize this gradient so as to minimize the **loss**

## BackPropogation



