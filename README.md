# Deep Mixture Generative Autoencoder
This is the implementation of the Deep Mixture Generative Autoencoder. This project also includes the implementation of InforVAEGAN (Please see more details in https://github.com/dtuzi123/InfoVAEGAN).

# Title:Deep Mixture Generative Autoencoder

# Paper link

https://pubmed.ncbi.nlm.nih.gov/33872161/

# Abstract

Variational autoencoders (VAEs) are powerful deep generative models which
can capture the variation of data. In this paper, we propose a Mixture of VAE
components model. Each component is implemented by a variational encoder
and its associated sub-decoder in order to learn a collection of separate latent
spaces that capture different aspects of data. This model enables the variational
framework to be extended to localised sections of the latent variable space. We
further introduce the d-variable Hilbert-Schmidt Independence Criterion (dHSIC)
to enforce the independence on encoder distributions for representation learning.
For the choice of number of VAE components, we use the dropout technology.
The dropout rate, which is learnable variable, controls the number of components
during the generation process. However, dropout masks are often sampled from
Bernoulli distribution and are non-differentiable. In order to deal with this issue,
we extend the Gumble-Softmax distribution to sample the smooth approximation
of Bernoulli variables. We perform a series of experiments to demonstrate that each
component in the mixture model can encode underlying factors and meaningful
information in different ways, which benefit down-stream tasks and generation.

# Environment

1. Tensorflow 1.5
2. Python 3.6

# Cite

Ye F, Bors AG. Deep Mixture Generative Autoencoders. IEEE Trans Neural Netw Learn Syst. 2021 Apr 19;PP. doi: 10.1109/TNNLS.2021.3071401. Epub ahead of print. PMID: 33872161.
