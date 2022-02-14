# stepik-dl-cv

My attempts at solving the Stepik ["Neural networks and computer vision"](https://stepik.org/course/50352) course tasks.

Files:
- `module03_sin_prediction.ipynb` — *One-dimensional regression with fully connected networks.* In this notebook we will approximate the noisy sine data with a simple fully connected neural network (1 hidden layer with sigmoid activation) and see how various network parameters (such as the learning rate, the activation function, number of epochs...) affect the quality of our network;
- `module03_wine_prediction.ipynb` — *# Wine quality prediction with fully connected networks.* In this notebook we try to achieve the best classification accuracy on the classical [wine quality](https://archive.ics.uci.edu/ml/datasets/wine+quality) dataset by varying the neural network's hyperparameters;
- `module04_mnist_fc.ipynb` — *MNIST classification by a fully connected network.* In this notebook we construct a fully connected network with two hidden layers for the MNIST dataset, and then see how its quality and training time are affected by its learning parameters (such as number of epochs, batch size, and an optimizer);
- `module05_mnist_conv.ipynb` — *MNIST classification by LeNet.* In this notebook we apply the classic LeNet network to the MNIST dataset classification and try to modify it in order to achieve better test prediction accuracy.
- `module06_mnist_batchnorm.ipynb` — *Convolutional networks for the CIFAR dataset.* In this notebook we construct our own convolutional network and train it on the CIFAR dataset. Moreover, we compare its performance with various ResNet's and measure the effects that various regularization techniques (dropout, batch normalization and weight decay) take on the prediction quality.
