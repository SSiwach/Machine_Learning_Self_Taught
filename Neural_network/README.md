# Neural Network
Artificial neural networks are computational systems that can learn to perform tasks by considering examples, generally without being programmed with any task-specific rules. It is supposed to mimic a biological system, wherein neurons interact by sending signals in the form of mathematical functions between layers. All layers can contain an arbitrary number of neurons, and each connection is represented by a weight variable.

An artificial neural network (ANN), is a computational model that consists of layers of connected neurons, or nodes or units. We will refer to these interchangeably as units or nodes, and sometimes as neurons.

It is supposed to mimic a biological nervous system by letting each neuron interact with other neurons by sending signals in the form of mathematical functions between layers. A wide variety of different ANNs have been developed, but most of them consist of an input layer, an output layer and eventual layers in-between, called hidden layers. All layers can contain an arbitrary number of nodes, and each connection between two nodes is associated with a weight variable.

## Feed-forward neural networks
The feed-forward neural network (FFNN) was the first and simplest type of ANNs that were devised. In this network, the information moves in only one direction: forward through the layers.

## Convolutional Neural Network
Convolutional neural networks emulate the behaviour of neurons in the visual cortex by enforcing a local connectivity pattern between nodes of adjacent layers: Each node in a convolutional layer is connected only to a subset of the nodes in the previous layer, in contrast to the fully-connected FFNN. Often, CNNs consist of several convolutional layers that learn local features of the input, with a fully-connected layer at the end, which gathers all the local data and produces the outputs. They have wide applications in image and video recognition.

## Recurrent neural networks
 Recurrent neural networks have connections between nodes that form directed cycles. This creates a form of internal memory which are able to capture information on what has been calculated before; the output is dependent on the previous computations. Recurrent NNs make use of sequential information by performing the same task for every element in a sequence, where each element depends on previous elements. An example of such information is sentences, making recurrent NNs especially well-suited for handwriting and speech recognition.

## Multilayer perceptrons
One uses often so-called fully-connected feed-forward neural networks with three or more layers (an input layer, one or more hidden layers and an output layer) consisting of neurons that have non-linear activation functions.

Such networks are often called multilayer perceptrons (MLPs).

## The multilayer  perceptron (MLP)

The multilayer perceptron is a very popular, and easy to implement approach, to deep learning. It consists of
1. A neural network with one or more layers of nodes between the input and the output nodes.

2. The multilayer network structure, or architecture, or topology, consists of an input layer, one or more hidden layers, and one output layer.

3. The input nodes pass values to the first hidden layer, its nodes pass the information on to the second and so on till we reach the output layer.

For an MLP network there is no direct connection between the output nodes/neurons/units and  the input nodes/neurons/units.
Hereafter we will call the various entities of a layer for nodes. There are also no connections within a single layer.

The number of input nodes does not need to equal the number of output nodes. This applies also to the hidden layers. Each layer may have its own number of nodes and activation functions.


# Activation Funciton



![image](https://user-images.githubusercontent.com/54826291/202520313-c1a124e2-459d-419f-85e2-d707dbcd0eb7.png)
![image](https://user-images.githubusercontent.com/54826291/202520354-32c82a6d-3c2e-488e-82ff-e6873549ab41.png)
![image](https://user-images.githubusercontent.com/54826291/202520387-0d085325-3e75-47e3-8c29-68f1c8e4dac8.png)
![image](https://user-images.githubusercontent.com/54826291/202520414-274f7f00-149e-44ab-a261-bacc2927815f.png)
