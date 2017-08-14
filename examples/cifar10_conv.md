# The Problem

Classify images with a simple model alternating convolutional and pooling
layers.

# The Data

Uses the [CIFAR10](http://neon.nervanasys.com/docs/latest/datasets.html#cifar10)
class to acquire 60,000 32X32 images in 10 categories.

# The Model

The model consists of a few convolutional layers alternating with pooling
layers.

# Local Training

`python cifar10_conv.py`

# Nervana Cloud Training

`ncloud model train cifar10_conv.py`
