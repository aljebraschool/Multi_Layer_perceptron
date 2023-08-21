# Multi_Layer_perceptron

## This Multi-layer perceptron was developed using the MNIST dataset to meet the prerequisites of the Udacity Introduction to Deep Learning Nanodegree program.

A Multi-Layer Perceptron (MLP) stands as a foundational component within the landscape of machine learning and serves as a cornerstone of deep neural networks. It's a type of feedforward neural network that's characterized by its layered architecture, comprising an input layer, one or more hidden layers, and an output layer. Each layer contains nodes, also known as neurons, that process information and pass it to subsequent layers.

In the context of an MLP, each neuron in a layer is connected to every neuron in the subsequent layer. These connections are associated with weights that determine the significance of the information transfer between neurons. Additionally, each neuron is equipped with an activation function, which introduces non-linearity to the network. This non-linearity is crucial for the model to capture complex relationships present in the data.

The hidden layers in an MLP serve as feature extractors, progressively learning more abstract and intricate representations of the input data. As information flows through the network, transformations occur at each layer, enabling the model to identify intricate patterns and features within the input data. Finally, the output layer produces predictions or classifications based on the learned representations from the hidden layers.

In the project at hand, I constructed a model leveraging the power of an MLP to recognize and categorize hand-written digits. By training this model on the well-known [MNIST dataset](https://www.tensorflow.org/datasets/catalog/mnist), which is composed of grayscale images of handwritten digits, I aimed to harness the capabilities of an MLP in order to achieve accurate digit identification and classification

 

## Requirements
- PyTorch
- Numpy
- Matplotlib
- Multilayer Perceptron
