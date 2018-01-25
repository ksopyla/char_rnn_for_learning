# Char-RNN implementations for learning
The repository contains working and tested scripts with different RNN implementations. 

## Minimal character-level RNN by Andrej Karpathy [@karpathy](https://github.com/karpathy)
Minimal character-level Vanilla RNN model. 
https://gist.github.com/karpathy/d4dee566867f8291f086

License: BSD

Requirements: 
* numpy


Andrej blog post ["The Unreasonable Effectiveness of Recurrent Neural Networks"](http://karpathy.github.io/2015/05/21/rnn-effectiveness/) gives you introduction to this models

There is also youtube video, where he explains the implementation details
https://www.youtube.com/watch?v=iX5V1WpxxkY

### Vanilla Char-RNN using TensorFlow by Vinh Khuc [@vinhkhuc](https://github.com/vinhkhuc)

Adapted from Karpathy's min-char-rnn.py https://gist.github.com/vinhkhuc/7ec5bf797308279dc587

Concise and straightforward tensorflow implementation of Andrej char RNN. You will learn how to create necessary TF variables which stores all input to hidden and hidden to hidden matrices.

License: BSD

Requirements: 
* tensorflow>=1.0

## TensorFlow-Char-RNN by [@crazydonkey200](https://github.com/crazydonkey200)

A TensorFlow implementation of Andrej Karpathy's Char-RNN, a character level language model using multilayer Recurrent Neural Network (RNN, LSTM or GRU)

https://github.com/crazydonkey200/tensorflow-char-rnn
