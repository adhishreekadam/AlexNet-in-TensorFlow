# AlexNet-in-TensorFlow
Reproduction of the AlexNet convolutional neural network architecture TensorFlow 2.x and Keras API to ensure compatibility with GPU acceleration and modern training utilities. The model was trained on CIFAR-10, CIFAR-100, and ImageNet-21k datasets, then tested on the ObjectNet test set.

## About AlexNet
The winner of the 2012 ImageNet Large Scale Visual Recognition Challenge (ILSVRC) was AlexNet, developed by Alex Krizhevsky, Ilya Sutskever and Geoffrey Hinton. AlexNet’s architecture is depicted in Figure 1. It consists of five convolution layers, three max pooling layers, two normalized layers, two fully connected layers, and one softmax layer. Each convolution layer consisted of a convolution filter and the "ReLU" activation filter. Another key feature of AlexNet is its use of overlapping pooling. Overlapping pooling is almost identical to standard pooling, but, as the pooling window moves across the layer before, it overlaps with the previous window. After winning the ILSVRC, its success revealed that CNNs can greatly outperform other machine learning algorithms for classifying large datasets.

