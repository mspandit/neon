# The Problem

Recognize handwritten digits.

# The Data

Uses the [MNIST](http://neon.nervanasys.com/docs/latest/datasets.html#mnist)
class to acquire 70,000 28X28 images in 10 categories---one for each digit.

# The Model

The model consists of two affine layers. Demonstrates the use of the `MultiOptimizer` [class](http://neon.nervanasys.com/docs/latest/generated/neon.optimizers.optimizer.MultiOptimizer.html?highlight=multioptimizer) to employ a different optimizer for each layer.

# Local Training

`python multi_optimizer.py`

# Nervana Cloud Training

`ncloud model train multi_optimizer.py`
