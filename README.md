# autoencoder-as-feature-extractor-CIFAR-10

I used 2 different autoencoder models ([U-net](https://arxiv.org/pdf/1505.04597.pdf) and Convolutional Autoencoder) to create features for using as input in classifier models to classify the images of [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) dataset. I used both stacked dense layer and dense layers after convolution layers as classifier models. I also used a simple convolution neural network to classify the dataset without any autoencoder as a baseline model.
