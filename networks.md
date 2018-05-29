---
layout: default
---

<strong><a href="http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.569.5982&rep=rep1&type=pdf"> Neocognitron </a></strong>

<img style="float: left; width: 350px;" src="/assets/img/neocognitron_fuk_1980.png">

<p align="justify">
A hierarchical multi-layered neural network, proposed by Kunihiko Fukushima in 1982.
It has been used for handwritten character recognition and other pattern recognition tasks.
Since backpropagation had not yet been applied for training neural nets at the time, it was limited by the lack of a training algorithm.<br />
<a href="https://ml4a.github.io/ml4a/convnets/"> source </a>
</p>

<br>

<strong><a href="http://yann.lecun.com/exdb/publis/pdf/lecun-01a.pdf"> LeNet-5 </a></strong>

<img style="float: right; width: 550px;" src="/assets/img/lenet5.png">

<p align="justify">
A pioneering digit classification neural network by LeCun et. al.
It was applied by several banks to recognise hand-written numbers on checks.
The network was composed of three types layers: convolution, pooling and non-linearity, and was trained using the backpropagation algorithm.<br />
<a href="https://en.wikipedia.org/wiki/Convolutional_neural_network"> source </a><br />
</p>

[![LeNet demo from 1993](https://img.youtube.com/vi/FwFduRA_L6Q/default.jpg)](https://www.youtube.com/watch?v=FwFduRA_L6Q "LeNet")

<strong><a href="https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf"> AlexNet </a></strong>
<p align="justify">

<img style="float: right; width: 500px;" src="/assets/img/alexnet.png">

A convolutional neural network, which competed in the ImageNet Large Scale Visual Recognition Challenge in 2012 and achieved a top-5 error of 15.3%, more than 10.8% ahead of the runner up.
AlexNet was designed by Alex Krizhevsky, Geoffrey Hinton, and Ilya Sutskever.
The network consisted of five convolutional layers, some of which were followed by max-pooling layers, and three fully-connected layers with a final 1000-way softmax.
All the convolutional and fully connected layers were followed by the ReLU nonlinearity.<br />
<a href="https://en.wikipedia.org/wiki/AlexNet"> source </a>
</p>

<strong><a href="https://arxiv.org/pdf/1409.1556.pdf"> VGGNet </a></strong>

<img style="float: right; width: 350px;" src="/assets/img/imagenet_vgg16.png">

<p align="justify">
A 19 layer convolutional neural network from VGG group, Oxford, that was simpler and deeper than AlexNet.
All large-sized filters in AlexNet were replaced by cascades of 3x3 filters (with nonlinearity in between).
Max pooling was placed after two or three convolutions and after each pooling the number of filters was always doubled.
<a href="https://www.cs.toronto.edu/~frossard/post/vgg16/"> source </a>
</p>

<strong><a href="https://arxiv.org/pdf/1512.03385.pdf"> ResNet </a></strong>

<img style="float: left; width: 300px;" src="/assets/img/resnet.png">

<p align="justify">
Developed by Microsoft Research, ResNet won first place in ILSVRC 2015 image classification using a 152-layer network -- 8 times deeper than the VGG.
The basic element in this architecture is the residual block, which	contains two paths between the input and the output, one of them being direct.
This forces the network to learn the features on top of already available input, and facilitates the optimization process.
</p>

[back](cheat_sheet)
