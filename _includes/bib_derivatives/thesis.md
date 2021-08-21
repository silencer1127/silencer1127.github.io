### 2019: Doctor of Philosophy in Electrical Engineering

* **J. Li**,  
"Functional connectivity analysis and network identification in the human brain",  
*University of Southern California*, Los Angeles, CA, May 2019.  &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/Li_2019_USC_Functional.bib)  
[https://digitallibrary.usc.edu/asset-management/2A3BF1WJGF0M](https://digitallibrary.usc.edu/asset-management/2A3BF1WJGF0M){:target="Li_2019_USC_Functional"}  
  <details>
    <summary style="font-size:16px">Abstract</summary>
      <p style="margin-left: 20px; text-align: justify; font-size:16px">
      Brain connectivity is modeled as a complex, segregative and integrative network of connections between different brain regions. Studying functional brain connectivity can offer us an effective way to examine how different brain networks relate to human behaviors as well as how those networks may be altered in neurological diseases. However, measuring functional connectivity poses a variety of mathematical, signal processing and neuroscience challenges. First, a good high-level representation of the data is often required in order to obtain an accurate estimation of the functional connectivity, because most of the typically-used linear measures are not capable of capturing the true highly non-linear brain interactions. Second, the temporal stationarity of the time series assumed by most of the studies may not be realistic due to the dynamic nature of the brain. Hence, how to reliably estimate the spatial and temporal dynamics of functional connectivity simultaneously is a key challenge to us. Moreover, signals collected via almost all neuroimaging techniques are heavily corrupted with noise. The inherent low signal-to-noise ratio prevents us from obtaining a robust estimation of functional connectivity. In this work, we present and validate several novel approaches and methods to address some of the challenges in functional connectivity estimation and brain network identification problems. To address the high-level data representation issue, we defined a bio-electrical marker that can differentiate the epileptogenic zone from areas of propagation in patients with epilepsy. We discovered a specific ictal time-frequency pattern, referred as the “fingerprint”, in the epileptogenic zone which contains a combination of sharp spikes preceding multi-band fast activity concurrent with suppression of lower frequencies. We developed a novel machine learning system that automatically extracts each of these features, classifies electrode contacts as being within the epileptogenic zone or outside the epileptogenic zone and generates individualized epileptogenic zone predictions for each patient based on their anatomical magnetic resonance images. To address the dynamic brain network identification issue, we developed a rank-recursive scalable and robust sequential canonical polyadic decomposition framework that allows us to robustly discover brain networks which can overlap in both space and time in large-scale datasets. The robustness and scalability were achieved by using lower-rank solutions as the warm start to higher-rank decompositions. This scalable and robust sequential canonical polyadic decomposition framework is flexible in the sense that it is not only applicable to wavelet-transformed electroencephalography data but also to multi-subject asynchronous functional magnetic resonance imaging data if the data is temporally aligned across subjects using the BrainSync algorithm. To address the noise corruption issue, we described an optimization-based method that provides a means of systematically selecting the parameter for the temporal non-local means filtering. We further developed global PDF-based temporal non-local means, a novel data-driven optimized kernel function based on Bayes factor for the temporal non-local means filtering, which allows us to perform global filtering with improved noise reduction effects but without blurring adjacent functional regions. Applications of these proposed methods are illustrated using a variety of simulated as well as in-vivo clinical data.
      </p>
  </details>

### 2017: Master of Science in Statistics

* **J. Li**,  
"Distributed parameter model based system identification and input determination in the estimation of blood alcohol concentration from transdermal alcohol biosensor data",  
*University of Southern California*, Los Angeles, CA, Jul. 2017.  &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/Li_2017_USC_Distributed.bib)  
[https://digitallibrary.usc.edu/asset-management/2A3BF16286SX](https://digitallibrary.usc.edu/asset-management/2A3BF16286SX){:target="Li_2017_USC_Distributed"}  
  <details>
    <summary style="font-size:16px">Abstract</summary>
      <p style="margin-left: 20px; text-align: justify; font-size:16px">
      Methods for the estimation of blood or breath alcohol concentration (BAC/BrAC) from biosensor measured transdermal alcohol concentration (TAC) are developed, evaluated and compared. Specifically, a scheme based on a distributed parameter model with unbounded input and output for ethanol transport in the skin is compared to more conventional filtering/deconvolution techniques, one based on frequency domain methods, and the other on a time series approach using an autoregressive moving average (ARMA) input/output model. Our basis for comparison are five statistics of interest to alcohol researchers and clinicians: peak BAC/BrAC, time of peak BAC/BrAC, the ascending and descending slopes of the BAC/BrAC curve and area underneath the BAC/BrAC curve. It can be shown that the ARMA-based method yields the best estimation of the peak while the distributed parameter model produces the best estimation of the time of the peak. The Fourier-based method has the least variance out of the three and is computationally very efficient.
      </p>
  </details>

### 2011: Bachelor of Engineering in Electronic and Information Engineering

* **J. Li**,  
"Spatio-temporal correlation-based near-duplicate video detection",  
*Beijing University of Technology*, Beijing, China, Jun. 2011.  &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/Li_2011_BJUT_Spatio.bib)  
  <details>
    <summary style="font-size:16px">Abstract</summary>
      <p style="margin-left: 20px; text-align: justify; font-size:16px">
      视频拷贝检测是目前多媒体处理领域的前沿研究热点，在海量视频信息检索和版权保护等方面有着重要的应用价值。视频拷贝检测的实质在于判断不同的视频片段是否具有相同的内容，从而实现对特定视频内容的搜索、检测和跟踪。在视频拷贝检测技术领域，当前国内外的研究重点是寻找各种复杂的特征提取方法来提高拷贝检测的准确性。然而在实际应用中，最需要解决的问题是在大规模数据下，在保持检测的准确性、鲁棒性的同时，如何显著提高拷贝检测的速度。本论文提出了一种基于时空相关性的视频拷贝检测技术。该技术利用视频时间和空间的相关性，直接在压缩域进行视频拷贝检测，在不解压或者少解压的情况下，在保证检测准确性的同时，大大提高检测的速度。该方法的实现过程如下: 首先，从 MPEG-2 压缩码流中提取亮度、颜色、纹理、运动 以及显著图等信息，然后利用这些信息对待检测的两段视频进行粗略的镜头分割，使之成为视频段落，然后对压缩域中提取的各种特征信息并进行统计，依据某一准则进行比对，最后综合各种特征的对比结果，给出两段视频相似程度。实验结果表明，本文提出的基于时空相关性的视频拷贝检测算法能够在保证检测准确率的同时，有效地降低处理复杂度，提升检测效率，并对不同分辨率、不同质量、不同内容的视频均具有较强的鲁棒性。
      </p>
  </details>
