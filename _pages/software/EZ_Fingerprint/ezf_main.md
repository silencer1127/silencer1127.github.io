---
title: "Introduction ~ EZ Fingerprint"
category: "ezf"
permalink: /software/EZ_Fingerprint/ezf_main
layout: single
author_profile: false
date: 2019-11-05
---

> 2019/04/30:
>
> We recently migrated our backend services to AWS for their reliability purpose. However, it triggers an incompatibility issue between the MATLAB http request functions and AWS. This should not prevent you from using the software, however, you may not able to check and install updates automatically. Therefore, we strongly encourage you to reinstall the EZF software to get the most recent version. Reinstallation is as simple as 1) uninstall the current version as instructed [here](/software/EZ_Fingerprint/tutorial/ezf_misc#uninstall); 2) re-download the installation file [here](/software/EZ_Fingerprint/ezf_download); and 3) reinstall the EZF as shown [here](/software/EZ_Fingerprint/ezf_install).


# **<center>Epileptogenic Zone Fingerprint</center>**

## Introduction

<br/>Epileptogenic Zone Fingerprint (EZF) is an open-source software that allows you to process stereotactic EEG (SEEG) recordings, visualize time-frequency (TF) plots and potentially help you localize the EZ(s) for subjects with focal epilepsies.

Our main objectives are:

* Provide a friendly graphic user interface (GUI) for the processing, visualization and analysis of SEEG data without deep knowledge about MATLAB programming.

* Provide a convenient data management tool that allows users to group different type of subjects in different workspaces and be able to switch from one to another easily.

* Promote reproducibility and productivity in epilepsy research and facilitate and help the localization of the EZ for unseen subjects.

## Disclaimer

IN NO EVENT SHALL THE AUTHORS, THE CONTRIBUTORS, THE DISTRIBUTORS AND THE UNIVERSITY OF SOUTHERN CALIFORNIA ("AUTHORS") BE LIABLE TO ANY PARTY FOR DIRECT, INDIRECT, SPECIAL, INCIDENTAL, OR CONSEQUENTIAL DAMAGES, INCLUDING LOST PROFITS, ARISING OUT OF THE USE OF THIS SOFTWARE, EVEN IF THE AUTHORS HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGE. THE AUTHORS SPECIFICALLY DISCLAIM ANY WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE. THIS SOFTWARE IS FOR RESEARCH PURPOSE ONLY AND HAS NOT BEEN APPROVED FOR ANY CLINICAL USE. THIS SOFTWARE IS PROVIDED ON A "AS IS" BASIS AND THE AUTHORS HAVE NO OBLIGATION TO PROVIDE MAINTENANCE, SUPPORT, UPDATES, ENHANCEMENTS, OR MODIFICATIONS.

Also note that even for a single subject, the type and the appearance of TF plots may differ from one seizure to another. Therefore, predictions using mixed type of seizures for a subject may lead to partial detection or even no detection of the EZ contacts.

Again, this software is for **research purpose only**. One should not make any clinical decision based on the prediction result using this EZF software.

## Get Started

* First you need to install [MATLAB](https://www.mathworks.com/products/matlab.html){:target="matlab"} and the [Brainstorm](http://neuroimage.usc.edu/brainstorm/){:target="brainstorm"} software if you don't have them in your computer as they are required in order to run our EZF software. 

* Then you may proceed to [Download](/software/EZ_Fingerprint/ezf_download) section followed by a easy [Installation](/software/EZ_Fingerprint/ezf_install) procedure.

* We provide a complete online [Tutorial](/software/EZ_Fingerprint/ezf_tutorial) that will take you through all the steps one by one.

* Feel free to [contact](mailto:jian.li.andrew@gmail.com) us if you have any questions or send us any feedback.

## How to Cite EZF

Please cite the following papers in your publications if you have used our EZF software in your research.

O. Grinenko, J. Li, J. C. Mosher, I. Z. Wang, J. C. Bulacio, J. Gonzalez-Martinez, D. Nair, I. Najm, R. M. Leahy, P. Chauvel, "A fingerprint of the epileptogenic zone in human epilepsies", *Brain*, vol. 141, no. 1, pp. 117--131, 2018. &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/GrinenkoLi2018Afotezihe.bib)

J. Li, O. Grinenko, J. C. Mosher, J. Gonzalez-Martinez, R. M. Leahy, P. Chauvel, "Learning to define an electrical biomarker of the epileptogenic zone", *Human Brain Mapping*, 2019. (In press) &nbsp; [<i class="fa fa-quote-right"></i>](/files/bib/Li2019Ltdaebotez.bib) 

## Support

This work was supported in part by the National Institutes of Health under award R01NS089212 and R01EB009048. The content is solely
the responsibility of the authors and does not necessarily represent the official views of the National Institutes of Health.

<div class="pagination">
	<a class="right" href="/software/EZ_Fingerprint/ezf_download"> Download <i class="fa fa-arrow-circle-right"></i></a>
</div>