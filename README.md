# Deep Convolutional Generative Adversarial Networks

Generative Adversarial Networks (GANs) are one of the most interesting ideas in computer science today. Two models are trained simultaneously by an adversarial process. A generator ("the artist") learns to create images that look real, while a discriminator ("the art critic") learns to tell real images apart from fakes.

![Deep-convolutional-generative-adversarial-networks-DCGAN-for-generative-model-of-BF-NSP](https://github.com/Akhil-77/Deep_Convolutional_Generative_Adversarial_Network/assets/89073369/1b9882c8-2f75-493c-8eff-d3547a35dfb9)

During training, the generator progressively becomes better at creating images that look real, while the discriminator becomes better at telling them apart. The process reaches equilibrium when the discriminator can no longer distinguish real images from fakes.

![gan2](https://github.com/Akhil-77/Deep_Convolutional_Generative_Adversarial_Network/assets/89073369/b73b2c11-9047-4ebf-978e-44fb28c555be)

This notebook demonstrates this process on the CelebFaces Attributes (CelebA) Dataset available on Kaggle. The following animation shows a series of images produced by the generator as it was trained for 50 epochs. The images begin as random noise, and increasingly resemble human faces over time.


