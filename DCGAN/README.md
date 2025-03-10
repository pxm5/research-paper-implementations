
## Brief Synopsis:

DCGANs, or Deep Convolutional Generational Adverserial Networks, are similar to the perceptron GANs, but instead of using perceptrons as the underlying models for the models, we use a CNN. The generator takes in random noise and generates an image through interpolation, and then those images, along with real images from the dataset, are sent into the discriminator that uses a traditional CNN to find which is which. These models produce better images, but are slow to train. (using batchnorm on every layer got me better training).

Research Paper for those who are interested: https://arxiv.org/pdf/1511.06434


