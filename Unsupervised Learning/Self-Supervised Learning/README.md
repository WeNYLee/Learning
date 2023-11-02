A type of unsupervised learning

Self-supervised learning creates labels for the data.

Generative methods, 
Predictive methods,
Contrastive methods,
Booststrapping methods,
Simple extra regularization methods

Generative methods can generate data instances.

Contrastive self-supervised learning uses both positive samples and negative samples, while non-contrastive self-supervised learning uses positive samples only. Negative examples help prevent model collapse. Generally, the loss function of contrastive self-supervised learning is designed to minimize the distance between positive samples but maximize that between negative samples.


Include Generative Adversarial Networks (GANs)

GAN is a deep learning framework. The framework typically has a generator and a discriminator, where the generator learns to produce fake data, and the discriminator learns to tell if the data are fake or not. That is, the generative network generates candidates while the discriminative network evaluates them. [1]

Reference:
1. I. Goodfellow et al., "Generative Adversarial Nets," in Proc. of NIPS, 2014
