<div class="abstract">   
    <strong>Convolutional Neural Networks in the View of Sparse Coding</strong>
    <p align="justify">
Convolutional sparse coding (CSC) has recently gained increasing attention in the signal and image processing communities. Although several works have presented algorithmic solutions to the global pursuit problem under this new model, very few truly effective guarantees are known for the success of such methods. In this talk, we present a thorough analysis of the CSC model and its associated pursuit, showing new and much stronger guarantees when compared to those of the classical sparse theory.

We then present a multi-layer extension of the CSC model, named ML-CSC, which is tightly connected to Convolutional Neural Networks (CNN). More concretely, we show that the forward pass of the CNN is identical to a pursuit associated with our proposed model. Leveraging this connection, we bring a fresh view to CNN with a deeper theoretical understanding. In particular, we show that the forward pass is guaranteed to recover an estimate of the underlying representations of an input signal, assuming these are sparse in a local sense. Moreover, we show that a mild corruption in the input signal does not change this property, indicating the stability of the CNN. Lastly, we exploit the answers to the above questions in order to propose an alternative to the forward pass algorithm, which is tightly connected to deconvolutional and recurrent networks.
</p>
</div>
[Readings for this lecture](readings#lecture-10)


![Vardan Papyan](/assets/img/VardanPapyan.png)  

[Vardan Papyan](http://vardanp.cswp.cs.technion.ac.il/) received the B.Sc. degree in 2013 from the Computer Science Department, Technion - Israel Institute of Technology, Haifa, Israel.
He later received the M.Sc. and Ph.D. degrees in the same department under the supervision of Prof. Michael Elad.
He is currently a postdoc student of Prof. David Donoho in the statistics department of Stanford.
His research interests include signal and image processing, sparsity-based modeling of signals, and in particular deep learning and its relation to sparsity.

[back](./)
