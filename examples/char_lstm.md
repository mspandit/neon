# The Problem

Implementation of [Andrej Karpathy's
char-rnn](http://github.com/karpathy/char-rnn) on the Neon framework.

# The Data

Uses the `[PTB](http://neon.nervanasys.com/docs/latest/datasets.html#text)`
class to acquire large amounts of English text for training, validation, and
testing.

# The Model

This code implements a two-layer network of LSTMs or GRUs, depending on
command-line parameters,

> for training/sampling from character-level language models. In other words, 
> the model takes one text file as input and trains a...network that learns to
> predict the next character in a sequence.
