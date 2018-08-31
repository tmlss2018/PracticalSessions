# RNN training tutorial
by Wojtek Czarnecki

## This is a tutorial training various RNNs on simple datasets and doing some analysis.

#### Structure:

1. basic (vanilla RNN) implementation
2. observing exploding/vanishing gradients
3. intepretability by plotting and analysing activations of a network:
   - identifying interpretable neurons
   - identifying neurons-gates interactions
   - identifying hidden state dynamics through time
4. training an LSTM on character level langugage modelling task
   - comparing training of an LSTM and RNN, playing with architectures
   
First three sections are almost independent, one can go switch between them without any code dependencies (apart from being unable to use vanilla RNN in section 4, if it was not implemented in 1.).

Cells that include "starting point" in their title require filling in some code gaps; all remaining ones are complete (but feel free to play with them if you want!)

Please pay attention to questions after each section. Finding out answers to these is crucial to make sure one understands various modes of RNN operation.

Language model exercises are based on [Sonnet LSTM example](https://github.com/deepmind/sonnet/blob/master/sonnet/examples/rnn_shakespeare.py).
