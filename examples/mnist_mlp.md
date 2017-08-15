# The Problem

Recognize handwritten digits.

# The Data

Uses the [MNIST](http://neon.nervanasys.com/docs/latest/datasets.html#mnist)
class to acquire 70,000 28X28 images in 10 categories---one for each digit.

# The Model

The model consists of two affine layers.

# Local Training

`python mnist_mlp.py`

or 

`neon mnist_mlp.yaml -b cpu`

# Nervana Cloud Training

`ncloud model train mnist_mlp.py`

or

`ncloud model train mnist_mlp.yaml`