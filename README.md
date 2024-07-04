# Implementing a Neural Network from Scrath - Experimenting

This experiment is based on [this blog post](https://dennybritz.com/posts/wildml/implementing-a-neural-network-from-scratch/) and is a part of a report for a ML for NLP course at the University of Trento, CIMeC.

Experimenting with it, I managed to:
- implement a slightly bigger moon-shaped dataset;
- divide it into train and test splits;
- change the gradient descent for a minibatch gradient descent with `batch_size = 32`;
- implement an annealing schedule for the gradient descent learning rate, decreasing it each 2000 passages;
- experiment with other activation function;
- test each model's accuracy;
- plot all the results.

Moreover, most of the function have been slighly modified to integrate more modulability (e.g., using the specified activation function, loading the the training dataset...)
