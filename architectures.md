---
layout: default
---

<strong>Convolutional neural network (CNN)</strong>

<img style="float: right; width: 550px;" src="/assets/img/lenet5.png">

<p align="justify">
A multi-layer neural network constructed from convolutional layers.
These apply a convolution operation to the input, passing the result to the next layer.
The weights in the convolutional layers are shared, which means that the same filter bank is used in all the spatial locations.<br />
<a href="https://en.wikipedia.org/wiki/Convolutional_neural_network"> source </a>
</p>

<strong>Deconvolutional networks</strong>

<img style="float: right; width: 550px;" src="/assets/img/conv_deconv.png">

<p align="justify">
A generative network that is a special kind of convolutional network that uses transpose convolutions, also known as a deconvolutional layers.

<br>

<a href="https://arxiv.org/pdf/1505.04366.pdf"> image source </a><br />

</p>

<strong><a href="https://arxiv.org/pdf/1406.2661.pdf"> Generative Adversarial Networks (GAN) </a></strong>
<p align="justify">

<img style="float: right; width: 250px;" src="/assets/img/gan2.png">

A system of two neural networks, introduced by Ian Goodfellow et al. in 2014, contesting with each other in a zero-sum game framework.
The first is a deconvolutional network, G, that generates signals.
While the second is a classifier, D, that learns to discriminates between signals from the true data distribution and fake ones produced by the generator.
The generative network's goal is to increase the error rate of the discriminative network by fooling it with synthesized examples that appear to have come from the true data distribution.<br />
<a href="https://en.wikipedia.org/wiki/Generative_adversarial_network"> source </a>
</p>

<img style="width: 600px;" src="/assets/img/gan1.png">

<strong>Recurrent neural networks (RNN)</strong>
<p align="justify">
RNNs are built on the same computational unit as the feed forward neural network, but differ in the way these are connected.
Feed forward neural networks are organized in layers, where information flows in one direction -- from input units to output units -- and no cycles are allowed.
RNNs, on the other hand, do not have to be organized in layers and directed cycles are allowed.
This allows them to have internal memory and as a result to process sequential data.
One can convert an RNN into a regular feed forward neural network by "unfolding" it in time, as depicted in the figures.
</p>

<img style="width: 550px;" src="/assets/img/rnn.png">

<br>

<a href="https://magenta.tensorflow.org/2016/06/10/recurrent-neural-network-generation-tutorial"> image source </a><br />

[back](cheat_sheet)
