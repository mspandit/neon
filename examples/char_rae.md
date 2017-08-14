# The Problem

Given a text sequence, learn to output the same sequence in reverse order.

# The Data

Uses the [PTB](http://neon.nervanasys.com/docs/latest/datasets.html#text)
class to acquire large amounts of English text for training, validation, and
testing.

# The Model

This model shows how to use the Seq2Seq container class to build an
encoder-decoder recurrent neural network.

The encoder and decoder consist of GRU layers.

# Local Training

`python char_rae.py`

# Nervana Cloud Training

`ncloud model train char_rae.py`
