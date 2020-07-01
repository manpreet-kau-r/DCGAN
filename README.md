# DCGAN

### Generate Synthetic Images with DCGANs in Keras

Architecture for stable Deep Convolutional GANs:

-> Replace any pooling layers with strided convolutions(discriminator) and fractional-strinded convolutions(generator)

-> Use batchnorm in both generator and dicriminator

-> Remove fully connected hidden layers for deeper architectures

-> Use ReLU activation in generator for all layers except for output which uses tanh

-> Use LeakyReLU activation in discriminator for all layers except for output which uses sigmoid for binary classification
