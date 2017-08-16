# Neon Examples

This directory contains the following examples of models implemented in Neon:

## Models on the MNIST Data Set

* [mnist-mlp](mnist_mlp.md), a multilayer perceptron for recognizing digits.
* [mnist-hdf5](mnist_hdf5.md), the above model trained using the HDF5 data iterator.
* [conv-autoencoder](conv_autoencoder.md), an autoencoder for MNIST images.
* [mnist-branch](mnist_branch.md), a multilayer perceptron with a branching topology.
* [mnist-merge](mnist_merge.md), a multilayer perceptron with a merging topology.

## Models on Text Data

* [char-lstm](char_lstm.md), an implementation of [Andrej Karpathy's
char-rnn](http://github.com/karpathy/char-rnn) on the Neon framework.
* [char-rae](char_rae.md), a recurrent autoencoder that outputs a text sequence in reverse order.
* [char-rnn](char_rnn.md), a character-level language model using a single tanh layer as described [here](https://arxiv.org/abs/1212.0901).

## Models on the CIFAR 10 Data Set

* [cifar10](cifar10.md), an image classification model consisting of two affine layers.
* [cifar10-conv](cifar10_conv.md), an image classification model consisting of a few convolutional layers alternating with pooling layers.
* [cifar10-allcnn](cifar10_allcnn.md), an image classification model consisting only of convolutional layers, as described [here](https://arxiv.org/abs/1412.6806).
