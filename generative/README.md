# Tutorial on training generative models (VAEs and GANs)
by Mihaela Rosca 

_Designed for education purposes. Please do not distribute without permission_.

**Questions/Correspondence**: 2018tmlss@gmail.com

## VAE training tutorial
This is a tutorial training a [VAE](https://arxiv.org/abs/1312.6114) on MNIST and latent analysis

**Structure**:

* create encoder and decoder, choose latent and model distributions.
* VAE training
* check likelihood for overfitting.
* latent analysis

**Your tasks**:

* define the decoder distribution
* define the encoder distribution
* define the terms of the loss
* define the samples and reconstruction tensors
* run the KL analysis
* run the latent traversal task
* run the colab with a different number of latent dimensions (and see how that affects the kl analysis)

## GAN training tutorial
This is a tutorial training a [GAN](https://papers.nips.cc/paper/5423-generative-adversarial-nets.pdf) on MNIST and doing a latent traversal. We will focus on the original GAN, but there are other GANs out there (such as Wasserstein GAN).

**Structure**:

* basic GAN training
* latent traversal
* try bigger learning rate to see what happens
* optional: add gradient penalty

**Your tasks**:

* finish up generator definition
* define the discriminator loss
* define the generator loss
* define the discriminator and generator update operations
* run the latent traversal task
* change the learning rates of the discriminator / generator to see if you can get mode collapse
* change the training to do 5 discriminator updates for generator update
* (optional): implement gradient penalties
