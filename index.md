---
layout: titlepage3
---

This class meets Tuesday and Thursday from 10:30 - 11:50 AM in [Packard, Room 101](https://campus-map.stanford.edu/?srch=Packard%20Electrical%20Engineering).

## Teaching Assistants

<div class="speaker-wrap">
<div class="speakerphoto">
<img src="assets/img/Nathan.png">
</div>
<div class="card">
<a class="talkdate" href="https://people.stanford.edu/stanfurd/">Nathan Zhang</a> <br>
<span class="speaker">Office Hours TBA</span> <br>
</div>
</div>

<div class="speaker-wrap">
<div class="speakerphoto">
<img src="assets/img/Nandita.jpg">
</div>
<div class="card">
<a class="talkdate" href="http://web.stanford.edu/~nanbhas/">Nandita Bhaskhar</a> <br>
<span class="speaker">Office Hours TBA</span> <br>
</div>
</div>

## Class Information
<img src="https://www.nsf.gov/images/logos/NSF_4-Color_bitmap_Logo_thumb.jpg">NSF</img>
<p>
Funding for this research/activity was partially provided by the  National Science Foundation Division of Computing and Communication Foundations under award number <a href="https://nsf.gov/awardsearch/showAward?AWD_ID=1563113&HistoricalAwards=false">1563113</a>.
</p>

## Schedule

<style type="text/css">
.tg  {
  border-collapse:collapse;
  border-spacing:0;
}

.tg td {
  font-family:Arial, sans-serif;
  font-size:14px;
  padding:10px 5px;
  overflow:hidden;
  word-break:normal;
  border: 1px solid black;
}

.tg th {
  font-family:Arial, sans-serif;
  font-size:14px;
  font-weight:normal;
  padding:10px 5px;
  overflow:hidden;
  word-break:normal;
}

.tg td {
  font-weight:bold;
  text-align:center;
  vertical-align:top;
}

.tg td:last-child {
  vertical-align:top;
}

</style>
<table width="720" class="tg">
<tbody>
<tr>
<td width="36">
<p><strong>Lecture</strong></p>
</td>
<td width="96">
<p><strong>Date</strong></p>
</td>
<td width="294">
<p><strong>Topic</strong></p>
</td>
<td width="198">
<p><strong>Reading</strong></p>
</td>
<td width="96">
<p><strong>Spatial Assignment</strong></p>
</td>
</tr>
<tr>
<td width="36">
<p>1</p>
</td>
<td width="96">
<p>9/25/2018</p>
</td>
<td width="294">
<p>Introduction,</p>
<p>Softwore 2.0</p>
<p>Role of hardware accelerators in post Dennard&nbsp;and Moore era</p>
</td>
<td width="198">
<p>&nbsp;</p>
</td>
<td width="96">
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td width="36">
<p>2</p>
</td>
<td width="96">
<p>9/27/2018</p>
</td>
<td width="294">
<p>Guest Lecture: Kian Katan</p>
<p>Classical ML algorithms: Regression, SVMs</p>
<p>(What is the&nbsp;building block?)</p>
</td>
<td width="198">
<p><u><a href="https://ieeexplore.ieee.org/document/6241647/">Is Dark silicon useful?</a></u><br /> Hennessy Patterson Chapter 7.1-7.2</p>
</td>
<td width="96">
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td width="36">
<p>3</p>
</td>
<td width="96">
<p>10/2/2018</p>
</td>
<td width="294">
<p>Linear algebra fundamentals and accelerating linear algebra<br /> BLAS operations<br /> 20th century techniques: Systolic arrays and MIMDs, CGRAs</p>
</td>
<td width="198">
<p><u><a href="http://www.eecs.harvard.edu/~htk/publication/1982-kung-why-systolic-architecture.pdf">Why Systolic Architectures?</a></u><br /> <u><a href="https://www.cs.utexas.edu/users/pingali/CS378/2008sp/papers/gotoPaper.pdf">Anatomy of high performance GEMM</a></u></p>
<p><u><a href="https://arxiv.org/abs/1602.04183">Dark Memory</a></u></p>
</td>
<td width="96">
<p></p>
</td>
</tr>
<tr>
<td width="36">
<p>4</p>
</td>
<td width="96">
<p>10/4/2018</p>
</td>
<td width="294">
<p>Guest Lecture: Hadi Esmaeilzadeh</p>
<p>Tabla &amp; Cosmic</p>
</td>
<td width="198">
<p><u><a href="https://www.cc.gatech.edu/~hadi/doc/paper/2015-tr-tabla.pdf">TABLA</a></u></p>
<p><u><a href="https://ieeexplore.ieee.org/document/6212466/">Codesign Tradeoffs</a></u></p>
</td>
<td width="96">
<p></p>
</td>
</tr>
<tr>
<td width="36">
<p>5</p>
</td>
<td width="96">
<p>10/9/2018</p>
</td>
<td width="294">
<p>David Koeplinger &amp; Tian: Modeling neural networks with Spatial, Analyzing&nbsp;<br /> performance and energy with Spatial</p>
</td>
<td width="198">
<p><u><a href="https://stanford-ppl.github.io/website/papers/pldi18_koeplinger.pdf">Spatial</a></u><br />
<u><a href="https://dl.acm.org/citation.cfm?id=2665689"> Aladdin </a></u>
</p>
</td>
<td width="96">
<p></p>
<p>Linear Algebra<br /> Accelerators</p>
</td>
</tr>
<tr>
<td width="36">
<p>6</p>
</td>
<td width="96">
<p>10/11/2018</p>
</td>
<td width="294">
<p><strong>Evaluating Performance, Energy efficiency, Parallelism, Locality,<br /> Memory hierarchy, Roofline model</strong></p>
<p>Real-World Architectures: Putting it into practice<br /> Accelerating GEMM:<br /> Custom, GPU, TPU1 architectures and their GEMM performance</p>
</td>
<td width="198">
<p><u><a href="https://people.eecs.berkeley.edu/~kubitron/cs252/handouts/papers/RooflineVyNoYellow.pdf">Roofline Model </a> </u></p>
<p><u><a href="https://arxiv.org/pdf/1704.04760.pdf">Google TPU</a></u><br /> <u><a href="http://images.nvidia.com/content/volta-architecture/pdf/volta-architecture-whitepaper.pdf">NVIDIA Tesla V100</a></u></p>
</td>
<td width="96">
<p></p>
</td>
</tr>
<tr>
<td width="36">
<p>7</p>
</td>
<td width="96">
<p>10/16/2018</p>
</td>
<td width="294">
<p>Neural networks: MLPs and CNNs Inference</p>
<p>Accelerating Inference for CNNs</p>
<p>Blocking and parallelism</p>
<p>DianNao, TPUs</p>
</td>
<td width="198">
<p><u><a href="http://www.rle.mit.edu/eems/wp-content/uploads/2017/11/2017_pieee_dnn.pdf">Efficient Processing of DNNs</a></u><br /></p>
<p><u><a href="https://arxiv.org/abs/1606.04209">Systematic Approach to Blocking</a></u></p>
</td>
<td width="96">
<p></p>
</td>
</tr>
<tr>
<td width="36">
<p>8</p>
</td>
<td width="96">
<p>10/18/2018</p>
</td>
<td width="294">
<p>Guest Lecture: Yu-Hsin</p>
<p>CNN Inference</p>
</td>
<td width="198">
<p><u><a href="https://people.csail.mit.edu/emer/papers/2016.06.isca.eyeriss_architecture.pdf">Eyeriss</a></u><br /> Google TPU (see lecture 5)
<br />
<u><a href="https://www.morganclaypool.com/doi/abs/10.2200/S00783ED1V01Y201706CAC041">Brooks' Book, Chapter 5</a></u>
</p>
</td>
<td width="96">
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td width="36">
<p>9</p>
</td>
<td width="96">
<p>10/23/2018</p>
</td>
<td width="294">
<p>Accelerating CNN cont.</p>
<p>&nbsp;</p>
</td>
<td width="198">
<p> <u><a href="https://arxiv.org/pdf/1809.10170.pdf">
High Performance Zero-Memory Overhead Direct Convolutions
</a></u> <br/> <u> <a href="https://arxiv.org/abs/1509.09308">Fast algorithms for convolution </a> </u> </p>
</td>
<td width="96">
</td>
</tr>
<tr>
<td width="36">
<p>10</p>
</td>
<td width="96">
<p>10/25/2018</p>
</td>
<td width="294">
<p>Guest Lecture: Robert Schreiber</p>
<p>&nbsp;</p>
</td>
<td width="198">
<p>&nbsp;</p>
</td>
<td width="96">
<p>CNN Inference<br /> Accelerators</p>
</td>
</tr>
<tr>
<td width="36">
<p>11</p>
</td>
<td width="96">
<p>10/30/2018</p>
</td>
<td width="294">
<p>Training 1: SGD, back propagation, statistical efficiency, batch size</p>
</td>
<td width="198">
<p>
  <u><a href="https://arxiv.org/pdf/1706.00517.pdf">Caterpillar</a></u><br />
  <u><a href="https://dl.acm.org/citation.cfm?doid=3079856.3080244">ScaleDeep</a></u><br />
  <u><a href="https://youtu.be/7XtBZ4Hsi_M">GraphCore Talk</a></u>
  </p>
</td>
<td width="96">
<p></p>
<p></p>
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td width="36">
<p>12</p>
</td>
<td width="96">
<p>11/1/2018</p>
</td>
<td width="294">
<p>Guest Lecture: Boris Ginsburg</p>
<p>Generalization and Regularization of Training</p>
<p>&nbsp;</p>
</td>
<td width="198">
  <u><a href="http://ruder.io/optimizing-gradient-descent/"> Optimizing Gradient Descent </a></u> <br />
  <u><a href="https://arxiv.org/pdf/1708.03888.pdf"> Large Batch Training of Convolutional Networks </a> </u> <br />
  <u><a href="https://arxiv.org/pdf/1607.04381.pdf"> Dense-Sparse-Dense </a> </u>
</td>
<td width="96">
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td width="36">
<p>13</p>
</td>
<td width="96">
<p>11/6/2018</p>
</td>
<td width="294">
<p>Guest Lecture: Paulius Micikevicius</p>
<p>Low Precision of Training</p>
</td>
<td width="198">
  <u><a href="https://arxiv.org/abs/1803.03383.pdf">HALP</a></u><br/>
  <u><a href="https://arxiv.org/pdf/1602.01528.pdf">EIE</a></u>
</td>
<td width="96">
GEMV + Project Proposals due 11/6
  <br />
 GEMM due 11/10
<p>&nbsp;</p>
<p></p>
</td>
</tr>
<tr>
<td width="36">
<p>14</p>
</td>
<td width="96">
<p>11/8/2018</p>
</td>
<td width="294">
<p>Guest Lecture: Eric Chung Catapult, Brainwave</p>
</td>
<td width="198">
<p><u><a href="https://www.microsoft.com/en-us/research/wp-content/uploads/2016/10/Cloud-Scale-Acceleration-Architecture.pdf">Catapult</a></u><br /> <u><a href="https://www.microsoft.com/en-us/research/uploads/prod/2018/03/mi0218_Chung-2018Mar25.pdf">Brainwave</a></u></p>
</td>
<td width="96">
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td width="36">
<p>15</p>
</td>
<td width="96">
<p>11/13/2018</p>
</td>
<td width="294">
<p>Guest Lecture: Cliff Young:</p>
<p>ML benchmarks MLPerf</p>
</td>
<td width="198">
<p><u><a href="https://cs.stanford.edu/~matei/papers/2017/nips_sysml_dawnbench.pdf">DawnBench</a></u><br /> <u><a href="https://mlperf.org/">MLPerf</a></u></p>
</td>
<td width="96">
  Staff meetings with student project groups
  <br />
  CNN assignment due 11/17
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td width="36">
<p>16</p>
</td>
<td width="96">
<p>11/15/2018</p>
</td>
<td width="294">
<p>Scaling Training</p>
</td>
<td width="198">
<u><a href="https://arxiv.org/pdf/1804.07612.pdf">Revisiting Small Batch Training for Neural Networks </a></u><br />
  <u><a href="https://supercomputersfordl2017.github.io/">Deep Learning At Supercomputer Scale</a></u><br />
  <u><a href="https://arxiv.org/abs/1712.01887">Deep Gradient Compression</a></u>
</td>
<td width="96">
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td width="36">
<p>-</p>
</td>
<td width="96">
<p>11/20/2018</p>
</td>
<td width="294">
<p>Thanksgiving</p>
</td>
<td width="198">
<p>&nbsp;</p>
</td>
<td width="96">
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td width="36">
<p>-</p>
</td>
<td width="96">
<p>11/22/2018</p>
</td>
<td width="294">
<p>Thanksgiving</p>
</td>
<td width="198">
<p>&nbsp;</p>
</td>
<td width="96">
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td width="36">
<p>17</p>
</td>
<td width="96">
<p>11/27/2018</p>
</td>
<td width="294">
<p>FPGAs and CGRAs, Plasticine</p>
</td>
<td width="198">
<p><u><a href="http://dawn.cs.stanford.edu/pubs/plasticine-isca2017.pdf">Plasticine</a></u></p>
</td>
<td width="96">
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td width="36">
<p>18</p>
</td>
<td width="96">
<p>11/29/2018</p>
</td>
<td width="294">
<p>Guest Lecture: Mikhail Smelyanskiv</p>
<p>AI at Facebook Datacenter Scale&nbsp;</p>
</td>
<td width="198">
<p>
  <a href="https://research.fb.com/publications/applied-machine-learning-at-facebook-a-datacenter-infrastructure-perspective/">ML @ Facebook </a>, Due Friday
  </p>
</td>
<td width="96">
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td width="36">
<p>19</p>
</td>
<td width="96">
<p>12/4/2018</p>
</td>
<td width="294">
<p>NIPS Keynote Preview</p>
<p>Programming Assignment Optimization and Performance</p>
</td>
<td width="198">
<p>&nbsp;</p>
</td>
<td width="96">
<p>&nbsp;</p>
</td>
</tr>
<tr>
<td width="36">
<p>20</p>
</td>
<td width="96">
<p>12/6/2018</p>
</td>
<td width="294">
<p>No Lecture</p>
</td>
<td width="198">
<p>&nbsp;</p>
</td>
<td width="96">
<p>&nbsp;</p>
</td>
</tr>
</tbody>
</table>

## [](#Lectures) Guest Lectures

<div class="speaker-wrap">
<div class="speakerphoto">
<img src="assets/img/kian_katanforoosh.jpg">
</div>
<div class="card">
<a class="talkdate" href="./katanforoosh_lecture">Kian Katanforoosh, deeplearning.ai and Stanford University</a> <br>
<span class="speaker">From Machine Learning to Deep Learning: a computational transition</span> <br>
<span class="speakerposition">Thursday September 27, 2018</span>
</div>
</div>

* * *

<div class="speaker-wrap">
<div class="speakerphoto">
<img src="assets/img/hadi_esmaeilzadeh.jpg">
</div>
<div class="card">
<a class="talkdate" href="./esmaeilzadeh_lecture">Hadi Esmaeilzadeh, UC San Diego</a> <br>
<span class="speaker">TABLA</span> <br>
<span class="speakerposition">Thursday October 4, 2018</span>
</div>
</div>

* * *

<div class="speaker-wrap">
<div class="speakerphoto">
<img src="assets/img/YuHsin_Chen.png">
</div>
<div class="card">
<a class="talkdate" href="./chen_lecture">Yu-Hsin Chen, MIT</a> <br>
<span class="speaker">Accelerating Inference for CNNs & Eyeriss</span> <br>
<span class="speakerposition">Thursday October 18, 2018</span>
</div>
</div>

* * *

<div class="speaker-wrap">
<div class="speakerphoto">
<img src="assets/img/Robert_Schreiber.jpeg">
</div>
<div class="card">
<a class="talkdate" href="./schreiber_lecture">Robert Schreiber, Cerebras Systems</a> <br>
<span class="speaker">Understanding Numerical Errors</span> <br>
<span class="speakerposition">Thursday October 25, 2018</span>
</div>
</div>

* * *

<div class="speaker-wrap">
<div class="speakerphoto">
<img src="assets/img/Boris_Ginsburg-200x200.jpg">
</div>
<div class="card">
<a class="talkdate" href="./ginsburg_lecture">Boris Ginsburg, NVIDIA</a> <br>
<span class="speaker">Large Batch Training of Convolution Networks</span> <br>
<span class="speakerposition">Thursday November 1, 2018</span>
</div>
</div>

* * *

<div class="speaker-wrap">
<div class="speakerphoto">
<img src="assets/img/paulius-200x200.jpg">
</div>
<div class="card">
<a class="talkdate" href="">Paulius Micikevicius, NVIDIA</a> <br>
<span class="speaker">Low Precision Training</span> <br>
<span class="speakerposition">Tuesday November 6, 2018</span>
</div>
</div>

* * *

<div class="speaker-wrap">
<div class="speakerphoto">
<img src="assets/img/Eric_Chung.png">
</div>
<div class="card">
<a class="talkdate" href="./chung_lecture">Eric Chung, Microsoft Research</a> <br>
<span class="speaker">Real-Time AI at Cloud Scale with Project Brainwave</span> <br>
<span class="speakerposition">Thursday November 8, 2018</span>
</div>
</div>

* * *

<div class="speaker-wrap">
<div class="speakerphoto">
<img src="assets/img/cliff_young.jpg">
</div>
<div class="card">
<a class="talkdate" href="./young_lecture">Cliff Young, Google</a> <br>
<span class="speaker">MLPerf</span> <br>
<span class="speakerposition">Tuesday November 13, 2018</span>
</div>
</div>

* * *

<div class="speaker-wrap">
<div class="speakerphoto">
<img src="assets/img/Mikhail_Smelyanskiy.JPG">
</div>
<div class="card">
<a class="talkdate" href="./smelyanskiy_lecture">Mikhail Smelyanskiy, Facebook</a> <br>
<span class="speaker">AI at Facebook Datacenter Scale</span> <br>
<span class="speakerposition">Thursday November 29, 2018</span>
</div>
</div>

## Related Stanford Courses

-   [CS230](http://cs230.stanford.edu/syllabus.html)
-   [CS231n](http://cs231n.github.io)
-   [STATS 385](https://stats385.github.io/)

## [Reading list and other resources](readings)

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
