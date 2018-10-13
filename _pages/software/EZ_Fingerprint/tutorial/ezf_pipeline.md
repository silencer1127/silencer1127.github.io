---
title: "Tutorial ~ EZ Fingerprint"
category: "ezf_tt"
permalink: /software/EZ_Fingerprint/tutorial/ezf_pipeline
layout: single
author_profile: false
date: 2018-04-12
---

# EZF Processing Pipeline

<br/>This is the main panel of EZF software and all data processing and analysis related steps can be found here. The following figure shows the appearance of the EZF preprocessing pipeline.

<p align="center">
  <img src="/images/software/EZ_Fingerprint/pipeline.png">
</p>

## [Data Panel](/software/EZ_Fingerprint/tutorial/pipeline/ezf_data) (Left)

All data management and manipulation functions are provided in this panel, including data importing, deletion, splitting, merging, selection. Also we provide a visualization of the status of the processing steps. For details, click [here](/software/EZ_Fingerprint/tutorial/pipeline/ezf_data).

## Processing Panel (Right)

This panel includes the entire data processing pipeline all the way from preprocessing to EZ prediction. The instruction for each step can be found as follows:

* [Preprocessing](/software/EZ_Fingerprint/tutorial/pipeline/ezf_preprocess):
	* [Time-Frequency](/software/EZ_Fingerprint/tutorial/pipeline/ezf_preprocess#tf)
	* [Artifact Removal](/software/EZ_Fingerprint/tutorial/pipeline/ezf_preprocess#ar)
	* [Normalization](/software/EZ_Fingerprint/tutorial/pipeline/ezf_preprocess#norm)
* [Labeling](/software/EZ_Fingerprint/tutorial/pipeline/ezf_label)
	* [Mark Bad Channels and End of FA](/software/EZ_Fingerprint/tutorial/pipeline/ezf_label#mark)
	* [Label Resection](/software/EZ_Fingerprint/tutorial/pipeline/ezf_label#lr)
* [Training](/software/EZ_Fingerprint/tutorial/pipeline/ezf_train)
	* [Feature Extraction](/software/EZ_Fingerprint/tutorial/pipeline/ezf_train#fe)
	* [Classifier Training](/software/EZ_Fingerprint/tutorial/pipeline/ezf_train#ct)
	* [Hyperparameter Tuning](/software/EZ_Fingerprint/tutorial/pipeline/ezf_train#ht)
* [Testing](/software/EZ_Fingerprint/tutorial/pipeline/ezf_test)
* [Prediction](/software/EZ_Fingerprint/tutorial/pipeline/ezf_predict)

<div class="pagination">
	<a class="left" href="/software/EZ_Fingerprint/tutorial/ezf_setup"><i class="fa fa-arrow-circle-left"></i> Setup </a>
	<a class="right" href="/software/EZ_Fingerprint/tutorial/pipeline/ezf_data"> Data <i class="fa fa-arrow-circle-right"></i></a>
</div>
