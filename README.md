# Bio-Networks

The current horse-power of deep-learning is backpropagation, a computational technique where the unique goal is to change the weights of a network in order to minimize the defined loss function. 
However neuroscientists often claim that neural cortex can't do backpropagation and in particular they state that it's biological implausible. The main problem behind is that it's an algorithm described by a non-local mathematics, while the synapse-change procedure is physically local.

In the paper "Unsupervised learning by competing hidden units" by D.Krotov and J.J. Hopfield, they are proposing an engineered plasticity rule and creating a local training procedure that is able to achieve great results in a standard classification task using the MNIST dataset. 

The project consists in implementing the naive version of the algorithm proposed in the paper, look at the pros and cons of this method and explain why this work can be considered a step toward explainable deep-learning.
