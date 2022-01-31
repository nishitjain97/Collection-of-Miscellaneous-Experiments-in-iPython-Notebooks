# Collection of Miscellaneous Experiments in iPython Notebooks
This repository will containg iPython NBs with experiments perfomed based on articles, books or any source of knowledge I am perusing.

## 1. Weight Initialization in Neural Networks: A Journey From the Basics to Kaiming

* Neural networks are made of a layered architecture with each layer containing a set of weights, biases and an activation function

* Input to a layer is first multiplied with the weights, then biases are added to the product and finally it is passed through the activation function

* At the start of the training phase for an NN, weights and biases need to be initialized to any value, from where the training then corrects these values to reduce prediction error

    * Traditionally, weights are initialized by sampling from a standard normal distribution, while the biases are set to 1

    * However, this initialization can lead to exploding gradients (output from the layer becomes infinite or nan) or vanishing gradients (output becomes 0), which can prevent the training from converging to an optima