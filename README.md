# Generative Adversarial Networks (GAN)

<em>Generative modeling is an unsupervised learning task in machine learning that involves automatically discovering and learning the patterns in input data in such a way that the model can be used to generate or output new examples that plausibly could have been drawn from the original dataset.</em>

### A generative adversarial network (GAN) has two parts:

<ul>
<li>The generator learns to generate plausible data. The generated instances become negative training examples for the discriminator.</li>
<li>The discriminator learns to distinguish the generator's fake data from real data. The discriminator penalizes the generator for producing implausible results.</li>
</ul>

<img src="https://cdn.hashnode.com/res/hashnode/image/upload/v1673604003083/0b631935-aad5-497c-a73f-578cabeaf809.png?auto=compress,format&format=webp" alt="DCGAN">