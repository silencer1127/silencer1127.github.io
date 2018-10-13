---
title: "Introduction ~ EZ Fingerprint"
category: "ezf"
permalink: /software/EZ_Fingerprint/ezf_main
layout: single
author_profile: false
date: 2018-04-12
---

# **<center>Epileptogenic Zone Fingerprint</center>**

## Introduction

<br/>Epileptogenic Zone Fingerprint (EZF) is an open-source software that allows you to process stereotactic EEG (SEEG) recordings, visualize time-frequency (TF) plots and potentially help you localize the EZ(s) for subjects with focal epilepsies.

Our main objectives are:

* Provide a friendly graphic user interface (GUI) for the processing, visualization and analysis of SEEG data without much knowledge about MATLAB programming.

* Provide a convenient data management tool that allows users to group different type of subjects in different workspaces and be able to switch from one to another easily.

* Promote reproducibility and productivity in epilepsy research and facilitate and help the localization of the EZ for unseen subjects.

## Disclaimer

IN NO EVENT SHALL THE AUTHORS, THE CONTRIBUTORS, THE DISTRIBUTORS AND THE UNIVERSITY OF SOUTHERN CALIFORNIA ("AUTHORS") BE LIABLE TO ANY PARTY FOR DIRECT, INDIRECT, SPECIAL, INCIDENTAL, OR CONSEQUENTIAL DAMAGES, INCLUDING LOST PROFITS, ARISING OUT OF THE USE OF THIS SOFTWARE, EVEN IF THE AUTHORS HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGE. THE AUTHORS SPECIFICALLY DISCLAIM ANY WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE. THIS SOFTWARE IS FOR RESEARCH PURPOSE ONLY AND HAS NOT BEEN APPROVED FOR ANY CLINICAL USE. THIS SOFTWARE IS PROVIDED ON A "AS IS" BASIS AND THE AUTHORS HAVE NO OBLIGATION TO PROVIDE MAINTENANCE, SUPPORT, UPDATES, ENHANCEMENTS, OR MODIFICATIONS.

Also note that:

* The reseach behind this software was conducted on a particular group of subjects which had sustained fast activities with high frequency oscillations (generally gamma or higher). The EZ contacts may not be correctly identified for subjects with lower fast activity. See the patient selection protocol in our paper below. We are currently actively evaluating the performance on different group of subjects.

* We realized that even for a single subject, the type and the appearance of the TF plots may differ from one seizure to another. Therefore, predictions using mixed type of seizures for a subject may lead to partial detection or even no detection of the EZ contacts.

Again, this software is for **research purpose only**. One should not make any clinical decision based on the prediction result using this EZF software.

## Get Started

* First you need to install [MATLAB](https://www.mathworks.com/products/matlab.html){:target="matlab"} and the [Brainstorm](http://neuroimage.usc.edu/brainstorm/){:target="brainstorm"} software if you don't have them in your computer as they are required in order to run our EZF software. 

* Then you may proceed to [Download](/software/EZ_Fingerprint/ezf_download) section followed by a easy [Installation](/software/EZ_Fingerprint/ezf_install) procedure.

* We provide a complete online [Tutorial](/software/EZ_Fingerprint/ezf_tutorial) that will take you through all the steps one by one.

* Feel free to [contact](/software/EZ_Fingerprint/tutorial/ezf_misc#about) us if you have any questions or send us any feedback.

## How to Cite EZF

Please cite the following paper in your publications if you have used our EZF software in your research.

O. Grinenko, J. Li, J. C. Mosher, Z. Wang, J. Bulacio, J. Gonźalez-Martinez, D. Nair, I. Najm, R. M. Leahy, P. Chauvel, "A fingerprint of the epileptogenic zone in human epilepsies", Brain, vol. 141, no. 1, pp. 117-131, 2018.

[[bib]](/files/bib/brain_2017_fingerprint.bib)

## Support

This work was supported in part by the National Institutes of Health under award R01NS089212 and R01EB009048. The content is solely
the responsibility of the authors and does not necessarily represent the official views of the National Institutes of Health.

## What's New

* Remembered the path for choosing a file or directory
* Added the function to export labels to csv in testing and prediction
* Provided super high and super low range when displaying TF
* Show label of resection if exists in all TF plots

<div class="pagination">
	<a class="right" href="/software/EZ_Fingerprint/ezf_download"> Download <i class="fa fa-arrow-circle-right"></i></a>
</div>