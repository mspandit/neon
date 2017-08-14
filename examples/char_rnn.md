# The Problem

Train a character-level language model on Penn Treebank data, as described in _[Advances in Optimizing Recurrent Networks](https://arxiv.org/abs/1212.0901),_ by Yoshua Bengio, Nicolas Boulanger-Lewandowski, and Razvan Pascanu.

# The Data

Uses the [PTB](http://neon.nervanasys.com/docs/latest/datasets.html#text)
class to acquire large amounts of English text for training, validation, and
testing.

# The Model

This model is a character-level language model with a single recurrent layer of
tanh units.

# Local Training

`python char_rnn.py`

# Nervana Cloud Training

`ncloud model train char_rnn.py`
