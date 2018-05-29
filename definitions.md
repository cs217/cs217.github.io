---
layout: default
---

<strong>Depth of a network
<p align="justify">
The number of layers in the network.
</p>

<strong>Feature vector / representation / volume</strong>

<img style="float: right; width: 400px; margin-left: 20px" src="/assets/img/depth.jpeg">

<p align="justify">
A three dimensional tensor of size
<a href="http://www.codecogs.com/eqnedit.php?latex=W&space;\times&space;H&space;\times&space;D" target="_blank"><img src="http://latex.codecogs.com/gif.latex?W&space;\times&space;H&space;\times&space;D" title="W \times H \times D" /></a>
obtained in a certain layer of a neural network.
W is the width, H is the height and D is the depth, i.e., the number of channels.
If there is more than one example, this becomes a four dimensional tensor of size
<a href="http://www.codecogs.com/eqnedit.php?latex=W&space;\times&space;H&space;\times&space;D&space;\times&space;B" target="_blank"><img src="http://latex.codecogs.com/gif.latex?W&space;\times&space;H&space;\times&space;D&space;\times&space;B" title="W \times H \times D \times B" /></a>
, where
<a href="http://www.codecogs.com/eqnedit.php?latex=B" target="_blank"><img src="http://latex.codecogs.com/gif.latex?B" title="B" /></a>
is the batch size.

<a href="http://cs231n.github.io/convolutional-networks/"> image source </a>
</p>

<strong>Spatial invariant feature vector</strong>
<p align="justify">
A feature vector that remains unchanged even if the input to the network is spatially translated.
</p>

<strong>Filters and biases</strong>
<p align="justify">
Filters are a four dimensional tensor of size

<a href="http://www.codecogs.com/eqnedit.php?latex=F&space;\times&space;F&space;\times&space;D&space;\times&space;K" target="_blank"><img src="http://latex.codecogs.com/gif.latex?F&space;\times&space;F&space;\times&space;D&space;\times&space;K" title="F \times F \times D \times K" /></a>

and biases are a vector of length

<a href="http://www.codecogs.com/eqnedit.php?latex=K" target="_blank"><img src="http://latex.codecogs.com/gif.latex?K" title="K" /></a>

.

<a href="http://www.codecogs.com/eqnedit.php?latex=F" target="_blank"><img src="http://latex.codecogs.com/gif.latex?F" title="F" /></a>

is the width and height of the filter,
 
<a href="http://www.codecogs.com/eqnedit.php?latex=D" target="_blank"><img src="http://latex.codecogs.com/gif.latex?D" title="D" /></a>

is the number of channels and 
 
<a href="http://www.codecogs.com/eqnedit.php?latex=K" target="_blank"><img src="http://latex.codecogs.com/gif.latex?K" title="K" /></a>

 is the number of filters.
</p>

<img style="width: 500px;" src="/assets/img/filters.png">
<br>
<a href="https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf"> image source </a>


<strong>Neighbourhood</strong>

<img style="float: right; width: 500px; margin-left: 20px" src="/assets/img/neighborhood.png">

<p align="justify">
A group of consecutive entries in a two-dimensional signal that has a rectangular or a square shape.

<a href="http://what-when-how.com/introduction-to-video-and-image-processing/neighborhood-processing-introduction-to-video-and-image-processing-part-1/"> image source </a>
</p>

[back](motifs)
