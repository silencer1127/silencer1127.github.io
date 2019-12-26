### 2019

* A. A. Joshi, H. Akrami, **J. Li**, R. M. Leahy,  
"A matched filter decomposition of fMRI into resting and task components",  
*22nd International Conference on Medical Image Computing and Computer-Assisted Intervention*, Shenzhen, China, Sept. 2019, pp. 673--681.  &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/Joshi2019Amfdofiratc.bib)  
[https://doi.org/10.1007/978-3-030-32248-9_75](https://doi.org/10.1007/978-3-030-32248-9_75){:target="Joshi2019Amfdofiratc"}  
  <details>
    <summary style="font-size:16px">Abstract</summary>
        <p style="margin-left: 20px; text-align: justify; font-size:16px">
        The human brain exhibits dynamic interactions among brain regions when responding to stimuli and executing tasks, which can be recorded using functional magnetic resonance imaging (fMRI). Functional MRI signals collected in response to specific tasks consist of a combination of task-related and spontaneous (task-independent) activity. By exploiting the highly structured spatiotemporal patterns of resting state networks, this paper presents a matched-filter approach to decomposing fMRI signals into task and resting-state components. To perform the decomposition, we first use a temporal alignment procedure that is a windowed version of the brainsync transform to synchronize a resting template to the brain's response to tasks. The resulting 'matched filter' removes the components of the fMRI signal that can be described by resting connectivity, leaving the portion of brain activity directly related to tasks. We present a closed-form expression for the windowed synchronization transform that is used by the matched filter. We demonstrate performance of this procedure in application to motor task and language task fMRI data. We show qualitatively and quantitatively that by removing the resting activity, we are able to identify task activated regions in the brain more clearly. Additionally, we show improved prediction accuracy in multivariate pattern analysis when using the matched filtered fMRI data.
        </p>
  </details>

* **J. Li**, J. L. Wisnowski, A. A. Joshi, R. M. Leahy,  
"Brain network identification in asynchronous task fMRI data using robust and scalable tensor decomposition",  
*Proc. SPIE Medical Imaging 2019: Image Processing*, San Diego, CA, Mar. 2019, pp. 164--172.  &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/Li2019Bniiatfdurastd.bib)  
[https://doi.org/10.1117/12.2512684](https://doi.org/10.1117/12.2512684){:target="Li2019Bniiatfdurastd"}  
  <details>
    <summary style="font-size:16px">Abstract</summary>
        <p style="margin-left: 20px; text-align: justify; font-size:16px">
        The goal of this work is to robustly identify common brain networks and their corresponding temporal dynamics across subjects in asynchronous task functional MRI (tfMRI) signals. We approached this problem using a robust and scalable tensor decomposition method combined with the BrainSync algorithm. We first used BrainSync algorithm to temporally align asynchronous tfMRI data, allowing us to study common brain networks across subjects. We mapped the synchronized tfMRI data into a 3D tensor (vertices × time × session) and performed a greedy canonical polyadic (CP) decomposition, reducing the rank to 20 in order to improve the signal-to-noise ratio (SNR). We incorporated the Nesterovaccelerated adaptive moment estimation into our previously developed scalable and robust sequential CP decomposition (SRSCPD) framework and applied this improved version of SRSCPD to the rank-reduced tensor to identify dynamic brain networks. We successfully identified 9 brain networks with their corresponding temporal dynamics from 40 subjects using Human Connectome Project tfMRI data without using any prior information with regard to the task designs. Three of these show the subjects’ responses to cues at the beginning of each task block (fronto-parietal attentional control network, visual network and executive control network); one corresponds to the default mode network that exhibits deactivation during the tasks; four show motors networks (left hand, right hand, tongue, and both feet) where the temporal dynamics are strongly correlated to the task designs, and the remaining component reflects physiological noise (respiration).
        </p>
  </details>

* H. Akrami, A. A. Joshi, **J. Li**, R. M. Leahy,  
"Group-wise alignment of resting fMRI in space and time",  
*Proc. SPIE Medical Imaging 2019: Image Processing*, San Diego, CA, Mar. 2019, pp. 737--744.  &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/Akrami2019Gaorfisat.bib)  
[https://doi.org/10.1117/12.2512564](https://doi.org/10.1117/12.2512564){:target="Akrami2019Gaorfisat"}  
  <details>
    <summary style="font-size:16px">Abstract</summary>
        <p style="margin-left: 20px; text-align: justify; font-size:16px">
        Spontaneous brain activity is an important biomarker for various neurological and psychological conditions and can be measured using resting functional Magnetic Resonance Imaging (rfMRI). Since brain activity during resting is spontaneous, it is not possible to directly compare rfMRI time-courses across subjects. Moreover, the spatial configuration of functionally specialized brain regions can vary across subjects throughout the cortex limiting our ability to make precise spatial comparisons. We describe a new approach to jointly align and synchronize fMRI data in space and time, across a group of subjects. We build on previously described methods for inter-subject spatial “Hyper-Alignment” and temporal synchronization through the “BrainSync” transform. We first describe BrainSync Alignment (BSA), a group-based extension of the pair-wise BrainSync transform, that jointly synchronizes resting or task fMRI data across time for multiple subjects. We then explore the combination of BSA with Response Hyper-Alignment (RHA) and compare with Connectivity Hyper-Alignment (CHA), an alternative approach to spatial alignment based on resting fMRI. The result of applying RHA and BSA is both to produce improved functional spatial correspondence across a group of subjects, and to align their time-series so that, even for spontaneous resting data, we see highly correlated temporal dynamics at homologous locations across the group. These spatiotemporally aligned data can then be used as an atlas in future applications. We validate these transfer functions by applying them to z-score maps of an independent dataset and calculating inter-subject correlation. The results show that RHA can be calculated from rfMRI and have comparable output with CHA by leveraging BSA. Moreover, through calculation and application to task fMRI-based spatial transformations on an independent dataset, we show that the combination of RHA and BSA produces improved spatial functional alignment significantly relative to either RHA or CHA alone.
        </p>
  </details>

* A. A. Joshi, **J. Li**, H. Akrami, R. M. Leahy,  
"Predicting cognitive scores from resting fMRI data and geometric features of the brain",  
*Proc. SPIE Medical Imaging 2019: Image Processing*, San Diego, CA, Mar. 2019, pp. 619--625.  &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/Joshi2019Pcsfrfdagfotb.bib)  
[https://doi.org/10.1117/12.2512063](https://doi.org/10.1117/12.2512063){:target="Joshi2019Pcsfrfdagfotb"}  
  <details>
    <summary style="font-size:16px">Abstract</summary>
        <p style="margin-left: 20px; text-align: justify; font-size:16px">
        Anatomical T1 weighted Magnetic Resonance Imaging (MRI) and functional magnetic resonance imaging collected during resting (rfMRI) are promising markers that offer insight into structure and function of the human brain. The objective of this work is to explore the use of a deep learning neural network to predict cognitive performance scores and ADHD indices in a group of ADHD and control subjects. First, we processed the rfMRI and MRI data of subjects using the BrainSuite fMRI Processing (BFP) pipeline to perform anatomical and functional preprocessing. This produces for each subject fMRI and geometric (anatomical) features represented in a standardized grayordinate system. The geometric and functional cortical data corresponding to the two hemispheres were then transformed to 128x128 multichannel images and input to a convolutional component of the neural network. Subcortical data were presented in a standard vector form and input to a standard input layer of the network. The neural network was implemented in Python using the Keras library with a TensorFlow backend. Training was performed on 168 images with 90 images used for testing. We observed significant correlation between predicted and actual values of the indices tested: Performance IQ: 0.47; Verbal IQ: 0.41, ADHD: 0.57. Comparing these values to those from network trained on functional-only and structural-only data, we saw that rfMRI is more informative than MRI, but the two modalities are highly complementary in terms of predicting these indices.
        </p>
  </details>

### 2018

* A. A. Joshi, **J. Li**, M. Chong, H. Akrami, R. M. Leahy,  
"rfDemons: resting fMRI-based cortical surface registration using the BrainSync transform",  
*21st International Conference on Medical Image Computing and Computer-Assisted Intervention*, Granada, Spain, Sept. 2018, pp. 198--205.  &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/Joshi2018rrfcsrutBt.bib)  
[https://doi.org/10.1007/978-3-030-00931-1_23](https://doi.org/10.1007/978-3-030-00931-1_23){:target="Joshi2018rrfcsrutBt"}  
  <details>
    <summary style="font-size:16px">Abstract</summary>
        <p style="margin-left: 20px; text-align: justify; font-size:16px">
        Cross subject functional studies of cerebral cortex require cortical registration that aligns functional brain regions. While cortical folding patterns are approximate indicators of the underlying cytoarchitecture, coregistration based on these features alone does not accurately align functional regions in cerebral cortex. This paper presents a method for cortical surface registration (rfDemons) based on resting fMRI (rfMRI) data that uses curvature-based anatomical registration as an initialization. In contrast to existing techniques that use connectivity-based features derived from rfMRI, the proposed method uses 'synchronized' resting rfMRI time series directly. The synchronization of rfMRI data is performed using the BrainSync transform which applies an orthogonal transform to the rfMRI time series to temporally align them across subjects. The rfDemons method was applied to rfMRI from the Human Connectome Project and evaluated using task fMRI data to explore the impact of cortical registration performed using resting fMRI data on functional alignment of the cerebral cortex.
        </p>
  </details>

* **J. Li**, S. Choi, A. A. Joshi, J. L. Wisnowski, R. M. Leahy,  
"Global PDF-based temporal non-local means filtering reveals individual differences in brain connectivity",  
*IEEE 15th International Symposium on Biomedical Imaging*, Washington D.C., Apr. 2018, pp. 15--19.  &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/Li2018GPtnmfridibc.bib) &nbsp; [<i class="fa fa-code"></i>](/software/GPDF/gpdf_main){:target="Li2018GPtnmfridibc-CODE"}  
[https://doi.org/10.1109/ISBI.2018.8363513](https://doi.org/10.1109/ISBI.2018.8363513){:target="Li2018GPtnmfridibc"}  
  <details>
    <summary style="font-size:16px">Abstract</summary>
        <p style="margin-left: 20px; text-align: justify; font-size:16px">
        Characterizing functional brain connectivity using resting fMRI is challenging due to the relatively small BOLD signal contrast and low SNR. Gaussian filtering tends to undermine the individual differences detected by analysis of BOLD signal by smoothing signals across boundaries of different functional areas. Temporal non-local means (tNLM) filtering denoises fMRI data while preserving spatial structures but the kernel and parameters for tNLM filter need to be chosen carefully in order to achieve optimal results. Global PDF-based tNLM filtering (GPDF) is a new, data-dependent optimized kernel function for tNLM filtering which enables us to perform global filtering with improved noise reduction effects without blurring adjacent functional regions.
        </p>
  </details>

### 2017

* **J. Li**, J. C. Mosher, D. R. Nair, J. Gonzalez-Martinez, R. M. Leahy,  
"Robust tensor decomposition of resting brain networks in stereotactic EEG",  
*IEEE 51st Asilomar Conference on Signals, Systems and Computers*, Pacific Grove, CA, Oct. 2017, pp. 1544--1548.  &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/Li2017RtdorbnisE.bib) &nbsp; [<i class="fa fa-code"></i>](/software/SRSCPD_ALS/srscpd_als_main){:target="Li2017RtdorbnisE-CODE"}  
[https://doi.org/10.1109/ACSSC.2017.8335616](https://doi.org/10.1109/ACSSC.2017.8335616){:target="Li2017RtdorbnisE"}  
  <details>
    <summary style="font-size:16px">Abstract</summary>
        <p style="margin-left: 20px; text-align: justify; font-size:16px">
        Stereotactically implanted Electro-Encephalography (SEEG) in patients with epilepsy provides a unique insight into spontaneous human brain activity. Exploring dynamic functional connectivity in spontaneous SEEG signals provides a rich framework for studying brain networks. Tensor decomposition is a powerful tool for decoding dynamic networks, capturing the intrinsic interactions between multiple dimensions with less restrictive constraints than traditional 2D matrix decomposition methods such as PCA and ICA. Tensor decomposition, however, is seldom used for decoding large resting brain datasets due to its high computational complexity and poor robustness. In this paper, we describe a Scalable and Robust Sequential Canonical Polyadic Decomposition (SRSCPD) framework that can sequentially and robustly identify tensor models of successively higher rank. We demonstrate that SRSCPD is not only more robust than the popular Alternating Least Square (ALS) algorithm, but can also be extended to large-scale problems.
        </p>
  </details>

* **J. Li**, R. M. Leahy,  
"Parameter selection for optimized non-local means filtering of task fMRI",  
*IEEE 14th International Symposium on Biomedical Imaging*, Melbourne, Australia, Apr. 2017, pp. 476--480.  &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/Li2017Psfonmfotf.bib)  
[https://doi.org/10.1109/ISBI.2017.7950564](https://doi.org/10.1109/ISBI.2017.7950564){:target="Li2017Psfonmfotf"}  
  <details>
    <summary style="font-size:16px">Abstract</summary>
        <p style="margin-left: 20px; text-align: justify; font-size:16px">
        Non-local means (NLM) filtering of fMRI can reduce noise while preserving spatial structure. We have developed a variant called temporal-NLM (tNLM) which uses similarity in time-series between voxels as the basis for computing the weights in the filter. Using tNLM, dynamic fMRI data can be denoised while spatial boundaries between functionally distinct areas in the brain tend to be preserved. The degree of smoothing in tNLM is determined by a parameter h. Here we describe a procedure for selection of h to optimize our ability to differentiate functionally discrete brain regions. We demonstrate the method in application to optimized filtering of task fMRI data.
        </p>
  </details>

### 2012

* A. Kuruvilla, **J. Li**, P. H. Yeomans, P. Quelhas, N. Shaikh, A. Hoberman, J. Kovačević,  
"Otitis media vocabulary and grammar",  
*IEEE 19th International Conference on Image Processing*, Orlando, FL, Oct. 2012, pp. 2845--2848.  &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/Kuruvilla2012Omvag.bib)  
[https://doi.org/10.1109/ICIP.2012.6467492](https://doi.org/10.1109/ICIP.2012.6467492){:target="Kuruvilla2012Omvag"}  
  <details>
    <summary style="font-size:16px">Abstract</summary>
        <p style="margin-left: 20px; text-align: justify; font-size:16px">
        We propose an automated algorithm for classifying diagnostic categories of otitis media (middle ear inflammation); acute otitis media, otitis media with effusion and no effusion. Acute otitis media represents a bacterial superinfection of the middle ear fluid and otitis media with effusion a sterile effusion that tends to subside spontaneously. Diagnosing children with acute otitis media is hard, leading to overprescription of antibiotics that are beneficial only for children with acute otitis media, prompting a need for an accurate and automated algorithm. To that end, we design a feature set understood by both otoscopists and engineers based on the actual visual cues used by otoscopists; we term this otitis media vocabulary. We also design a process to combine the vocabulary terms based on the decision process used by otoscopists; we term this otitis media grammar. The algorithm achieves 84% classification accuracy, in the range or outperforming clinicians who did not receive special training, as well as state-of-the-art classifiers.
        </p>
  </details>