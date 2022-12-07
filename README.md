# 273A-Final
This repository contains the final project of Annie Lu, Jack Mauro, and Tracy Yu for UCLA Mathematics Math 273A. 

The folder Shallow Network Tests performs an initial experiment on the results of batch normalization and weight normalization introduced in [1] and [2]. A network with 2 linear networks is used to perform classification on the MNIST dataset, and a 6 layer Convolutional Neural Network with 2 linear layers is used to perform classification on the CIFAR10 dataset. The CNN is modeled off of [2], but is modified slightly due to memory constraints. 

The folder Deep Network Tests extends the experiment to a deep network setting. The linear layer networks are extended to contain both 5 and 10 layers. The convolution blocks in the CNN are held constant, but the linear portion of the network is extended to contain both 5 and 10 layers. 

The folder Weight Initialization Methods experiments with how initializing weights differently impacts the two dynamic normalization procedures of weight and batch normalization. Four different intialization methods were used. One was the standard sampling from the default uniform distribution, one was sampling from the standard Gaussian distribution centered at 0 with standard deviation 1, one was sampling from the Xavier uniform distribution proposed in [3], and the final method was a Gaussian distribution centered at 0 with adjusted variance proposed in [4]. The same 5 layer networks from the folder Deep Network Tests were used to perform this experiment on both MNIST and CIFAR10.

The results of the experiments can be viewed in the attached final report.

Questions can be directed to jmauro at math dot ucla dot edu. 

[1] S. Ioffe and C. Szegedy, “Batch normalization: Accelerating deep network training by reducing internal
covariate shift,” CoRR, vol. abs/1502.03167, 2015.

[2] T. Salimans and D. P. Kingma, “Weight normalization: A simple reparameterization to accelerate training of deep neural networks,” CoRR, vol. abs/1602.07868, 2016.

[3] X. Glorot and Y. Bengio, “Understanding the difficulty of training deep feedforward neural networks,” in Proceedings of the Thirteenth International Conference on Artificial Intelligence and Statistics (Y. W. Teh and M. Titterington, eds.), vol. 9 of Proceedings of Machine Learning Research, (Chia Laguna Resort, Sardinia, Italy), pp. 249–256, PMLR, 13–15 May 2010.

[4] K. He, X. Zhang, S. Ren, and J. Sun, “Delving deep into rectifiers: Surpassing human-level performance on imagenet classification,” CoRR, vol. abs/1502.01852, 2015.
