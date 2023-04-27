---
title: "fMRIPrep SAMSEG"
category: "main"
permalink: /software/fMRIPrep_SAMSEG/fMRIPrep_SAMSEG_main
layout: single
date: 2023-04-27
---

# **<center>SAMSEG-compatible version of fMRIPrep</center>**

## Introduction

[fMRIPrep](https://fmriprep.org){:target="fmriprep"} is a one of the commonly used tools for preprocessing of task-based and resting-state functional MRI (fMRI) data. One of the key steps in structural processing pipeline is surface reconstruction based on [FreeSurfer](https://surfer.nmr.mgh.harvard.edu){:target="freesurfer"}. fMRIPrep will call `recon-all` automatically if FreeSurfer has not been run on the structural image before processing functional data. Or users may run any customized FreeSurfer pipeline by themselves and tell fMRIPrep to pick up the prerun FreeSurfer outputs using the `--fs-subjects-dir` flag.

When working with images with pathology (very common in clinical scans), standard FreeSurfer pipeline does not work out of the box often due to inaccurate segmentation of brain tissues. In those cases, the Sequence Adaptive Multimodal SEGmentation ([SAMSEG](https://surfer.nmr.mgh.harvard.edu/fswiki/Samseg){:target="samseg"}) tool can be used to robustly segment brain structures without preprocessing (then standard surface recon pipeline can follow successfully). It has been integrated into FreeSurfer available in version 7.2 or later.

However, when feeding fMRIPrep (tested on v22.0.2) with SAMSEG FreeSurfer outputs, it produces a brain mask well beyond the brain, which leads to a cross modality co-registratoin error. An example/report can be found [here](https://neurostars.org/t/fmriprep-skull-strip-and-registration-error/21831){:target="fmriprep_neurostar_thread"}. Providing a pre-skull-stripped T1 image does not help if SAMSEG FreeSurfer outputs are supplied. The reason is SAMSEG has extra labels for structures outside the brain, such as skull, eyeball fluid, etc., which are absent from the standard aseg results. And fMRIPrep does not recognize these labels correctly as background pixels.


## Solution

The solution below assumes that a singularity/docker image version 22.0.2 is used, although it should work well in any other version/format in a similar way. The download link is provided at the bottom of this page if you'd like to use the patched image directly without fixing the problem by yourself.

---
A (dirty) fix to this issue is to shell into the singularity image and change the code as follows:

- convert existing image to a sandbox
`singularity build --sandbox --fakeroot fmriprep fmriprep-22.0.2.simg`

- shell into it
`singularity shell --fakeroot --writable fmriprep`

- make edits (any editor can be used)
`cd /opt/conda/lib/python3.9/site-packages/niworkflows/interfaces`
`vim freesurfer.py`

- inside the function `refine_aseg(aseg, ball_size=4):`, add the following after Line 483: `bmask = aseg.copy()`
```
bmask[bmask == 24] = 0  # CSF
bmask[bmask == 165] = 0  # Skull
bmask[bmask == 258] = 0  # Head-ExtraCerebral
bmask[bmask == 259] = 0  # Eye-Fluid
```

the line after should be `bmask[bmask > 0] = 1`

- convert sandbox back to image
`singularity build --fakeroot fmriprep-22.0.2-samseg.simg fmriprep`


## Disclaimer

IN NO EVENT SHALL THE AUTHORS, THE CONTRIBUTORS, THE DISTRIBUTORS, THE MASSACHUSETTS GENERAL HOSPITAL ("AUTHORS") BE LIABLE TO ANY PARTY FOR DIRECT, INDIRECT, SPECIAL, INCIDENTAL, OR CONSEQUENTIAL DAMAGES, INCLUDING LOST PROFITS, ARISING OUT OF THE USE OF THIS SOFTWARE OR PACKAGE ("SOFTWARE"), EVEN IF THE AUTHORS HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGE. THE AUTHORS SPECIFICALLY DISCLAIM ANY WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE. FOR RESEARCH PURPOSE ONLY. THIS SOFTWARE IS PROVIDED ON A "AS IS" BASIS AND THE AUTHORS HAVE NO OBLIGATION TO PROVIDE MAINTENANCE, SUPPORT, UPDATES, ENHANCEMENTS, OR MODIFICATIONS.

## Download

Please follow this [link](https://software.imagicastle.com:48877/download.php?app=fmriprep_samseg){:target="fmriprep_samseg_download"} (will open a new page) and fill out the form. An e-mail will be sent to you with a personal download link. 
