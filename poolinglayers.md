---
layout: default
---

<strong>Pooling layer</strong>

<img style="float: right; width: 500px; margin:0px 20px" src="/assets/img/pooling.jpg">

<p align="justify">
Accepts as input:
<ul style="list-style-type:circle">
	<li>feature vector of size
	
	<a href="http://www.codecogs.com/eqnedit.php?latex=W_1&space;\times&space;H_1&space;\times&space;D_1" target="_blank"><img src="http://latex.codecogs.com/gif.latex?W_1&space;\times&space;H_1&space;\times&space;D_1" title="W_1 \times H_1 \times D_1" /></a>
	
	</li>
	<li>size of neighbourhood
	
	<a href="http://www.codecogs.com/eqnedit.php?latex=F" target="_blank"><img src="http://latex.codecogs.com/gif.latex?F" title="F" /></a>
	
	</li>
	<li>stride S</li>
</ul>  
Outputs another feature vector of size

<a href="http://www.codecogs.com/eqnedit.php?latex=W_2&space;\times&space;H_2&space;\times&space;D_1" target="_blank"><img src="http://latex.codecogs.com/gif.latex?W_2&space;\times&space;H_2&space;\times&space;D_1" title="W_2 \times H_2 \times D_1" /></a>

, where
Accepts as input:
<ul style="list-style-type:circle">
	<li>
	
	<a href="http://www.codecogs.com/eqnedit.php?latex=W_2&space;=&space;\frac{W_1&space;-&space;F}{S}&space;&plus;&space;1&plus;&space;1" target="_blank"><img src="http://latex.codecogs.com/gif.latex?W_2&space;=&space;\frac{W_1&space;-&space;F}{S}&space;&plus;&space;1" title="W_2 = \frac{W_1 - F}{S} + 1" /></a>
	
	</li>
	<li>
	
	<a href="http://www.codecogs.com/eqnedit.php?latex=H_2&space;=&space;\frac{H_1&space;-&space;F}{S}&space;&plus;&space;1" target="_blank"><img src="http://latex.codecogs.com/gif.latex?H_2&space;=&space;\frac{H_1&space;-&space;F}{S}&space;&plus;&space;1" title="H_2 = \frac{H_1 - F}{S} + 1" /></a>
	
	</li>
</ul>  
The pooling resizes independently every channel of the input feature vector by applying a certain function on neighbourhoods of size

<a href="http://www.codecogs.com/eqnedit.php?latex=F&space;\times&space;F" target="_blank"><img src="http://latex.codecogs.com/gif.latex?F&space;\times&space;F" title="F \times F" /></a>

, with a stride

<a href="http://www.codecogs.com/eqnedit.php?latex=S" target="_blank"><img src="http://latex.codecogs.com/gif.latex?S" title="S" /></a>

.<br />
<a href="http://cs231n.github.io/convolutional-networks/"> source </a>
<br>
<a href="https://www.embedded-vision.com/platinum-members/cadence/embedded-vision-training/documents/pages/neuralnetworksimagerecognition"> image source </a>
</p>

<strong>Max pooling</strong>
<p align="justify">
Picks the maximal value from every neighbourhood.
</p>

<strong>Average pooling</strong>
<p align="justify">
Computes the average of every neighbourhood.
</p>

[back](motifs)
