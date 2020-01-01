# Deep-Neural-Networks
Using Deep Neural Networks to solve problems of MNIST Classification (hand written digit classification) and Speech Denoising

Notebook **MNIST-Classification.ipynb** contains code which is used for training a fully-connected Neural Network using **tensorflow** on MNIST training data and then predict on test data. In this notebook, we also look at output from various layers to understand how neural networks construct different fetures for different classes, we also use PCA and t-SNE to visualize the features at different layers for different classes.

Notebook **Speech-Denoising.ipynb** contains code which is used to train a fully-connected Neural Network using **tensorflow** to remove noise from an audio signal. We train the neural network by giving speech with noise (train_dirty_male.wav) and clean speech (train_clean_male.wav) as input and output. We then test by giving a new signal with noise(test_x_01.wav) and generate clean output(test_s_01_recons.wav). We use Signal-to-noise ratio to measure the performance of the neural network.

