---
title: "Publications"
category: "main"
permalink: /pub/
layout: single
author_profile: true
date: 2019-01-11
---

{% comment %}
[<i class="ai ai-google-scholar-square"></i> Google Scholar Page](https://scholar.google.com/citations?user=1GqG2q8AAAAJ){:.pub_ext}{:#pub_google_scholar}{:target="google_scholar"}
{% endcomment %}

<br/>
Authors marked with \* are co-first authors that contributed to the work equally.

## Journal Publications

{% comment %}

* GPDF, TMI
* EZF 2, brain
* Tensor fMRI, neuroimage

{% endcomment %}

* **J. Li**, S. E. Luczak, I. G. Rosen,  
Comparing a distributed parameter model-based system identification technique with more conventional methods for inverse problems,  
Journal of Inverse and Ill-posed Problems, 2019. (In press)
	<details>
		<summary>Abstract</summary>
			<p style="margin-left: 20px; text-align: justify; font-size:16px">
			Three methods for the estimation of blood or breath alcohol concentration (BAC/BrAC) from biosensor measured transdermal alcohol concentration (TAC) are evaluated and compared. Specifically, we consider a system identification/quasi-blind deconvolution scheme based on a distributed parameter model with unbounded input and output for ethanol transport in the skin and compare it to two more conventional system identification and filtering/deconvolution techniques for ill-posed inverse problems, one based on frequency domain methods, and the other on a time series approach using an ARMA input/output model. Our basis for comparison are five statistical measures of interest to alcohol researchers and clinicians: peak BAC/BrAC, time of peak BAC/BrAC, the ascending and descending slopes of the BAC/BrAC curve, and the area underneath the BAC/BrAC curve.
			</p>
	</details>

* **J. Li**, J. P. Haldar, J. C. Mosher, D. R. Nair, J. Gonźalez-Martinez, R. M. Leahy,  
[Scalable and robust tensor decomposition for brain network identification in spontaneous stereotactic EEG data](https://doi.org/10.1109/TBME.2018.2875467){:.pub_j_web}{:#pub_tbme_2018_srscpd_web}{:target="pub_tbme_2018_srscpd_web"},  
IEEE Transactions on Biomedical Engineering, 2018. (In press) &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/tbme_2018_srscpd.bib) &nbsp; [<i class="fa fa-code"></i>](/software/SRSCPD_ALS/srscpd_als_main)
	<details>
		<summary>Abstract</summary>
			<p style="margin-left: 20px; text-align: justify; font-size:16px">
			Objective: Identification of networks from resting brain signals is an important step in understanding the dynamics of spontaneous brain activity. We approach this problem using a tensor-based model. Methods: We develop a rank-recursive Scalable and Robust Sequential Canonical Polyadic Decomposition (SRSCPD) framework to decompose a tensor into several rank-1 components. Robustness and scalability are achieved using a warm start for each rank based on the results from the previous rank. Results: In simulations we show that SRSCPD consistently outperforms the multi-start alternating least square (ALS) algorithm over a range of ranks and signal-to-noise ratios (SNRs), with lower computation cost. When applying SRSCPD to resting in-vivo stereotactic EEG (SEEG) data from two subjects with epilepsy, we found components corresponding to default mode and motor networks in both subjects. These components were also highly consistent within subject between two sessions recorded several hours apart. Similar components were not obtained using the conventional ALS algorithm. Conclusion: Consistent brain networks and their dynamic behaviors were identified from resting SEEG data using SRSCPD. Significance: SRSCPD is scalable to large datasets and therefore a promising tool for identification of brain networks in long recordings from single subjects.
			</p>
	</details>

* E. Cvetkovska, W. A. Martins, J. Gonźalez-Martinez, K. Taylor, **J. Li**, O. Grinenko, J. C. Mosher, R. M. Leahy, P. Chauvel, D. Nair,  
[Heterotopia or overlaying cortex: what about in-between?](https://doi.org/10.1016/j.ebcr.2018.09.007){:.pub_j_web}{:#pub_ebcr_2018_heterotopia_web}{:target="pub_ebcr_2018_heterotopia_web"},  
Epilepsy & Behavior Case Reports, vol. 11, pp. 4-9, 2018. &nbsp; [<i class="fa fa-file-pdf-o"></i>](/files/pdf/ebcr_2018_pnh.pdf){:.pub_j_pdf}{:#pub_ebcr_2018_pnh_pdf}{:target="pub_ebcr_2018_pnh_pdf"} &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/ebcr_2018_heterotopia.bib) 
	<details>
		<summary>Abstract</summary>
			<p style="margin-left: 20px; text-align: justify; font-size:16px">
			We describe a patient with unilateral periventricular nodular heterotopia (PNH) and drug-resistant epilepsy, whose SEEG revealed that seizures were arising from the PNH, with the almost simultaneous involvement of heterotopic neurons (“micronodules”) scattered within the white matter, and subsequently the overlying cortex. Laser ablation of heterotopic nodules and the adjacent white matter rendered the patient seizure free.<br>
			This case elucidates that “micronodules” scattered in white matter between heterotopic nodules and overlying cortex might be another contributor in complex epileptogenicity of heterotopia. Detecting patient-specific targets in the epileptic network of heterotopia creates the possibility to disrupt the pathological circuit by minimally invasive procedures.
			</p>
	</details>

* A. A. Joshi, M. Chong, **J. Li**, S. Y. Choi, R. M. Leahy,  
[Are you thinking what I'm thinking? Synchronization of resting fMRI time-series across subjects](https://doi.org/10.1016/j.neuroimage.2018.01.058){:.pub_j_web}{:#pub_neuroimage_2017_brainsync_web}{:target="pub_neuroimage_2017_brainsync_web"},  
Neuroimage, vol. 172, pp. 740-752, 2018. &nbsp; [<i class="fa fa-file-pdf-o"></i>](/files/pdf/neuroimage_2018_brainsync.pdf){:.pub_j_pdf}{:#pub_neuroimage_2017_brainsync_pdf}{:target="pub_neuroimage_2017_brainsync_pdf"} &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/neuroimage_2018_brainsync.bib)
	<details>
		<summary>Abstract</summary>
			<p style="margin-left: 20px; text-align: justify; font-size:16px">
			We describe BrainSync, an orthogonal transform that allows direct comparison of resting fMRI (rfMRI) time-series across subjects. For this purpose, we exploit the geometry of the rfMRI signal space to propose a novel orthogonal transformation that synchronizes rfMRI time-series across sessions and subjects. When synchronized, rfMRI signals become approximately equal at homologous locations across subjects. The method is based on the observation that rfMRI data exhibit similar connectivity patterns across subjects, as reflected in the pairwise correlations between different brain regions. We show that if the data for two subjects have similar correlation patterns then their time courses can be approximately synchronized by an orthogonal transformation. This transform is unique, invertible, efficient to compute, and preserves the connectivity structure of the original data for all subjects. Analogously to image registration, where we spatially align structural brain images, this temporal synchronization of brain signals across a population, or within-subject across sessions, facilitates cross-sectional and longitudinal studies of rfMRI data. The utility of the BrainSync transform is illustrated through demonstrative simulations and applications including quantification of rfMRI variability across subjects and sessions, cortical functional parcellation across a population, timing recovery in task fMRI data, comparison of task and resting state data, and an application to complex naturalistic stimuli for annotation prediction.
			</p>
	</details>

* O. Grinenko<sup>\*</sup>, **J. Li**<sup>\*</sup>, J. C. Mosher, Z. Wang, J. Bulacio, J. Gonźalez-Martinez, D. Nair, I. Najm, R. M. Leahy, P. Chauvel,  
[A fingerprint of the epileptogenic zone in human epilepsies](https://doi.org/10.1093/brain/awx306){:.pub_j_web}{:#pub_brain_2017_fingerprint_web}{:target="pub_brain_2017_fingerprint_web"},  
Brain, vol. 141, no. 1, pp. 117-131, 2018. &nbsp; [<i class="fa fa-file-pdf-o"></i>](/files/pdf/brain_2017_fingerprint.pdf){:.pub_j_pdf}{:#pub_brain_2017_fingerprint_pdf}{:target="pub_brain_2017_fingerprint_pdf"} &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/brain_2017_fingerprint.bib) &nbsp; [<i class="fa fa-code"></i>](/software/EZ_Fingerprint/ezf_main)
	<details>
		<summary>Abstract</summary>
			<p style="margin-left: 20px; text-align: justify; font-size:16px">
			Defining a bio-electrical marker for the brain area responsible for initiating a seizure remains an unsolved problem. Fast gamma activity has been identified as the most specific marker for seizure onset, but conflicting results have been reported. In this study, we describe an alternative marker, based on an objective description of interictal to ictal transition, with the aim of identifying a time-frequency pattern or 'fingerprint' that can differentiate the epileptogenic zone from areas of propagation. Seventeen patients who underwent stereoelectroencephalography were included in the study. Each had seizure onset characterized by sustained gamma activity and were seizure-free after tailored resection or laser ablation. We postulated that the epileptogenic zone was always located inside the resection region based on seizure freedom following surgery. To characterize the ictal frequency pattern, we applied the Morlet wavelet transform to data from each pair of adjacent intracerebral electrode contacts. Based on a visual assessment of the time-frequency plots, we hypothesized that a specific time-frequency pattern in the epileptogenic zone should include a combination of (i) sharp transients or spikes; preceding (ii) multiband fast activity concurrent; with (iii) suppression of lower frequencies. To test this hypothesis, we developed software that automatically extracted each of these features from the time-frequency data. We then used a support vector machine to classify each contact-pair as being within epileptogenic zone or not, based on these features. Our machine learning system identified this pattern in 15 of 17 patients. The total number of identified contacts across all patients was 64, with 58 localized inside the resected area. Subsequent quantitative analysis showed strong correlation between maximum frequency of fast activity and suppression inside the resection but not outside. We did not observe significant discrimination power using only the maximum frequency or the timing of fast activity to differentiate contacts either between resected and non-resected regions or between contacts identified as epileptogenic versus non-epileptogenic. Instead of identifying a single frequency or a single timing trait, we observed the more complex pattern described above that distinguishes the epileptogenic zone. This pattern encompasses interictal to ictal transition and may extend until seizure end. Its time-frequency characteristics can be explained in light of recent models emphasizing the role of fast inhibitory interneurons acting on pyramidal cells as a prominent mechanism in seizure triggering. The pattern clearly differentiates the epileptogenic zone from areas of propagation and, as such, represents an epileptogenic zone 'fingerprint'.
			</p>
	</details>

## Conference Proceedings

{% comment %}

* S. Choi, A. A. Joshi, C. Vu, **J. Li**, S. O'Niel, J. C. Wood, R. M. Leahy,  
Detecting alterations of brain connectivity in anemic subjects using fMRI under hypoxic and hyperoxic conditions,  
25th Annual Meeting of the Organization for Human Brain Mapping (OHBM), Rome, 2019.

* A. A. Joshi, **J. Li**, H. Akrami, R. M. Leahy,  
A matched filter decomposition of task fmri for extraction of dynamical components,  
25th Annual Meeting of the Organization for Human Brain Mapping (OHBM), Rome, 2019.

{% endcomment %}

* **J. Li**, J. L. Wisnowski, A. A. Joshi, R. M. Leahy,  
Brain network identification in asynchronous task fMRI data using robust and scalable tensor decomposition,  
Proc. SPIE Medical Imaging: Image Processing, San Diego, 2019 (In press)

* A. A. Joshi, **J. Li**, H. Akrami, R. M. Leahy,  
Predicting cognitive scores from resting fMRI data and geometric features,  
Proc. SPIE Medical Imaging: Image Processing, San Diego, 2019. (In press)

* H. Akrami, A. A. Joshi, **J. Li**, R. M. Leahy,  
Group-wise alignment of resting fMRI in space and time,  
Proc. SPIE Medical Imaging: Image Processing, San Diego, 2019 (In press)

* O. Grinenko<sup>\*</sup>, **J. Li**<sup>\*</sup>, J. C. Mosher, J. Bulacio, J. Gonźalez-Martinez, I. Najm, P. Chauvel, R. M. Leahy,  
[In search of biomarkers for the epileptogenic zone: A machine learning approach](https://www.aesnet.org/meetings_events/annual_meeting_abstracts/view/502570){:.pub_c_web}{:#pub_aes_2019_ezfmri_web}{:target="pub_aes_2019_ezfmri_web"},  
72nd Annual Meeting of the American Epilepsy Society, New Orleans, 2018.

* A. A. Joshi, **J. Li**, M. Chong, H. Akrami, R. M. Leahy,  
[rfDemons: resting fMRI-based cortical surface registration using BrainSync transform](https://doi.org/10.1007/978-3-030-00931-1_23){:.pub_c_web}{:#pub_miccai_2018_rfdemons_web}{:target="pub_rmiccai_2018_rfdemons_web"},  
21st International Conference on Medical Image Computing and Computer-Assisted Intervention (MICCAI), Granada, 2018. &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/miccai_2018_rfdemons.bib)
	<details>
		<summary>Abstract</summary>
			<p style="margin-left: 20px; text-align: justify; font-size:16px">
			Cross subject functional studies of cerebral cortex require cortical registration that aligns functional brain regions. While cortical folding patterns are approximate indicators of the underlying cytoarchitecture, coregistration based on these features alone does not accurately align functional regions in cerebral cortex. This paper presents a method for cortical surface registration (rfDemons) based on resting fMRI (rfMRI) data that uses curvature-based anatomical registration as an initialization. In contrast to existing techniques that use connectivity-based features derived from rfMRI, the proposed method uses ‘synchronized’ resting rfMRI time series directly. The synchronization of rfMRI data is performed using the BrainSync transform which applies an orthogonal transform to the rfMRI time series to temporally align them across subjects. The rfDemons method was applied to rfMRI from the Human Connectome Project and evaluated using task fMRI data to explore the impact of cortical registration performed using resting fMRI data on functional alignment of the cerebral cortex.
			</p>
	</details>

* **J. Li**, J. L. Wisnowski, A. A. Joshi, R. M. Leahy,  
[Identifying brain networks using tensor decomposition of multiple subject asynchronous task fMRI](https://ww5.aievolution.com/hbm1801/index.cfm?do=abs.viewAbs&abs=2867){:.pub_c_web}{:#pub_ohbm_2018_srscpd_fmri_web}{:target="pub_ohbm_2018_srscpd_fmri_web"},  
24th Annual Meeting of the Organization for Human Brain Mapping (OHBM), Singapore, 2018. &nbsp; [<i class="fa fa-file-pdf-o"></i>](/files/pdf/ohbm_2018_srscpd_fmri.pdf){:.pub_c_pdf}{:#pub_ohbm_2018_srscpd_fmri_pdf}{:target="pub_ohbm_2018_srscpd_fmri_pdf"} &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/ohbm_2018_srscpd_fmri.bib)

* H. Akrami, A. A. Joshi, **J. Li**, R. M. Leahy,  
[Average template for comparison of resting fMRI based on group synchronization of their time series](https://ww5.aievolution.com/hbm1801/index.cfm?do=abs.viewAbs&abs=1807){:.pub_c_web}{:#pub_ohbm_2018_fmri_atlas_web}{:target="pub_ohbm_2018_fmri_atlas_web"},  
24th Annual Meeting of the Organization for Human Brain Mapping (OHBM), Singapore, 2018. &nbsp; [<i class="fa fa-file-pdf-o"></i>](/files/pdf/ohbm_2018_fmri_atlas.pdf){:.pub_c_pdf}{:#pub_ohbm_2018_fmri_atlas_pdf}{:target="pub_ohbm_2018_fmri_atlas_pdf"} &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/ohbm_2018_fmri_atlas.bib)

* A. A. Joshi, D. McCoy, M. Chong, **J. Li**, S. Y. Choi, D. Shattuck, R. M. Leahy,  
[BFP: BrainSuite fMRI pipeline](https://ww5.aievolution.com/hbm1801/index.cfm?do=abs.viewAbs&abs=1422){:.pub_c_web}{:#pub_ohbm_2018_bfp_web}{:target="pub_ohbm_2018_bfp_web"},
24th Annual Meeting of the Organization for Human Brain Mapping (OHBM), Singapore, 2018. &nbsp; [<i class="fa fa-file-pdf-o"></i>](/files/pdf/ohbm_2018_bfp.pdf){:.pub_c_pdf}{:#pub_ohbm_2018_bfp_pdf}{:target="pub_ohbm_2018_bfp_pdf"} &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/ohbm_2018_bfp.bib)

* **J. Li**, S. Y. Choi, A. A. Joshi, J. L. Wisnowski, R. M. Leahy,  
[Global PDF-based temporal non-local means filtering reveals individual differences of brain connectivity](https://doi.org/10.1109/ISBI.2018.8363513){:.pub_c_web}{:#pub_isbi_2018_gpdf_web}{:target="pub_isbi_2018_gpdf_web"},  
IEEE 15th International Symposium on Biomedical Imaging (ISBI), Washington D.C., 2018. &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/isbi_2018_gpdf.bib) &nbsp; [<i class="fa fa-code"></i>](/software/GPDF/gpdf_main)
	<details>
		<summary>Abstract</summary>
			<p style="margin-left: 20px; text-align: justify; font-size:16px">
			Characterizing functional brain connectivity using resting fMRI is challenging due to the relatively small BOLD signal contrast and low SNR. Gaussian filtering tends to undermine the individual differences detected by analysis of BOLD signal by smoothing signals across boundaries of different functional areas. Temporal non-local means (tNLM) filtering denoises fMRI data while preserving spatial structures but the kernel and parameters for tNLM filter need to be chosen carefully in order to achieve optimal results. Global PDF-based tNLM filtering (GPDF) is a new, data-dependent optimized kernel function for tNLM filtering which enables us to perform global filtering with improved noise reduction effects without blurring adjacent functional regions.
			</p>
	</details>

* **J. Li**, J. C. Mosher, D. Nair, J. Gonźalez-Martinez, R. M. Leahy,  
[Robust tensor decomposition of resting brain networks in stereotactic EEG](https://doi.org/10.1109/ACSSC.2017.8335616){:.pub_c_web}{:#pub_asilomar_2017_srscpd_web}{:target="pub_asilomar_2017_srscpd_web"},  
IEEE 51st Asilomar Conference on Signal, System and Computers, Pacific Grove, 2017. &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/asilomar_2017_srscpd.bib) &nbsp; [<i class="fa fa-code"></i>](/software/SRSCPD_ALS/srscpd_als_main)
	<details>
		<summary>Abstract</summary>
			<p style="margin-left: 20px; text-align: justify; font-size:16px">
			Stereotactically implanted Electro-Encephalography (SEEG) in patients with epilepsy provides a unique insight into spontaneous human brain activity. Exploring dynamic functional connectivity in spontaneous SEEG signals provides a rich framework for studying brain networks. Tensor decomposition is a powerful tool for decoding dynamic networks, capturing the intrinsic interactions between multiple dimensions with less restrictive constraints than traditional 2D matrix decomposition methods such as PCA and ICA. Tensor decomposition, however, is seldom used for decoding large resting brain datasets due to its high computational complexity and poor robustness. In this paper, we describe a Scalable and Robust Sequential Canonical Polyadic Decomposition (SRSCPD) framework that can sequentially and robustly identify tensor models of successively higher rank. We demonstrate that SRSCPD is not only more robust than the popular Alternating Least Square (ALS) algorithm, but can also be extended to large-scale problems.
			</p>
	</details>

* **J. Li**, S. E. Luczak, I. G. Rosen,  
[On the modeling and deconvolution of blood or breath alcohol concentration (BrAC/BAC) from biosensor-measured transdermal alcohol concentration (TAC)](https://doi.org/10.1111/acer.13391){:.pub_c_web}{:#pub_rsa_2017_alcohol_web}{:target="pub_rsa_2017_alcohol_web"},  
40th Annual Meeting of the Research Society on Alcoholism (RSA), Denver, 2017. &nbsp; [<i class="fa fa-file-pdf-o"></i>](/files/pdf/rsa_2017_alcohol.pdf){:.pub_c_pdf}{:#pub_rsa_2017_alcohol_pdf}{:target="pub_rsa_2017_alcohol_pdf"} &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/rsa_2017_alcohol.bib)
	<details>
		<summary>Abstract</summary>
			<p style="margin-left: 20px; text-align: justify; font-size:16px">
			New technology has produced biosensors that measure transdermal alcohol concentration (TAC) in naturalistic settings. However, due to several physiological and environmental factors, no direct conversion from TAC to BAC/BrAC exists. The skin's transport and filtering of alcohol is physiologically complex and is affected by numerous factors that vary across individuals (e.g., skin layer thickness, porosity, tortuosity) and drinking episodes within individuals (e.g., skin surface, ambient temperature, hydration, vasodilation). TAC readings also depend on the particular device used to collect the data. In earlier work, we developed a mathematical framework and protocol for calibrating BrAC and TAC data for a single drinking episode that captured the dynamics of the forward process and then inverted the resulting fit model by deconvolving estimated BrAC from TAC for subsequent drinking episodes. In this study, we compare three methods for implementing this approach. Method 1 is frequency domain‐based wherein the forward convolution filter is taken to be the low pass filtered inverse Fourier transform of the quotient of the Fourier transforms of the calibration TAC and BrAC. In Method 2, the convolution filter is determined as the impulse response function of an auto regressive/moving average (ARMA) model fit to the calibration episode. In Method 3, the filter is determined via finite dimensional approximation of the linear semigroup‐based mild solution of a distributed parameter model with unbounded input and output fit to the calibration data. In tests using contemporaneous TAC and BrAC field data, we examined model fit indices and summary BrAC scores and curves. Results indicated Method 2 yielded the most accurate estimate of peak BrAC and Method 3 yielded the best estimate of time of peak BrAC. Method 1 had the smallest variance across episodes, in particular for estimating ascending and descending slopes, but had slightly larger bias. Method 1 is computationally efficient but theoretically is estimating infinitely many parameters. Method 3 estimates only two parameters but required more computational time to fit the data. Method 2 was between Method 1 and Method 3 in terms of computational efficiency and degrees of freedom. Future research will compare these methods when incorporated into learning algorithms. This research was supported by NIH grant R01AA17711.
			</p>
	</details>

* **J. Li**, S. Y. Choi, R. M. Leahy,  
Global PDF-based non-local means filtering of resting fMRI data,  
23rd Annual Meeting of the Organization for Human Brain Mapping (OHBM), Vancouver, 2017. &nbsp; [<i class="fa fa-file-pdf-o"></i>](/files/pdf/ohbm_2017_gpdf.pdf){:.pub_c_pdf}{:#pub_ohbm_2017_gpdf_pdf}{:target="pub_ohbm_2017_gpdf_pdf"} &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/ohbm_2017_gpdf.bib) &nbsp; [<i class="fa fa-code"></i>](/software/GPDF/gpdf_main)

* **J. Li**, R. M. Leahy,  
[Parameter selection for optimized non-local means filtering of task fMRI](https://doi.org/10.1109/ISBI.2017.7950564){:.pub_c_web}{:#pub_isbi_2017_tnlm_web}{:target="pub_isbi_2017_tnlm_web"},  
IEEE 14th International Symposium on Biomedical Imaging (ISBI), pp. 476-480, Melbourne, 2017. &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/isbi_2017_tnlm.bib)
	<details>
		<summary>Abstract</summary>
			<p style="margin-left: 20px; text-align: justify; font-size:16px">
			Non-local means (NLM) filtering of fMRI can reduce noise while preserving spatial structure. We have developed a variant called temporal-NLM (tNLM) which uses similarity in time-series between voxels as the basis for computing the weights in the filter. Using tNLM, dynamic fMRI data can be denoised while spatial boundaries between functionally distinct areas in the brain tend to be preserved. The degree of smoothing in tNLM is determined by a parameter h. Here we describe a procedure for selection of h to optimize our ability to differentiate functionally discrete brain regions. We demonstrate the method in application to optimized filtering of task fMRI data.
			</p>
	</details>

* A. Kuruvilla, **J. Li**, P. H. Yeomans, P. Quelhas, N. Shaikh, A. Hoberman, and J. Kovačević,  
[Otitis media vocabulary and grammar](https://doi.org/10.1109/ICIP.2012.6467492){:.pub_c_web}{:#pub_icip_2012_otitis_web}{:target="pub_icip_2012_otitis_web"},  
IEEE 19th International Conference on Image Processing (ICIP), pp. 2845-2848, Orlando, 2012. &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/icip_2012_otitis.bib)
	<details>
		<summary>Abstract</summary>
			<p style="margin-left: 20px; text-align: justify; font-size:16px">
			We propose an automated algorithm for classifying diagnostic categories of otitis media (middle ear inflammation); acute otitis media, otitis media with effusion and no effusion. Acute otitis media represents a bacterial superinfection of the middle ear fluid and otitis media with effusion a sterile effusion that tends to subside spontaneously. Diagnosing children with acute otitis media is hard, leading to overprescription of antibiotics that are beneficial only for children with acute otitis media, prompting a need for an accurate and automated algorithm. To that end, we design a feature set understood by both otoscopists and engineers based on the actual visual cues used by otoscopists; we term this otitis media vocabulary. We also design a process to combine the vocabulary terms based on the decision process used by otoscopists; we term this otitis media grammar. The algorithm achieves 84% classification accuracy, in the range or outperforming clinicians who did not receive special training, as well as state-of-the-art classifiers.
			</p>
	</details>

## Thesis/Dissertation

* **J. Li**,  
[Distributed parameter model based system identification and input determination in the estimation of blood alcohol concentration from transdermal alcohol biosensor data](http://digitallibrary.usc.edu/cdm/compoundobject/collection/p15799coll40/id/399407/){:.pub_t_web}{:#pub_stats_thesis_web}{:target="stats_thesis"},  
M.S. Thesis, University of Southern California, Jul. 2017.
	<details>
		<summary>Abstract</summary>
			<p style="margin-left: 20px; text-align: justify; font-size:16px">
			Methods for the estimation of blood or breath alcohol concentration (BAC/BrAC) from biosensor measured transdermal alcohol concentration (TAC) are developed, evaluated and compared. Specifically, a scheme based on a distributed parameter model with unbounded input and output for ethanol transport in the skin is compared to more conventional filtering/deconvolution techniques, one based on frequency domain methods, and the other on a time series approach using an autoregressive moving average (ARMA) input/output model. Our basis for comparison are five statistics of interest to alcohol researchers and clinicians: peak BAC/BrAC, time of peak BAC/BrAC, the ascending and descending slopes of the BAC/BrAC curve and area underneath the BAC/BrAC curve. It can be shown that the ARMA-based method yields the best estimation of the peak while the distributed parameter model produces the best estimation of the time of the peak. The Fourier-based method has the least variance out of the three and is computationally very efficient.
			</p>
	</details>

* **J. Li**,  
基于时空相关性的视频拷贝检测技术研究 (Spatio-temporal-correlation-based near-duplicate video detection),  
本科论文，北京工业大学，2011年6月 (B.E. Thesis, Beijing University of Technology, Jun. 2011)
	<details>
		<summary>Abstract</summary>
			<p style="margin-left: 20px; text-align: justify; font-size:16px">
			视频拷贝检测是目前多媒体处理领域的前沿研究热点，在海量视频信息检索和版权保护等方面有着重要的应用价值。视频拷贝检测的实质在于判断不同的视频片段是否具有相同的内容，从而实现对特定视频内容的搜索、检测和跟踪。在视频拷贝检测技术领域，当前国内外的研究重点是寻找各种复杂的特征提取方法来提高拷贝检测的准确性。然而在实际应用中，最需要解决的问题是在大规模数据下，在保持检测的准确性、鲁棒性的同时，如何显著提高拷贝检测的速度。本论文提出了一种基于时空相关性的视频拷贝检测技术。该技术利用视频时间和空间的相关性，直接在压缩域进行视频拷贝检测，在不解压或者少解压的情况下，在保证检测准确性的同时，大大提高检测的速度。该方法的实现过程如下: 首先，从 MPEG-2 压缩码流中提取亮度、颜色、纹理、运动 以及显著图等信息，然后利用这些信息对待检测的两段视频进行粗略的镜头分割，使之成为视频段落，然后对压缩域中提取的各种特征信息并进行统计，依据某一准则进行比对，最后综合各种特征的对比结果，给出两段视频相似程度。实验结果表明，本文提出的基于时空相关性的视频拷贝检测算法能够在保证检测准确率的同时，有效地降低处理复杂度，提升检测效率，并对不同分辨率、不同质量、不同内容的视频均具有较强的鲁棒性。
			</p>
	</details>