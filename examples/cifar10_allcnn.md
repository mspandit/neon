# The Problem

Classify images with a model consisting solely of convolutional layers.

# The Data

Uses the [CIFAR10](http://neon.nervanasys.com/docs/latest/datasets.html#cifar10)
class to acquire 60,000 32X32 images in 10 categories.

# The Model

The model consists of convolutional layers with dropout and a single pooling
layer.

# Local Training

`python cifar10_allcnn.py`

# Nervana Cloud Training

`ncloud model train cifar10_allcnn.py`
