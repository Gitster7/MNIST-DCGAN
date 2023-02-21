# MNIST - Deep Convolutional GAN (DCGAN)
DCGAN, or Deep Convolutional GAN, is a generative adversarial network architecture that uses convolution layers (Discriminator) and transposed convolution layers (Generator). Batch Normalization is used in both, the Generator and Discriminator except for the final layer. ReLU activation is used in the generator for all layers except for the output layer, which uses Tanh activation. LeakyReLU activation is used in the discriminator for all layers.


## Generative Adversarial Networks (GAN)
<em>Generative modeling is an unsupervised learning task in machine learning that involves automatically discovering and learning the patterns in input data in such a way that the model can be used to generate or output new examples that plausibly could have been drawn from the original dataset.</em>

### A generative adversarial network (GAN) has two parts:

<ul>
<li>The generator learns to generate plausible data. The generated instances become negative training examples for the discriminator.</li>
<li>The discriminator learns to distinguish the generator's fake data from real data. The discriminator penalizes the generator for producing implausible results.</li>
</ul>

<img src="https://i0.wp.com/neptune.ai/wp-content/uploads/2022/10/fig3-Objective-function.png?ssl=1" alt="DCGAN">

## Results
<img src="https://github.com/Gitster7/MNIST-DCGAN/blob/main/DCGAN.png" style="background-color:white" alt="Results">

## Additional

To know more about the project visit my blog on DCGAN at: https://omkarvatsa.hashnode.dev/deep-convolutional-gan-dcgan
