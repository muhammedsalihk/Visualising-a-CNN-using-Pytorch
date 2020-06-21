# Visualising-a-CNN-using-Pytorch

## Introduction
In this project, we try to understand what is happening inside a CNN and what exactly are the convolutional filters trying to do. For that purpose, we are building a simple CNN for recognising hadnwritten digits in the MNIST dataset.

## Methodology
Here we build a simple CNN with two convolutional layers and train it on the MNIST dataset of handwritten digits. 

![CNN Architecture](https://github.com/muhammedsalihk/Visualising-a-CNN-using-Pytorch/blob/master/Images/Model.png)

Following that, we try to visualise what the output of the convolutional layer look like for a few rightly classified and misclassified samples.

## Results
**Activations for a rightly classified sample - The digit in the image is 9**

Layer 1

![Layer 1](https://github.com/muhammedsalihk/Visualising-a-CNN-using-Pytorch/blob/master/Images/9_right_layer1.png&s=100)

Layer 2

![Layer 2](https://github.com/muhammedsalihk/Visualising-a-CNN-using-Pytorch/blob/master/Images/9_right_layer2.png)

**Activations for a misclassified sample - The digit in the image is 6, but was predicted as 0**

Layer 1

![Layer 1](https://github.com/muhammedsalihk/Visualising-a-CNN-using-Pytorch/blob/master/Images/6_wrong_layer1.png)

Layer 2

![Layer 2](https://github.com/muhammedsalihk/Visualising-a-CNN-using-Pytorch/blob/master/Images/6_wrong_layer2.png)
