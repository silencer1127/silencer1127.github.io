---
title: "JOSA"
category: "main"
permalink: /software/JOSA/josa_main
layout: single
date: 2024-08-28
---

<div class="text-center" style="font-size: 2em; font-weight: bold;">JOSA</div>
<div class="text-center" style="font-size: 1.2em;">Joint spherical registration and altas building</div>

<br> 

<div class="table-like authors">
  <div>
    <center>
      <a href="https://silencer1127.github.io/" target="_blank">Jian Li (Andrew)</a>
    </center>
    <center>
      <p class="affiliation">MGH Martinos &amp; CNTR</p>
    </center>
  </div>
  <div>
  	<center>
      <a href="http://www.tuckute.com/" target="_blank">Greta Tuckute</a>
    </center>
    <center>
      <p class="affiliation">MIT BCS &amp; McGovern</p>
    </center>
  </div>
  <div>
    <center>
      <a href="https://www.evlab.mit.edu/about-ev" target="_blank">Evelina Fedorenko</a>
    </center>
    <center>
      <p class="affiliation">MIT BCS &amp; McGovern</p>
    </center>
  </div>
  <div class="break"></div>
  <div>
    <center>
      <a href="https://www.comarecoverylab.org/brian-l-edlow-md" target="_blank">Brian L. Edlow</a>
    </center>
    <center>
      <p class="affiliation">MGH Martinos &amp; CNTR</p>
    </center>
  </div>
  <div>
    <center>
      <a href="https://www.mit.edu/~adalca/" target="_blank">Adrian V. Dalca</a>
    </center>
    <center>
      <p class="affiliation">MGH Martinos &amp; MIT CSAIL</p>
    </center>
  </div>
  <div>
    <center>
      <a href="https://lcn.martinos.org/people/fischl/" target="_blank">Bruce Fischl</a>
    </center>
    <center>
      <p class="affiliation">MGH Martinos &amp; MIT CSAIL</p>
    </center>
  </div>
</div>
<br>
<div class="text-center">
	<p style="font-size: 1.2em; font-weight: bold; color: #f79646">Medical Image Analysis</p>
</div>

<div class="text-center">
	<a href="https://silencer1127.github.io/files/pdf/Li_2024_MedImageAnal_Josa.pdf" target="_blank"><i class="fa fa-file-pdf-o"></i> &nbsp;Paper</a>
	&nbsp;&nbsp;&nbsp;
	<a href="https://github.com/freesurfer/freesurfer" target="_blank"><i class="fa fa-code"></i> &nbsp;Code</a>
</div>

## Overview

Surface-based cortical registration is an important topic in medical image analysis and facilitates many downstream applications. Current approaches for cortical registration are mainly driven by geometric features, such as sulcal depth and curvature, and often assume that registration of folding patterns leads to alignment of brain function. However, functional variability of anatomically corresponding areas across subjects has been widely reported, particularly in higher-order cognitive areas.

We present JOSA, a novel cortical registration framework that jointly models the mismatch between geometry and function while simultaneously learning an unbiased population-specific atlas. Using a semi-supervised training strategy, JOSA achieves superior registration performance in both geometry and function to the state-of-the-art methods but without requiring functional data at inference. This learning framework can be extended to any auxiliary data to guide spherical registration that is available during training but is difficult or impossible to obtain during inference, such as parcellations, architectonic identity, transcriptomic information, and molecular profiles.

![](/images/software/JOSA/NN.jpg)

## Validation

When trained using a large set of language task fMRI localizer maps [(Lipkin et al. 2022)](http://dx.doi.org/10.1038/s41597-022-01645-3){:target="_blank"}, JOSA achieved a substantially better alignment in both folding patterns and function, compared to the state-of-the-art registration methods. In particular, the predominant language region in the superior temporal gyrus shows a substantially higher and larger agreement across subjects.

![](/images/software/JOSA/Qual.jpg)

## Learned atlas

In contrast to many other learning-based methods, JOSA also estimates a population-specific atlas as the registration target during training. We find that the JOSA atlas provides more anatomical definition, supporting registration with higher resolution and finer details, which also contributes to the improved performance of JOSA.

![](/images/software/JOSA/Atlas.jpg)

## Citation

If you find our work or any of our materials useful, please cite our papers:

J. Li, G. Tuckute, E. Fedorenko, B. L. Edlow, A. V. Dalca<sup>&Dagger;</sup>, B. Fischl<sup>&Dagger;</sup>, "JOSA: Joint surface-based registration and atlas construction of brain geometry and function", *Medical Image Analysis*, , p. 103292, 2024. &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/Li_2024_MedImageAnal_Josa.bib)  

J. Li, G. Tuckute, E. Fedorenko, B. L. Edlow, B. Fischl<sup>&Dagger;</sup>, A. V. Dalca<sup>&Dagger;</sup>, "Joint cortical registration of geometry and function via semi-supervised learning", *Medical Imaging with Deep Learning*, Nashville, TN, Jul. 2023, pp. 862--876. &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/Li_2023_MIDL_Joint.bib)  


## Disclaimer

IN NO EVENT SHALL THE AUTHORS, THE CONTRIBUTORS, THE DISTRIBUTORS, THE MASSACHUSETTS GENERAL HOSPITAL ("AUTHORS") BE LIABLE TO ANY PARTY FOR DIRECT, INDIRECT, SPECIAL, INCIDENTAL, OR CONSEQUENTIAL DAMAGES, INCLUDING LOST PROFITS, ARISING OUT OF THE USE OF THIS CODE, EVEN IF THE AUTHORS HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGE. THE AUTHORS SPECIFICALLY DISCLAIMS ANY WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE. FOR RESEARCH PURPOSE ONLY. THIS CODE IS PROVIDED ON A "AS IS" BASIS AND THE AUTHORS HAVE NO OBLIGATION TO PROVIDE MAINTENANCE, SUPPORT, UPDATES, ENHANCEMENTS, OR MODIFICATIONS.
