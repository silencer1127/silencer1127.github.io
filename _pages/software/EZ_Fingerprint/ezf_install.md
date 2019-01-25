---
title: "Installation ~ EZ Fingerprint"
category: "ezf"
permalink: /software/EZ_Fingerprint/ezf_install
layout: single
author_profile: false
date: 2018-04-12
---

# Installation

## System Requirements

&nbsp; | Minimum | Recommended
:---:|:---:|:---:
CPU | x86_64 | x86_64
Memory | 4 GB | 8 GB +
OS<sup>*</sup> | Windows 7 (64-bit)<br> Mac OS X 10.8<br> Linux (64-bit) | Windows 7 (64-bit)<br> Mac OS X 10.12<br> Linux Ubuntu/Mint (64-bit)
[MATLAB](https://www.mathworks.com/products/matlab.html){:target="matlab"}<sup>&dagger;</sup> | R2012b/R2016b | R2017a
MATLAB toolbox | Image Processing Toolbox<br> Statistics and Machine Learning Toolbox | Image Processing Toolbox<br> Statistics and Machine Learning Toolbox <br> Parallel Computing Toolbox
[Brainstorm](http://neuroimage.usc.edu/brainstorm/){:target="brainstorm"} | Yes | Yes
Internet | Yes | Yes

<span style="font-size:0.8em;">\* Theoratically the operating system should not matter as long as MATLAB with required toolboxes and Brainstorm are successfully installed. However, the EZF is fully tested only on systems listed under recommendation.</span>  
<span style="font-size:0.8em;">&dagger; R2012b is the absolute minimum version to install EZF as MATLAB "app" does not exist before that. R2016b is the minimum version for EZF to be fully functional. Some advanced functions, such the bayesopt in the hyperparameter tuning section, do not exist before R2016b. We strongly recommmend using version R2017a, on which the EZF was fully tested. Due to the imcompatibilty of MATLAB functions across releases, it's not guaranteed to be bug-free using other versions. However, if you do have to use certain version of MATLAB and encounter some issues, feel free to contact us.</span>

## Download

Follow this [link](/software/EZ_Fingerprint/ezf_download) to the download page

## Installation

* Open MATLAB
* Install the App "EZFingerprint"

	![](/images/software/EZ_Fingerprint/install_1.png)
	
	* Click the `APPS` tab on the top
	* Click the second icon from the left `Install App`
	* Locate the downloaded file "EZFingerprint.mlappinstall"
	* Click `Open` and proceed as instructed
* An icon will appear under tab `APPS`, click `EZFingerprint` to open

	![](/images/software/EZ_Fingerprint/install_2.png)

## Uninstallation

Do **NOT** uninstall EZF using the MATLAB icon as shown above. Due to the incompatibility of the MATLAB APP management and our online installation mechanism, uninstallation using the MATLAB default method will result in some file/directory left-overs. Moreover, it will prevent you from installing EZF again in the future.

Instead, you can use the "Uninstall" button under the "Misc" tab to perform a **complete** uninstalltion. See details [here](/software/EZ_Fingerprint/tutorial/ezf_misc#uninstall).

<div class="pagination">
	<a class="left" href="/software/EZ_Fingerprint/ezf_download"><i class="fa fa-arrow-circle-left"></i> Download </a>
	<a class="right" href="/software/EZ_Fingerprint/ezf_tutorial"> Tutorial <i class="fa fa-arrow-circle-right"></i></a>
</div>
