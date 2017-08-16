# The Problem

Demonstrate use of HDF5 data iterator in recognition of handwritten digits.

# The Data

Uses the [MNIST](http://neon.nervanasys.com/docs/latest/datasets.html#mnist)
class to acquire 70,000 28X28 images in 10 categories---one for each digit.
Generates HDF5 files from these, for use during training.

# The Model

The model consists of two affine layers.

# Local Training

`python mnist_hdf5.py`

# Nervana Cloud Training

`ncloud model train mnist_hdf5.py`
