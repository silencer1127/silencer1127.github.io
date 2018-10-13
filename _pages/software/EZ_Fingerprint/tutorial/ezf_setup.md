---
title: "Tutorial ~ EZ Fingerprint"
category: "ezf_tt"
permalink: /software/EZ_Fingerprint/tutorial/ezf_setup
layout: single
author_profile: false
date: 2018-04-12
---

# Setup

<br/>The first main tab is "Setup" as shown below. In this panel, you need to setup two paths/directories before entering the processing pipeline.

<p align="center">
  <img src="/images/software/EZ_Fingerprint/setup.png">
</p>


## <a name="bst_dir"></a>Choose Brainstorm Protocol Directory

This directory is only used for data importing purpose. Make sure to choose the Brainstorm "Protocol" folder rather than the database folder. The "Protocol" folder typically contains two sub-folders: "anat" and "data". You may have multiple protocols in one database. Refer to the Brainstorm database structure [here](http://neuroimage.usc.edu/brainstorm/Tutorials/CreateProtocol#Database_structure){:target="bst_database"} for details.

The figure below shows the folder structure which corresponds to the Brainstorm protocol as shown in the [Prerequisite](/software/EZ_Fingerprint/tutorial/ezf_bst). The very top-level folder "2015_SZ_free_BST" is the protocol folder and should be selected.

<p align="center">
  <img src="/images/software/EZ_Fingerprint/bst_protocol_folder.png">
</p>

## <a name="ws_dir"></a>Choose Main Workspace Directory

This directory is your main workspace. A **workspace** is a place/folder where you can group a particular set of subjects and perform either training or testing together.

* Create a new workspace
	
	Create a new empty folder in your computer and select that folder as your workspace directory.

* Switch between workspaces
	
	Simply select the workspace directory you want to switch to.

* Delete a existing workspace

	Select another workspace directory if the current workspace is the one you want to delete. Then just delete the workspace folder from your computer.

Technically, the workspace folder is nothing but a regular operating system folder that contains the imported subjects' data and a "SubInfo.mat" which will be created and maintained by EZF when importing or deleting subjects. This means:

* You may copy the workspace folder to anywhere you want in your computer. You may also transfer the entire folder to your colleague and he/she will be able to load that workspace as well.

* You may have multiple workspaces existed in your computer simultaneously for different groups of subjects. EZF will treat them independently. However, you can only work on one of them at a time but can switch among them at your convenience.

Yet it's very flexible how you move the workspace folder around. We strongly recommend that you do **NOT** modify anything inside the folder by yourself unless you are very familiar with how EZF manages the subjects' data. Let EZF do the workspace management for you and several workspace management functions are provided, e.g. split, merge. (for geeks, feel free to read the code and learn the technical details)

Finally, it is strongly recommended **NOT** select the folder [where the EZF software installed](/software/EZ_Fingerprint/ezf_faqs#installation_folder) as your workspace. It is designed on purpose to separate the EZF software from the data so that if there is anything wrong with the software, your data will be kept intact.

<div class="pagination">
	<a class="left" href="/software/EZ_Fingerprint/tutorial/ezf_bst"><i class="fa fa-arrow-circle-left"></i> Prerequisite </a>
	<a class="right" href="/software/EZ_Fingerprint/tutorial/ezf_pipeline"> EZF Processing Pipeline <i class="fa fa-arrow-circle-right"></i></a>
</div>