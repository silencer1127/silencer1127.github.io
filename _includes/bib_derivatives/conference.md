### 2023

* **J. Li**, G. Tuckute, E. Fedorenko, B. L. Edlow, B. Fischl<sup>&Dagger;</sup>, A. V. Dalca<sup>&Dagger;</sup>,  
"Joint cortical registration of geometry and function via semi-supervised learning",  
*Medical Imaging with Deep Learning*, Nashville, TN, Jul. 2023.  &nbsp; [<i class="fa fa-link"></i>](https://openreview.net/forum?id=n9v_BuIcY7G){:target="Li_2023_MIDL_Joint-LINK"} &nbsp; [<i class="fa fa-file-pdf-o"></i>](/files/pdf/Li_2023_MIDL_Joint.pdf){:target="Li_2023_MIDL_Joint-PDF"} &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/Li_2023_MIDL_Joint.bib)  
  <details>
    <summary style="font-size:16px">Abstract</summary>
      <p style="margin-left: 20px; text-align: justify; font-size:16px">
      Brain surface-based image registration, an important component of brain image analysis, establishes spatial correspondence between cortical surfaces. Existing iterative and learning-based approaches focus on accurate registration of folding patterns of the cerebral cortex, and assume that geometry predicts function and thus functional areas will also be well aligned. However, structure/functional variability of anatomically corresponding areas across subjects has been widely reported. In this work, we introduce a learning-based cortical registration framework, JOSA, which jointly aligns folding patterns and functional maps while simultaneously learning an optimal atlas. We demonstrate that JOSA can substantially improve registration performance in both anatomical and functional domains over existing methods. By employing a semi-supervised training strategy, the proposed framework obviates the need for functional data during inference, enabling its use in broad neuroscientific domains where functional data may not be observed.
      </p>
  </details>

### 2021

* A. A. Joshi, S. Choi, **J. Li**, H. Akrami, R. M. Leahy,  
"A pairwise approach for fMRI group studies using BrainSync transform",  
*Proc. SPIE Medical Imaging 2021: Image Processing*, San Diego, CA, Mar. 2021.  &nbsp; [<i class="fa fa-link"></i>](https://doi.org/10.1117/12.2580980){:target="Joshi_2021_SPIEMI_Pairwise-LINK"} &nbsp; [<i class="fa fa-file-pdf-o"></i>](/files/pdf/Joshi_2021_SPIEMI_Pairwise.pdf){:target="Joshi_2021_SPIEMI_Pairwise-PDF"} &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/Joshi_2021_SPIEMI_Pairwise.bib)

### 2020

* **J. Li**, A. A. Joshi, R. M. Leahy,  
"A network-based approach to study of ADHD using tensor decomposition of resting fMRI data",  
*IEEE 17th International Symposium on Biomedical Imaging*, Iowa City, IA, Apr. 2020, pp. 1--5.  &nbsp; [<i class="fa fa-link"></i>](https://doi.org/10.1109/ISBI45749.2020.9098584){:target="Li_2020_ISBI_Network-LINK"} &nbsp; [<i class="fa fa-file-pdf-o"></i>](/files/pdf/Li_2020_ISBI_Network.pdf){:target="Li_2020_ISBI_Network-PDF"} &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/Li_2020_ISBI_Network.bib)  
  <details>
    <summary style="font-size:16px">Abstract &nbsp; <i class="fa fa-video-camera"></i></summary>
      <p style="margin-left: 20px; text-align: justify; font-size:16px">
      Identifying changes in functional connectivity in Attention Deficit Hyperactivity Disorder (ADHD) using functional magnetic resonance imaging (fMRI) can help us understand the neural substrates of this brain disorder. Many studies of ADHD using resting state fMRI (rs-fMRI) data have been conducted in the past decade with either manually crafted features that do not yield satisfactory performance, or automatically learned features that often lack interpretability. In this work, we present a tensor-based approach to identify brain networks and extract features from rs-fMRI data. Results show the identified networks are interpretable and consistent with our current understanding of ADHD conditions. The extracted features are not only predictive of ADHD score but also discriminative for classification of ADHD subjects from typically developed children.
      </p>
      <div class ="responsive-video-container"><iframe src="https://www.youtube.com/embed/yRRqWTOTJ_A" width="560" height="315" frameborder="0" allowfullscreen allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"></iframe></div>
  </details>

* H. Akrami, A. A. Joshi, **J. Li**, S. Aydöre, R. M. Leahy,  
"Brain lesion detection using a robust variational autoencoder and transfer learning",  
*IEEE 17th International Symposium on Biomedical Imaging*, Iowa City, IA, Apr. 2020, pp. 786--790.  &nbsp; [<i class="fa fa-link"></i>](https://doi.org/10.1109/ISBI45749.2020.9098405){:target="Akrami_2020_ISBI_Brain-LINK"} &nbsp; [<i class="fa fa-file-pdf-o"></i>](/files/pdf/Akrami_2020_ISBI_Brain.pdf){:target="Akrami_2020_ISBI_Brain-PDF"} &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/Akrami_2020_ISBI_Brain.bib)  
  <details>
    <summary style="font-size:16px">Abstract</summary>
      <p style="margin-left: 20px; text-align: justify; font-size:16px">
      Automated brain lesion detection from multi-spectral MR images can assist clinicians by improving sensitivity as well as specificity. Supervised machine learning methods have been successful in lesion detection. However, these methods usually rely on a large number of manually delineated images for specific imaging protocols and parameters and often do not generalize well to other imaging parameters and demographics. Most recently, unsupervised models such as autoencoders have become attractive for lesion detection since they do not need access to manually delineated lesions. Despite the success of unsupervised models, using pre-trained models on an unseen dataset is still a challenge. This difficulty is because the new dataset may use different imaging parameters, demographics, and different pre-processing techniques. Additionally, using a clinical dataset that has anomalies and outliers can make unsupervised learning challenging since the outliers can unduly affect the performance of the learned models. These two difficulties make unsupervised lesion detection a particularly challenging task. The method proposed in this work addresses these issues using a two-prong strategy: (1) we use a robust variational autoencoder model that is based on robust statistics, specifically the beta-divergence that can be trained with data that has outliers; (2) we use a transfer learning method for learning models across datasets with different characteristics. Our results on MRI datasets demonstrate that we can improve the accuracy of lesion detection by adapting robust statistical models and transfer learning for a variational autoencoder model.
      </p>
  </details>

### 2019

* A. A. Joshi, H. Akrami, **J. Li**, R. M. Leahy,  
"A matched filter decomposition of fMRI into resting and task components",  
*22nd International Conference on Medical Image Computing and Computer-Assisted Intervention*, Shenzhen, China, Sept. 2019, pp. 673--681.  &nbsp; [<i class="fa fa-link"></i>](https://doi.org/10.1007/978-3-030-32248-9_75){:target="Joshi_2019_MICCAI_Matched-LINK"} &nbsp; [<i class="fa fa-file-pdf-o"></i>](/files/pdf/Joshi_2019_MICCAI_Matched.pdf){:target="Joshi_2019_MICCAI_Matched-PDF"} &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/Joshi_2019_MICCAI_Matched.bib)  
  <details>
    <summary style="font-size:16px">Abstract</summary>
      <p style="margin-left: 20px; text-align: justify; font-size:16px">
      The human brain exhibits dynamic interactions among brain regions when responding to stimuli and executing tasks, which can be recorded using functional magnetic resonance imaging (fMRI). Functional MRI signals collected in response to specific tasks consist of a combination of task-related and spontaneous (task-independent) activity. By exploiting the highly structured spatiotemporal patterns of resting state networks, this paper presents a matched-filter approach to decomposing fMRI signals into task and resting-state components. To perform the decomposition, we first use a temporal alignment procedure that is a windowed version of the brainsync transform to synchronize a resting template to the brain's response to tasks. The resulting 'matched filter' removes the components of the fMRI signal that can be described by resting connectivity, leaving the portion of brain activity directly related to tasks. We present a closed-form expression for the windowed synchronization transform that is used by the matched filter. We demonstrate performance of this procedure in application to motor task and language task fMRI data. We show qualitatively and quantitatively that by removing the resting activity, we are able to identify task activated regions in the brain more clearly. Additionally, we show improved prediction accuracy in multivariate pattern analysis when using the matched filtered fMRI data.
      </p>
  </details>

* **J. Li**, J. L. Wisnowski, A. A. Joshi, R. M. Leahy,  
"Brain network identification in asynchronous task fMRI data using robust and scalable tensor decomposition",  
*Proc. SPIE Medical Imaging 2019: Image Processing*, San Diego, CA, Mar. 2019, pp. 164--172.  &nbsp; [<i class="fa fa-link"></i>](https://doi.org/10.1117/12.2512684){:target="Li_2019_SPIEMI_Brain-LINK"} &nbsp; [<i class="fa fa-file-pdf-o"></i>](/files/pdf/Li_2019_SPIEMI_Brain.pdf){:target="Li_2019_SPIEMI_Brain-PDF"} &nbsp; [<i class="fa fa-code"></i>](/software/NASCAR/nascar_main){:target="Li_2019_SPIEMI_Brain-CODE"} &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/Li_2019_SPIEMI_Brain.bib)  
  <details>
    <summary style="font-size:16px">Abstract</summary>
      <p style="margin-left: 20px; text-align: justify; font-size:16px">
      The goal of this work is to robustly identify common brain networks and their corresponding temporal dynamics across subjects in asynchronous task functional MRI (tfMRI) signals. We approached this problem using a robust and scalable tensor decomposition method combined with the BrainSync algorithm. We first used BrainSync algorithm to temporally align asynchronous tfMRI data, allowing us to study common brain networks across subjects. We mapped the synchronized tfMRI data into a 3D tensor (vertices × time × session) and performed a greedy canonical polyadic (CP) decomposition, reducing the rank to 20 in order to improve the signal-to-noise ratio (SNR). We incorporated the Nesterovaccelerated adaptive moment estimation into our previously developed scalable and robust sequential CP decomposition (SRSCPD) framework and applied this improved version of SRSCPD to the rank-reduced tensor to identify dynamic brain networks. We successfully identified 9 brain networks with their corresponding temporal dynamics from 40 subjects using Human Connectome Project tfMRI data without using any prior information with regard to the task designs. Three of these show the subjects’ responses to cues at the beginning of each task block (fronto-parietal attentional control network, visual network and executive control network); one corresponds to the default mode network that exhibits deactivation during the tasks; four show motors networks (left hand, right hand, tongue, and both feet) where the temporal dynamics are strongly correlated to the task designs, and the remaining component reflects physiological noise (respiration).
      </p>
  </details>

* H. Akrami, A. A. Joshi, **J. Li**, R. M. Leahy,  
"Group-wise alignment of resting fMRI in space and time",  
*Proc. SPIE Medical Imaging 2019: Image Processing*, San Diego, CA, Mar. 2019, pp. 737--744.  &nbsp; [<i class="fa fa-link"></i>](https://doi.org/10.1117/12.2512564){:target="Akrami_2019_SPIEMI_Group-LINK"} &nbsp; [<i class="fa fa-file-pdf-o"></i>](/files/pdf/Akrami_2019_SPIEMI_Group.pdf){:target="Akrami_2019_SPIEMI_Group-PDF"} &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/Akrami_2019_SPIEMI_Group.bib)  
  <details>
    <summary style="font-size:16px">Abstract</summary>
      <p style="margin-left: 20px; text-align: justify; font-size:16px">
      Spontaneous brain activity is an important biomarker for various neurological and psychological conditions and can be measured using resting functional Magnetic Resonance Imaging (rfMRI). Since brain activity during resting is spontaneous, it is not possible to directly compare rfMRI time-courses across subjects. Moreover, the spatial configuration of functionally specialized brain regions can vary across subjects throughout the cortex limiting our ability to make precise spatial comparisons. We describe a new approach to jointly align and synchronize fMRI data in space and time, across a group of subjects. We build on previously described methods for inter-subject spatial “Hyper-Alignment” and temporal synchronization through the “BrainSync” transform. We first describe BrainSync Alignment (BSA), a group-based extension of the pair-wise BrainSync transform, that jointly synchronizes resting or task fMRI data across time for multiple subjects. We then explore the combination of BSA with Response Hyper-Alignment (RHA) and compare with Connectivity Hyper-Alignment (CHA), an alternative approach to spatial alignment based on resting fMRI. The result of applying RHA and BSA is both to produce improved functional spatial correspondence across a group of subjects, and to align their time-series so that, even for spontaneous resting data, we see highly correlated temporal dynamics at homologous locations across the group. These spatiotemporally aligned data can then be used as an atlas in future applications. We validate these transfer functions by applying them to z-score maps of an independent dataset and calculating inter-subject correlation. The results show that RHA can be calculated from rfMRI and have comparable output with CHA by leveraging BSA. Moreover, through calculation and application to task fMRI-based spatial transformations on an independent dataset, we show that the combination of RHA and BSA produces improved spatial functional alignment significantly relative to either RHA or CHA alone.
      </p>
  </details>

* A. A. Joshi, **J. Li**, H. Akrami, R. M. Leahy,  
"Predicting cognitive scores from resting fMRI data and geometric features of the brain",  
*Proc. SPIE Medical Imaging 2019: Image Processing*, San Diego, CA, Mar. 2019, pp. 619--625.  &nbsp; [<i class="fa fa-link"></i>](https://doi.org/10.1117/12.2512063){:target="Joshi_2019_SPIEMI_Predicting-LINK"} &nbsp; [<i class="fa fa-file-pdf-o"></i>](/files/pdf/Joshi_2019_SPIEMI_Predicting.pdf){:target="Joshi_2019_SPIEMI_Predicting-PDF"} &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/Joshi_2019_SPIEMI_Predicting.bib)  
  <details>
    <summary style="font-size:16px">Abstract</summary>
      <p style="margin-left: 20px; text-align: justify; font-size:16px">
      Anatomical T1 weighted Magnetic Resonance Imaging (MRI) and functional magnetic resonance imaging collected during resting (rfMRI) are promising markers that offer insight into structure and function of the human brain. The objective of this work is to explore the use of a deep learning neural network to predict cognitive performance scores and ADHD indices in a group of ADHD and control subjects. First, we processed the rfMRI and MRI data of subjects using the BrainSuite fMRI Processing (BFP) pipeline to perform anatomical and functional preprocessing. This produces for each subject fMRI and geometric (anatomical) features represented in a standardized grayordinate system. The geometric and functional cortical data corresponding to the two hemispheres were then transformed to 128x128 multichannel images and input to a convolutional component of the neural network. Subcortical data were presented in a standard vector form and input to a standard input layer of the network. The neural network was implemented in Python using the Keras library with a TensorFlow backend. Training was performed on 168 images with 90 images used for testing. We observed significant correlation between predicted and actual values of the indices tested: Performance IQ: 0.47; Verbal IQ: 0.41, ADHD: 0.57. Comparing these values to those from network trained on functional-only and structural-only data, we saw that rfMRI is more informative than MRI, but the two modalities are highly complementary in terms of predicting these indices.
      </p>
  </details>

### 2018

* A. A. Joshi, **J. Li**, M. Chong, H. Akrami, R. M. Leahy,  
"rfDemons: resting fMRI-based cortical surface registration using the BrainSync transform",  
*21st International Conference on Medical Image Computing and Computer-Assisted Intervention*, Granada, Spain, Sept. 2018, pp. 198--205.  &nbsp; [<i class="fa fa-link"></i>](https://doi.org/10.1007/978-3-030-00931-1_23){:target="Joshi_2018_MICCAI_Rfdemons-LINK"} &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/Joshi_2018_MICCAI_Rfdemons.bib)  
  <details>
    <summary style="font-size:16px">Abstract</summary>
      <p style="margin-left: 20px; text-align: justify; font-size:16px">
      Cross subject functional studies of cerebral cortex require cortical registration that aligns functional brain regions. While cortical folding patterns are approximate indicators of the underlying cytoarchitecture, coregistration based on these features alone does not accurately align functional regions in cerebral cortex. This paper presents a method for cortical surface registration (rfDemons) based on resting fMRI (rfMRI) data that uses curvature-based anatomical registration as an initialization. In contrast to existing techniques that use connectivity-based features derived from rfMRI, the proposed method uses 'synchronized' resting rfMRI time series directly. The synchronization of rfMRI data is performed using the BrainSync transform which applies an orthogonal transform to the rfMRI time series to temporally align them across subjects. The rfDemons method was applied to rfMRI from the Human Connectome Project and evaluated using task fMRI data to explore the impact of cortical registration performed using resting fMRI data on functional alignment of the cerebral cortex.
      </p>
  </details>

* **J. Li**, S. Choi, A. A. Joshi, J. L. Wisnowski, R. M. Leahy,  
"Global PDF-based temporal non-local means filtering reveals individual differences in brain connectivity",  
*IEEE 15th International Symposium on Biomedical Imaging*, Washington D.C., Apr. 2018, pp. 15--19.  &nbsp; [<i class="fa fa-link"></i>](https://doi.org/10.1109/ISBI.2018.8363513){:target="Li_2018_ISBI_Global-LINK"} &nbsp; [<i class="fa fa-file-pdf-o"></i>](/files/pdf/Li_2018_ISBI_Global.pdf){:target="Li_2018_ISBI_Global-PDF"} &nbsp; [<i class="fa fa-code"></i>](/software/GPDF/gpdf_main){:target="Li_2018_ISBI_Global-CODE"} &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/Li_2018_ISBI_Global.bib)  
  <details>
    <summary style="font-size:16px">Abstract</summary>
      <p style="margin-left: 20px; text-align: justify; font-size:16px">
      Characterizing functional brain connectivity using resting fMRI is challenging due to the relatively small BOLD signal contrast and low SNR. Gaussian filtering tends to undermine the individual differences detected by analysis of BOLD signal by smoothing signals across boundaries of different functional areas. Temporal non-local means (tNLM) filtering denoises fMRI data while preserving spatial structures but the kernel and parameters for tNLM filter need to be chosen carefully in order to achieve optimal results. Global PDF-based tNLM filtering (GPDF) is a new, data-dependent optimized kernel function for tNLM filtering which enables us to perform global filtering with improved noise reduction effects without blurring adjacent functional regions.
      </p>
  </details>

### 2017

* **J. Li**, J. C. Mosher, D. R. Nair, J. Gonzalez-Martinez, R. M. Leahy,  
"Robust tensor decomposition of resting brain networks in stereotactic EEG",  
*IEEE 51st Asilomar Conference on Signals, Systems and Computers*, Pacific Grove, CA, Oct. 2017, pp. 1544--1548.  &nbsp; [<i class="fa fa-link"></i>](https://doi.org/10.1109/ACSSC.2017.8335616){:target="Li_2017_ACSSC_Robust-LINK"} &nbsp; [<i class="fa fa-file-pdf-o"></i>](/files/pdf/Li_2017_ACSSC_Robust.pdf){:target="Li_2017_ACSSC_Robust-PDF"} &nbsp; [<i class="fa fa-code"></i>](/software/SRSCPD_ALS/srscpd_als_main){:target="Li_2017_ACSSC_Robust-CODE"} &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/Li_2017_ACSSC_Robust.bib)  
  <details>
    <summary style="font-size:16px">Abstract</summary>
      <p style="margin-left: 20px; text-align: justify; font-size:16px">
      Stereotactically implanted Electro-Encephalography (SEEG) in patients with epilepsy provides a unique insight into spontaneous human brain activity. Exploring dynamic functional connectivity in spontaneous SEEG signals provides a rich framework for studying brain networks. Tensor decomposition is a powerful tool for decoding dynamic networks, capturing the intrinsic interactions between multiple dimensions with less restrictive constraints than traditional 2D matrix decomposition methods such as PCA and ICA. Tensor decomposition, however, is seldom used for decoding large resting brain datasets due to its high computational complexity and poor robustness. In this paper, we describe a Scalable and Robust Sequential Canonical Polyadic Decomposition (SRSCPD) framework that can sequentially and robustly identify tensor models of successively higher rank. We demonstrate that SRSCPD is not only more robust than the popular Alternating Least Square (ALS) algorithm, but can also be extended to large-scale problems.
      </p>
  </details>

* **J. Li**, R. M. Leahy,  
"Parameter selection for optimized non-local means filtering of task fMRI",  
*IEEE 14th International Symposium on Biomedical Imaging*, Melbourne, Australia, Apr. 2017, pp. 476--480.  &nbsp; [<i class="fa fa-link"></i>](https://doi.org/10.1109/ISBI.2017.7950564){:target="Li_2017_ISBI_Parameter-LINK"} &nbsp; [<i class="fa fa-file-pdf-o"></i>](/files/pdf/Li_2017_ISBI_Parameter.pdf){:target="Li_2017_ISBI_Parameter-PDF"} &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/Li_2017_ISBI_Parameter.bib)  
  <details>
    <summary style="font-size:16px">Abstract</summary>
      <p style="margin-left: 20px; text-align: justify; font-size:16px">
      Non-local means (NLM) filtering of fMRI can reduce noise while preserving spatial structure. We have developed a variant called temporal-NLM (tNLM) which uses similarity in time-series between voxels as the basis for computing the weights in the filter. Using tNLM, dynamic fMRI data can be denoised while spatial boundaries between functionally distinct areas in the brain tend to be preserved. The degree of smoothing in tNLM is determined by a parameter h. Here we describe a procedure for selection of h to optimize our ability to differentiate functionally discrete brain regions. We demonstrate the method in application to optimized filtering of task fMRI data.
      </p>
  </details>

### 2012

* A. Kuruvilla, **J. Li**, P. H. Yeomans, P. Quelhas, N. Shaikh, A. Hoberman, J. Kovačević,  
"Otitis media vocabulary and grammar",  
*IEEE 19th International Conference on Image Processing*, Orlando, FL, Oct. 2012, pp. 2845--2848.  &nbsp; [<i class="fa fa-link"></i>](https://doi.org/10.1109/ICIP.2012.6467492){:target="Kuruvilla_2012_ICIP_Otitis-LINK"} &nbsp; [<i class="fa fa-file-pdf-o"></i>](/files/pdf/Kuruvilla_2012_ICIP_Otitis.pdf){:target="Kuruvilla_2012_ICIP_Otitis-PDF"} &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/Kuruvilla_2012_ICIP_Otitis.bib)  
  <details>
    <summary style="font-size:16px">Abstract</summary>
      <p style="margin-left: 20px; text-align: justify; font-size:16px">
      We propose an automated algorithm for classifying diagnostic categories of otitis media (middle ear inflammation); acute otitis media, otitis media with effusion and no effusion. Acute otitis media represents a bacterial superinfection of the middle ear fluid and otitis media with effusion a sterile effusion that tends to subside spontaneously. Diagnosing children with acute otitis media is hard, leading to overprescription of antibiotics that are beneficial only for children with acute otitis media, prompting a need for an accurate and automated algorithm. To that end, we design a feature set understood by both otoscopists and engineers based on the actual visual cues used by otoscopists; we term this otitis media vocabulary. We also design a process to combine the vocabulary terms based on the decision process used by otoscopists; we term this otitis media grammar. The algorithm achieves 84% classification accuracy, in the range or outperforming clinicians who did not receive special training, as well as state-of-the-art classifiers.
      </p>
  </details>
