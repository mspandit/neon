# The Problem

Recognize handwritten digits.

# The Data

Uses the [MNIST](http://neon.nervanasys.com/docs/latest/datasets.html#mnist)
class to acquire 70,000 28X28 images in 10 categories---one for each digit.

# The Model

The model illustrates a branching topology, allowing the simultaneous exploration of multiple topologies sharing root layers.

# Local Training

`python mnist_branch.py`

# Nervana Cloud Training

`ncloud model train --framework-version v2.0.0 mnist_branch.py`
