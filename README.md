# 273A-Final
This repository contains the final project of Annie Lu, Jack Mauro and Tracy Yu for UCLA Mathematics Math 273A. 

The folder Shallow Networks performs an initial experiment on the results of batch normalization and weight normalization introduced in CITE. A network with 2 linear networks is used to perform classification on the MNIST dataset, and a 6 layer Convolutional Neural Network with 2 linear layers is used to perform classification on the CIFAR10 dataset. The CNN is modeled off of CITE, but is modified slightly due to memory constraints. 

The folder Deep Networks extends the experiment to a deep network setting. The linear layer networks are extended to contain both 5 and 10 layers. The convolution blocks in the CNN are held constant, but the linear portion of the network is extended to contain both 5 and 10 layers. 

The folder Weight Initializations experiments with how initializing weights differently impacts the two dynamic normalization procedures of weight and batch normalization. Four different intialization methods were used. One was the standard sampling from the uniform distribution between [-1,1], one was sampling from the standard Gaussian distribution centered at 0 with standard deviation 1, one was sampling from the Xavier uniform distribution proposed in CITE, and the final method was a Gaussian distribution centered at 0 with adjusted variance proposed in CITE.

The results of the experiments can be viewed in the attached final report.

Questions can be directed to jmauro at math dot ucla dot edu. 
