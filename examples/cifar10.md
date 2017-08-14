# The Problem

Classify images with a multi-layer perceptron.

# The Data

Uses the [CIFAR10](http://neon.nervanasys.com/docs/latest/datasets.html#cifar10)
class to acquire 60,000 32X32 images in 10 categories.

# The Model

The model consists of two affine layers.

# Local Training

`python cifar10.py`

# Nervana Cloud Training

`ncloud model train cifar10.py`
