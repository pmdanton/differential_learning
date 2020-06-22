# Differential Learning
This notebook implements the paper [*Differential Machine Learning*](https://arxiv.org/abs/2005.02347) by Brian Huge and Antoine Savine. The authors already provide notebooks [on their github page](https://github.com/differential-machine-learning) but using TensorFlow 1 code, and low-level manual implementation, in particular the explicit backpropagation in twin networks. Here we aim to:
1. Reproduce the results with high-level APIs like Keras, in Tensorflow 2
2. Replace the explicit backpropagation in twin networks with TensorFlow's built-in AAD (GradientTape)
