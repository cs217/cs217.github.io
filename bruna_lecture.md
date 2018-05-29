<div class="abstract">   
<strong>High-dimensional Energy Landscapes</strong>
    <p align="justify">
The loss surface of deep neural networks has recently attracted interest in the optimization and machine learning communities as a prime example of high-dimensional non-convex problem. Some insights were recently gained using spin glass models and mean-field approximations, but at the expense of simplifying the nonlinear nature of the model, as well as tensor decompositions. 

In this lecture, we will review these approaches and describe in detail our recent work that focuses on topological and geometrical properties of such energy landscapes. We will study conditions on the data distribution and model architecture that prevent the existence of bad local minima. We first take a topological approach and characterize absence of bad local minima by studying the connectedness of the loss surface level sets. Our theoretical work quantifies and formalizes two important facts: (i) the landscape of deep linear networks has a radically different topology from that of deep half-rectified ones, and (ii) that the energy landscape in the non-linear case is fundamentally controlled by the interplay between the smoothness of the data distribution and model over-parametrization. Our main theoretical contribution is to prove that half-rectified single layer networks are asymptotically connected, and we provide explicit bounds that reveal the aforementioned interplay. 

The conditioning of gradient descent is the next challenge we address. We study this question through the geometry of the level sets, and we introduce an algorithm to efficiently estimate the regularity of such sets on large-scale networks. Our empirical results show that these level sets remain connected throughout all the learning phase, suggesting a near convex behavior, but they become exponentially more curvy as the energy level decays, in accordance to what is observed in practice with very low curvature attractors. Joint work with Daniel Freeman (UC Berkeley), Luca Venturi and Afonso Bandeira (Courant, NYU).
</p>
</div>
[Readings for this lecture](readings#lecture-8)


![Joan Bruna](/assets/img/bruna.png)  

[Joan Bruna](http://cims.nyu.edu/~bruna/) is an assistant professor at Courant Institute, NYU, in the Department of Computer Science, Department of Mathematics (affiliated) and the Center for Data Science. Prior to this, he worked at FAIR (Facebook AI Research) in New York, conducting research on Unsupervised Learning. Joan did his PhD at Ecole Polytechnique, France, where he collaborated with Stephane Mallat.
   
Bruna's research interests touch several areas of Machine Learning, Signal Processing and High-Dimensional Statistics. In particular, in the past few years, he has been working on Deep Convolutional Networks, studying some of its theoretical properties and applications to several Computer Vision tasks.

[back](./)
