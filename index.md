---
layout: titlepage
---

This class meets TBA at [Gates TBD](https://campus-map.stanford.edu/?srch=Gates).

## Teaching Assistant

<div class="speaker-wrap">
<div class="speakerphoto">
<img src="assets/img/Stefan_Hadjis.png">
</div>
<div class="card">
<a class="talkdate" href="https://cs.stanford.edu/people/shadjis/">Stefan Hadjis</a> <br>
<span class="speaker">Office Hours TBA</span> <br>
</div>
</div>

## Schedule

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg .tg-cpu2{border-color:#000000;vertical-align:top}
.tg .tg-us36{border-color:inherit;vertical-align:top}
.tg .tg-7btt{font-weight:bold;border-color:inherit;text-align:center;vertical-align:top}
</style>
<table class="tg">
  <tr>
    <th class="tg-7btt">Lecture</th>
    <th class="tg-7btt">Topic</th>
    <th class="tg-7btt">Reading</th>
  </tr>
  <tr>
    <td class="tg-us36">1</td>
    <td class="tg-us36">Introduction, role of hardware accelerators in post Dennard<br>&nbsp;&nbsp;and Moore era</td>
    <td class="tg-us36"><a href="https://ieeexplore.ieee.org/document/6241647/">Is Dark silicon useful?</a><br>Hennessy Patterson Chapter 7.1-7.2</td>
  </tr>
  <tr>
    <td class="tg-us36">2</td>
    <td class="tg-us36">Classical ML algorithms: Regression, SVMs (What is the<br>&nbsp;&nbsp;building block?)</td>
    <td class="tg-us36"><a href="https://www.cc.gatech.edu/~hadi/doc/paper/2015-tr-tabla.pdf">TABLA</a></td>
  </tr>
  <tr>
    <td class="tg-us36">3</td>
    <td class="tg-us36">Linear algebra fundamentals and accelerating linear algebra<br>BLAS operations<br>20th century techniques: Systolic arrays and MIMDs, CGRAs</td>
    <td class="tg-us36"><a href="http://www.eecs.harvard.edu/~htk/publication/1982-kung-why-systolic-architecture.pdf">Why Systolic Architectures?</a><br><a href="https://www.cs.utexas.edu/users/pingali/CS378/2008sp/papers/gotoPaper.pdf">Anatomy of high performance GEMM</a></td>
  </tr>
  <tr>
    <td class="tg-us36">4</td>
    <td class="tg-us36">Evaluating Performance, Energy efficiency, Parallelism, Locality,<br>  Memory hierarchy, Roofline model </td>
    <td class="tg-us36"><a href="https://arxiv.org/abs/1602.04183">Dark Memory</a></td>
  </tr>
  <tr>
    <td class="tg-us36">5</td>
    <td class="tg-us36">Real-World Architectures: Putting it into practice<br>Accelerating GEMM:<br>Custom, GPU,  TPU1 architectures and their GEMM performance</td>
    <td class="tg-us36"><a href="https://arxiv.org/pdf/1704.04760.pdf">Google TPU</a><br><a href="https://ieeexplore.ieee.org/document/6212466/">Codesign Tradeoffs</a><br><a href="http://images.nvidia.com/content/volta-architecture/pdf/volta-architecture-whitepaper.pdf">NVIDIA Tesla V100</a></td>
  </tr>
  <tr>
    <td class="tg-us36">6</td>
    <td class="tg-us36">Neural networks: MLPs and CNNs Inference</td>
    <td class="tg-us36"><span style="color:rgb(254, 0, 0)">Viviense IEEE proceeding</span><br><span style="color:rgb(254, 0, 0)">Brooks’s book (Selected Chapters)</span></td>
  </tr>
  <tr>
    <td class="tg-us36">7</td>
    <td class="tg-us36"><span style="font-weight:bold">(2 Lectures) </span>Accelerating Inference for CNNs:<br>    Blocking and Parallelism in practice<br>    DianNao, Eyeriss, TPU1<br></td>
    <td class="tg-us36"><a href="https://arxiv.org/abs/1606.04209">Systematic Approach to Blocking</a><br><a href="https://people.csail.mit.edu/emer/papers/2016.06.isca.eyeriss_architecture.pdf">Eyeriss</a><br>Google TPU (see lecture 5)</td>
  </tr>
  <tr>
    <td class="tg-us36">8</td>
    <td class="tg-us36">Modeling neural networks with Spatial, Analyzing <br>  performance and energy with Spatial</td>
    <td class="tg-us36">Spatial<br><span style="color:rgb(254, 0, 0)">One related work</span></td>
  </tr>
  <tr>
    <td class="tg-us36">9</td>
    <td class="tg-us36">Resilience of DNNs: Sparsity and Low Precision Networks</td>
    <td class="tg-us36"><span style="color:rgb(254, 0, 0)">Some theory paper</span><br><a href="https://arxiv.org/pdf/1602.01528.pdf">EIE</a><br><a href="https://arxiv.org/pdf/1711.02213.pdf">Flexpoint of Nervana</a><br>Boris Ginsburg: <a href="https://arxiv.org/abs/1708.03888">paper</a>, <a href="http://on-demand.gputechconf.com/gtc/2017/presentation/s7218-training-with-mixed-precision-boris-ginsburg.pdf">presentation</a><br><span style="color:rgb(254, 0, 0)">LSTM Block Compression by Baidu?</span></td>
  </tr>
  <tr>
    <td class="tg-us36">10</td>
    <td class="tg-us36">Training: SGD, back propagation, statistical efficiency, batch size</td>
    <td class="tg-us36"><span style="color:rgb(254, 0, 0)">Nips workshop last year</span><br><a href="https://supercomputersfordl2017.github.io/Presentations/SimonKnowlesGraphCore.pdf">Graphcore</a></td>
  </tr>
  <tr>
    <td class="tg-us36">11</td>
    <td class="tg-us36">Low precision training</td>
    <td class="tg-us36"><a href="https://arxiv.org/abs/1803.03383">HALP</a><br><span style="color:rgb(254, 0, 0)">Ternary or binary networks</span><br>See Boris Ginsburg's work (lecture 9)</td>
  </tr>
  <tr>
    <td class="tg-us36">12</td>
    <td class="tg-us36">Training in Distributed and Parallel systems:  <br>Hogwild!, asynchrony and hardware efficiency</td>
    <td class="tg-us36"><a href="https://arxiv.org/abs/1712.01887">Deep Gradient compression</a><br><a href="https://people.eecs.berkeley.edu/~brecht/papers/hogwildTR.pdf">Hogwild!</a><br><a href="https://static.googleusercontent.com/media/research.google.com/en//archive/large_deep_networks_nips2012.pdf">Large Scale Distributed Deep Networks</a><br><span style="color:rgb(254, 0, 0)">Obstinate cache?</span></td>
  </tr>
  <tr>
    <td class="tg-cpu2">13</td>
    <td class="tg-cpu2">FPGAs and CGRAs: Catapult, Brainwave, Plasticine</td>
    <td class="tg-cpu2"><a href="https://www.microsoft.com/en-us/research/wp-content/uploads/2016/10/Cloud-Scale-Acceleration-Architecture.pdf">Catapult</a><br><a href="https://www.microsoft.com/en-us/research/uploads/prod/2018/03/mi0218_Chung-2018Mar25.pdf">Brainwave</a><br><a href="http://dawn.cs.stanford.edu/pubs/plasticine-isca2017.pdf">Plasticine</a></td>
  </tr>
  <tr>
    <td class="tg-cpu2">14</td>
    <td class="tg-cpu2">ML benchmarks: DAWNbench, MLPerf</td>
    <td class="tg-cpu2"><a href="https://cs.stanford.edu/~matei/papers/2017/nips_sysml_dawnbench.pdf">DawnBench</a><br><span style="color:rgb(254, 0, 0)">Some other benchmark paper</span></td>
  </tr>
  <tr>
    <td class="tg-cpu2">15</td>
    <td class="tg-cpu2">Project presentations</td>
    <td class="tg-cpu2"></td>
  </tr>
</table>


## [](#Lectures) Guest Lectures

<div class="speaker-wrap">
<div class="speakerphoto">
<img src="assets/img/Boris_Ginsburg-200x200.jpg">
</div>
<div class="card">
<a class="talkdate" href="./ginsburg_lecture">Boris Ginsburg, NVIDIA</a> <br>
<span class="speaker">Low Precision Training of DNNs</span> <br>
<span class="speakerposition">Date TBA</span>
</div>
</div>

---
<div class="speaker-wrap">
<div class="speakerphoto">
<img src="assets/img/Robert_Schreiber.jpeg">
</div>
<div class="card">
<a class="talkdate" href="./schreiber_lecture">Robert Schreiber, Cerebras Systems</a> <br>
<span class="speaker">Understanding Numerical Errors</span> <br>
<span class="speakerposition">Date TBA</span>
</div>
</div>

---
<div class="speaker-wrap">
<div class="speakerphoto">
<img src="assets/img/Mikhail_Smelyanskiy.JPG">
</div>
<div class="card">
<a class="talkdate" href="./smelyanskiy_lecture">Mikhail Smelyanskiy, Facebook</a> <br>
<span class="speaker">AI at Facebook Datacenter Scale</span> <br>
<span class="speakerposition">Date TBA</span>
</div>
</div>

## Related Stanford Courses
- [CS230](http://cs230.stanford.edu/syllabus.html)
- [CS231n](http://cs231n.github.io)
- [STATS 385](https://stats385.github.io/)

## [Reading list and other resources](readings)

## [Lecture slides](lecture_slides)    

## [Basic information about deep learning](basicinfo)    

## [Cheat sheet -- things that everyone needs to know](cheat_sheet)    

## [Blogs](blogs)

## [Grading](grading)


<!--
 If you are a guest speaker for this course, please read [travel section](#plan-your-visit) to plan your visit.   

* [Follow Stat385 on Twitter](https://twitter.com/stats385?lang=en)  

* [Follow Stat385 on ResearchGate (videos)](https://www.researchgate.net/project/Theories-of-Deep-Learning)  

## Deep Learning/AI News
 * [This Is The Future Of Artificial Intelligence](http://amp.timeinc.net/fortune/2016/06/15/future-of-work-2)


## [](#Lectures) Guest Lectures

---
<div class="speaker-wrap">
<div class="speakerphoto">
<img src="assets/img/bolcskei.jpg">
</div>
<div class="card">
<a class="talkdate" href="./bolcskei_lecture">Wednesday, 10/11/17</a> <br>
<span class="speaker">Helmut Bolcskei</span> <br>
<span class="speakerposition">ETH Zurich</span>
</div>
</div>

---
<div class="speaker-wrap">
<div class="speakerphoto">
<img src="assets/img/ankit_patel.jpg">
</div>
<div class="card">
<a class="talkdate" href="./patel_lecture">Wednesday, 10/18/17</a> <br>
<span class="speaker">Ankit Patel</span> <br>
<span class="speakerposition">Rice and BCM</span>
</div>
</div>
---
<div class="speaker-wrap">
<div class="speakerphoto">
<img src="assets/img/poggio.png">
</div>
<div class="card">
<a class="talkdate" href="./poggio_lecture">Wednesday, 10/25/17</a> <br>
<span class="speaker">Tomaso Poggio</span> <br>
<span class="speakerposition">MIT</span>
</div>
</div>
---
<div class="speaker-wrap">
<div class="speakerphoto">
<img src="assets/img/zaid.png">
</div>
<div class="card">
<a class="talkdate" href="./harchaoui_lecture">Wednesday, 11/01/17</a> <br>
<span class="speaker">Zaid Harchaoui</span> <br>
<span class="speakerposition">UW</span>
</div>
</div>
---
<div class="speaker-wrap">
<div class="speakerphoto">
<img src="assets/img/pennington.jpg">
</div>
<div class="card">
<a class="talkdate" href="./pennington_lecture">Wednesday, 11/08/17</a> <br>
<span class="speaker">Jeffrey Pennington</span> <br>
<span class="speakerposition">Google, NY</span>
</div>
</div>
---
<div class="speaker-wrap">
<div class="speakerphoto">
<img src="assets/img/bruna.png">
</div>
<div class="card">
<a class="talkdate" href="./bruna_lecture">Wednesday, 11/15/17</a> <br>
<span class="speaker">Joan Bruna</span> <br>
<span class="speakerposition">Courant Institute, NYU</span>
</div>
</div>
---
<div class="speaker-wrap">
<div class="speakerphoto">
<img src="assets/img/bruno_olshausen.jpg">
</div>
<div class="card">
<a class="talkdate" href="./olshausen_lecture">Wednesday, 11/29/17</a> <br>
<span class="speaker">Bruno Olshausen</span> <br>
<span class="speakerposition">UC Berkeley</span>
</div>
</div>
---
<div class="speaker-wrap">
<div class="speakerphoto">
<img src="assets/img/VardanPapyan.png">
</div>
<div class="card">
<a class="talkdate" href="./papyan_lecture">Wednesday, 12/6/17</a> <br>
<span class="speaker">Vardan Papyan</span> <br>
<span class="speakerposition">Stanford</span>
</div>
</div>

## [Looking for a postdoc?](postdoc)

## [In the media](media)

## [Reading list and other resources](readings)

## [Lecture slides](lecture_slides)    

## [Basic information about deep learning](basicinfo)    

## [Cheat sheet -- stuff that everyone needs to know](cheat_sheet)    

## [The course in a single graph](http://bl.ocks.org/vardanp91/raw/be0f763405b76d33caefdaebc2ac3487/)

## [Blogs](blogs)

## [Grading](grading)

## [Plan your visit](speaker_visit)
-->
