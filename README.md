# Beam-Search-Decoder

Natural language processing tasks, such as caption generation and machine translation, involve generating sequences of words.

Models developed for these problems often operate by generating probability distributions across the vocabulary of output words and it is up to decoding algorithms to sample the probability distributions to generate the most likely sequences of words. It is then left to a decoder process to transform the probabilities into a final sequence of words.

The final layer in the neural network model has one neuron for each word in the output vocabulary and a softmax activation function is used to output a likelihood of each word in the vocabulary being the next word in the sequence.

### Greedy Search Decoder
