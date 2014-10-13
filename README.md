neural-network
==============

back-propagation algorithm for neural networks and apply it to the task of hand-written digit recognition.

##Introduction

This project, implements the hand written digits classifier based on artificial neural network. 

###Architecture

There are 5000 training examples in data.mat, where each training example is a 20 pixel by 20 pixel 
grayscale image of the digit. The network has 3 layers an input layer, hidden layer and an output layer.
Since the images are of size 20 X 20, this gives us 400 input layer units. We trained network with 25
hidden units and 10 output units for each digit class. run the main.m file using Matlab/Octave to go through
details for the training.

###Visualize Trained Hidden Layer (25 units)
Hidden layer learns new representation of the input and gives some insight into what's going on after the
training is complete. Following is the visualization of the hidden layer showing what each hidden unit learns
after training the network

![alt tag]()

###Conclusion


