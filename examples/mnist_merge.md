# The Problem

Recognize handwritten digits.

# The Data

Uses the [MNIST](http://neon.nervanasys.com/docs/latest/datasets.html#mnist)
class to acquire 70,000 28X28 images in 10 categories---one for each digit.

# The Model

The model illustrates a merging topology, allowing the simultaneous exploration of multiple topologies sharing output layers.

# Local Training

`python mnist_merge.py`

# Nervana Cloud Training

`ncloud model train mnist_merge.py`
