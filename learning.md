---
layout: default
---

<strong>Gradient descent</strong>

<img style="float: right; width: 400px;" src="/assets/img/grad_descent.png">

<p align="justify">
To find a local minimum of a function using gradient descent, one takes steps proportional to the negative of the gradient of the function at the current point.<br />
<a href="https://en.wikipedia.org/wiki/Gradient_descent"> source </a>
<br>
<a href="https://github.com/rasbt/python-machine-learning-book"> image source </a>
</p>

<strong>Stochastic gradient descent (SGD)</strong>
<p align="justify">
A stochastic approximation of the gradient descent for minimizing an objective function that is a sum of functions.
The true gradient is approximated by the gradient of a randomly chosen single function.<br />
<a href="https://en.wikipedia.org/wiki/Stochastic_gradient_descent"> source </a>
</p>

<strong>Initialization of a network</strong>
<p align="justify">
Usually, the biases of a neural network are set to zero, while the weights are initialized with independent and identically distributed zero-mean Gaussian noise.
The variance of the noise is chosen in such a way that the magnitudes of input signals does not change drastically.<br />
<a href="https://arxiv.org/pdf/1502.01852.pdf"> source </a>
</p>

<strong>Learning rate</strong>
<p align="justify">
The scalar by which the negative of the gradient is multiplied in gradient descent.
</p>

<strong>Backpropagation</strong>

<img style="float: left; width: 350px;" src="/assets/img/backprop.png">

<p align="justify">
An algorithm, relying on an iterative application of the chain rule, for computing efficiently the derivative of a neural network with respect to all of its parameters and feature vectors.<br />
<a href="https://en.wikipedia.org/wiki/Backpropagation"> source </a>
<br>
<a href="https://www.researchgate.net/figure/241741756_fig2_Figure-2-Back-propagation-multilayer-ANN-with-one-hidden-layer"> image source </a>
</p>

<br>
<br>
<br>
<br>

<strong>Goal function</strong>
<p align="justify">
The function being minimized in an optimization process, such as SGD.
</p>

<strong>Data preprocessing</strong>

<p align="justify">
The input to a neural network is often mean subtracted, contrast normalized and whitened.
</p>

<img style="width: 700px;" src="/assets/img/preproc.png">
<br>
<a href="http://wangxinliu.com/machine%20learning/machine%20learning%20basic/NN3/"> image source </a>

<strong>One-hot vector</strong>

<img style="float: left; width: 200px; margin-right: 20px" src="/assets/img/onehotvec.png">

<p align="justify">
A vector containing one in a single entry and zero elsewhere.
<br>
<a href="https://blog.acolyer.org/2016/04/21/the-amazing-power-of-word-vectors/"> image source </a>
</p>

<br>
<br>

<strong>Cross entropy</strong>
<p align="justify">
Commonly used to quantify the difference between two probability distributions.
In the case of neural networks, one of the distributions is the output of the softmax, while the other is a one-hot vector corresponding to the correct class.
</p>

<strong>Added noise</strong>

<img style="float: right; width: 200px; margin:0px 20px" src="/assets/img/noisy.png">

<p align="justify">
A perturbation added to the input of the network or one of the feature vectors it computes.
<br>
<a href="https://people.sc.fsu.edu/~jburkardt/m_src/image_denoise/image_denoise.html"> image source </a>
</p>

[back](cheat_sheet)
