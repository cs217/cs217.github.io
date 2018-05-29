---
layout: default
---

<strong>Convolutional (Conv) layer</strong>

<img style="float: right; width: 300px; margin:0px 20px" src="/assets/img/conv.jpeg">

<p align="justify">
Accepts as input:<br />
<ul style="list-style-type:circle">
	<li>feature vector of size
	
	<a href="http://www.codecogs.com/eqnedit.php?latex=W_1&space;\times&space;H_1&space;\times&space;D_1" target="_blank"><img src="http://latex.codecogs.com/gif.latex?W_1&space;\times&space;H_1&space;\times&space;D_1" title="W_1 \times H_1 \times D_1" /></a>
	
	</li>
	<li>filters of size 
	
	<a href="http://www.codecogs.com/eqnedit.php?latex=F&space;\times&space;F&space;\times&space;D_1&space;\times&space;D_2" target="_blank"><img src="http://latex.codecogs.com/gif.latex?F&space;\times&space;F&space;\times&space;D_1&space;\times&space;D_2" title="F \times F \times D_1 \times D_2" /></a>
	
	</li>
	<li>biases of length 
	
	<a href="http://www.codecogs.com/eqnedit.php?latex=D_2" target="_blank"><img src="http://latex.codecogs.com/gif.latex?D_2" title="D_2" /></a>
	
	</li>
	<li>stride 
	
	<a href="http://www.codecogs.com/eqnedit.php?latex=S" target="_blank"><img src="http://latex.codecogs.com/gif.latex?S" title="S" /></a>
	
	</li>
	<li>amount of zero padding 
	
	<a href="http://www.codecogs.com/eqnedit.php?latex=P" target="_blank"><img src="http://latex.codecogs.com/gif.latex?P" title="P" /></a>
	
	</li>
</ul>  
Outputs another feature vector of size 

<a href="http://www.codecogs.com/eqnedit.php?latex=W_2&space;\times&space;H_2&space;\times&space;D_2" target="_blank"><img src="http://latex.codecogs.com/gif.latex?W_2&space;\times&space;H_2&space;\times&space;D_2" title="W_2 \times H_2 \times D_2" /></a>

, where
<ul style="list-style-type:circle">
	<li>
	
	<a href="http://www.codecogs.com/eqnedit.php?latex=W_2&space;=&space;\frac{W_1-F&plus;2P}{S}&plus;1" target="_blank"><img src="http://latex.codecogs.com/gif.latex?W_2&space;=&space;\frac{W_1-F&plus;2P}{S}&plus;1" title="W_2 = \frac{W_1-F+2P}{S}+1" /></a>
	
	</li>
	<li>
	
	<a href="http://www.codecogs.com/eqnedit.php?latex=H_2&space;=&space;\frac{H_1-F&plus;2P}{S}&plus;1" target="_blank"><img src="http://latex.codecogs.com/gif.latex?H_2&space;=&space;\frac{H_1-F&plus;2P}{S}&plus;1" title="H_2 = \frac{H_1-F+2P}{S}+1" /></a>
	
	</li>
</ul>  
The d-th channel in the output feature vector is obtained by performing a valid convolution with stride

<a href="http://www.codecogs.com/eqnedit.php?latex=S" target="_blank"><img src="http://latex.codecogs.com/gif.latex?S" title="S" /></a>

of the d-th filter and the padded input.<br />
<a href="http://cs231n.github.io/convolutional-networks/"> source </a>
</p>

<strong>Stride</strong>

<img style="float: right; width: 500px; margin:0px 20px" src="/assets/img/stride.png">

<p align="justify">
The amount by which a filter shifts spatially when convolving it with a feature vector.<br />
<a href="http://cs231n.github.io/convolutional-networks/"> source </a>
<br>
<a href="https://adeshpande3.github.io/A-Beginner%27s-Guide-To-Understanding-Convolutional-Neural-Networks-Part-2/"> image source </a>
</p>

<br>

<strong>Dilation</strong>

<img style="float: right; width: 500px; margin:0px 20px" src="/assets/img/dilation.png">

<p align="justify">
A filter is dilated by a factor

<a href="http://www.codecogs.com/eqnedit.php?latex=Q" target="_blank"><img src="http://latex.codecogs.com/gif.latex?Q" title="Q" /></a>

by inserting in every one of its channels independently

<a href="http://www.codecogs.com/eqnedit.php?latex=Q-1" target="_blank"><img src="http://latex.codecogs.com/gif.latex?Q-1" title="Q-1" /></a>

zeros between the filter elements.<br />
<a href="http://cs231n.github.io/convolutional-networks/"> source </a>
<br>
<a href="https://www.quora.com/What-is-the-difference-between-dilated-convolution-and-convolution+stride"> image source </a>
</p>

<strong>Fully connected (FC) layer</strong>

<img style="float: right; width: 200px; margin:0px 20px" src="/assets/img/fc.png">

<p align="justify">
In practice, FC layers are implemented using a convolutional layer.
To see how this might be possible, note that when an input feature vector of size 

<a href="http://www.codecogs.com/eqnedit.php?latex=H&space;\times&space;W&space;\times&space;D_1" target="_blank"><img src="http://latex.codecogs.com/gif.latex?H&space;\times&space;W&space;\times&space;D_1" title="H \times W \times D_1" /></a>

is convolved with a filter bank of size

<a href="http://www.codecogs.com/eqnedit.php?latex=H&space;\times&space;W&space;\times&space;D_1&space;\times&space;D_2" target="_blank"><img src="http://latex.codecogs.com/gif.latex?H&space;\times&space;W&space;\times&space;D_1&space;\times&space;D_2" title="H \times W \times D_1 \times D_2" /></a>

, it results in an output feature vector of size

<a href="http://www.codecogs.com/eqnedit.php?latex=1&space;\times&space;1&space;\times&space;D_2" target="_blank"><img src="http://latex.codecogs.com/gif.latex?1&space;\times&space;1&space;\times&space;D_2" title="1 \times 1 \times D_2" /></a>

.
Since the convolution is valid and the filter can not move spatially, the operation is equivalent to a fully connected one.
More over, when this feature vector of size 1x1xD_2 is convolved with another filter bank of size 

<a href="http://www.codecogs.com/eqnedit.php?latex=1&space;\times&space;1&space;\times&space;D_2&space;\times&space;D_3" target="_blank"><img src="http://latex.codecogs.com/gif.latex?1&space;\times&space;1&space;\times&space;D_2&space;\times&space;D_3" title="1 \times 1 \times D_2 \times D_3" /></a>

, the result is of size

<a href="http://www.codecogs.com/eqnedit.php?latex=1&space;\times&space;1&space;\times&space;D_3" target="_blank"><img src="http://latex.codecogs.com/gif.latex?1&space;\times&space;1&space;\times&space;D_3" title="1 \times 1 \times D_3" /></a>

.
In this case, again, the convolution is done over a single spatial location and therefore equivalent to a fully connected layer.<br />
<a href="http://cs231n.github.io/convolutional-networks/"> source </a>
<br>
<a href="https://www.quora.com/What-is-the-difference-between-dilated-convolution-and-convolution+stride"> image source </a>
</p>

<strong>Linear classifier</strong>

<img style="float: left; width: 400px; margin-right:0px 30px" src="/assets/img/linearclassifier.jpeg">

<p align="justify">
This is implemented in practice by employing a fully connected layer of size

<a href="http://www.codecogs.com/eqnedit.php?latex=H&space;\times&space;W&space;\times&space;D&space;\times&space;C" target="_blank"><img src="http://latex.codecogs.com/gif.latex?H&space;\times&space;W&space;\times&space;D&space;\times&space;C" title="H \times W \times D \times C" /></a>

, where 

<a href="http://www.codecogs.com/eqnedit.php?latex=C" target="_blank"><img src="http://latex.codecogs.com/gif.latex?C" title="C" /></a>

is the number of classes.
Each one of the filters of size 

<a href="http://www.codecogs.com/eqnedit.php?latex=H&space;\times&space;W&space;\times&space;D" target="_blank"><img src="http://latex.codecogs.com/gif.latex?H&space;\times&space;W&space;\times&space;D" title="H \times W \times D" /></a>

corresponds to a certain class and there are 

<a href="http://www.codecogs.com/eqnedit.php?latex=C" target="_blank"><img src="http://latex.codecogs.com/gif.latex?C" title="C" /></a>

classifiers, one for each class.
<br>
<a href="http://cs231n.github.io/linear-classify/"> image source </a>
</p>

[back](motifs)
