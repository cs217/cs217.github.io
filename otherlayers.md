---
layout: default
---

<strong>Batch normalization</strong>
<p align="justify">
Accepts as input:
<ul style="list-style-type:circle">
	<li>feature vector of size
	
	<a href="http://www.codecogs.com/eqnedit.php?latex=W&space;\times&space;H&space;\times&space;D" target="_blank"><img src="http://latex.codecogs.com/gif.latex?W&space;\times&space;H&space;\times&space;D" title="W \times H \times D" /></a>
	
	</li>
	<li>bias vector of size
	
	<a href="http://www.codecogs.com/eqnedit.php?latex=D" target="_blank"><img src="http://latex.codecogs.com/gif.latex?D" title="D" /></a>
	
	</li>
	<li>gain vector of size
	
	<a href="http://www.codecogs.com/eqnedit.php?latex=D" target="_blank"><img src="http://latex.codecogs.com/gif.latex?D" title="D" /></a>
	
	</li>
</ul>  
Outputs another feature vector of the same size.
This layer operates on each channel of the feature vector independently.
First, each channel is normalized to have a zero mean, unit variance and then it is multiplied by a gain and shifted by a bias.
The purpose of this layer is to ease the optimization process.
</p>

<strong>Softmax layer</strong>
<p align="justify">
Takes the output of the classifier, applies exponent on the score assigned to each class and then normalizes the result to unit sum.
The result can be interpreted as a vector of probabilities for the different classes.
</p>

[back](motifs)
