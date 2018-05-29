---
layout: default
---

<strong><a href="http://www.jmlr.org/papers/volume15/srivastava14a/srivastava14a.pdf"> Dropout </a></strong>

<img style="float: right; width: 450px;" src="/assets/img/dropout.jpeg">

<p align="justify">
Accepts as input:
<ul style="list-style-type:circle">
	<li>feature vector of size
	
	<a href="http://www.codecogs.com/eqnedit.php?latex=H&space;\times&space;W&space;\times&space;D" target="_blank"><img src="http://latex.codecogs.com/gif.latex?H&space;\times&space;W&space;\times&space;D" title="H \times W \times D" /></a>
	
	</li>
	<li>probability 
	
	<a href="http://www.codecogs.com/eqnedit.php?latex=p" target="_blank"><img src="http://latex.codecogs.com/gif.latex?p" title="p" /></a>
	
	</li>
</ul>  
Outputs another feature vector of the same size.
At train time, every neuron in it is set to the value of the corresponding neuron in the input with probability 

<a href="http://www.codecogs.com/eqnedit.php?latex=p" target="_blank"><img src="http://latex.codecogs.com/gif.latex?p" title="p" /></a>

, and zero otherwise.
At test time, the output feature vector is equal to the input one scaled by

<a href="http://www.codecogs.com/eqnedit.php?latex=p" target="_blank"><img src="http://latex.codecogs.com/gif.latex?p" title="p" /></a>

.
</p>

<strong>Weight decay</strong>
<p align="justify">
Soft

<a href="http://www.codecogs.com/eqnedit.php?latex=L_2" target="_blank"><img src="http://latex.codecogs.com/gif.latex?L_2" title="L_2" /></a>

constraint on the parameters of the network.
This is done by decreasing every parameter in each iteration of SGD by its value times a small constant, corresponding to the strength of the regularization.
</p>

<strong>Max norm constraints</strong>
<p align="justify">
Hard

<a href="http://www.codecogs.com/eqnedit.php?latex=L_2" target="_blank"><img src="http://latex.codecogs.com/gif.latex?L_2" title="L_2" /></a>

constraint on the parameters of the network.
This is done by imposing an upper bound on the

<a href="http://www.codecogs.com/eqnedit.php?latex=L_2" target="_blank"><img src="http://latex.codecogs.com/gif.latex?L_2" title="L_2" /></a>

norm of every filter and using projected gradient descent to enforce the constraint.<br />
<a href="http://cs231n.github.io/convolutional-networks/"> source </a>
</p>

<strong>Data augmentation</strong>
<p align="justify">
Creating additional training samples by perturbing existing ones.
In image classification this includes randomly flipping the input, cropping subsets from it, etc.
</p>

[back](cheat_sheet)
