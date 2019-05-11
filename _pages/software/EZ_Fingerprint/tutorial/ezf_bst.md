---
title: "Tutorial ~ EZ Fingerprint"
category: "ezf_tt"
permalink: /software/EZ_Fingerprint/tutorial/ezf_bst
layout: single
author_profile: false
date: 2018-09-19
---

# Prerequisite

<br/>
Our EZF software relies on the [Brainstorm](http://neuroimage.usc.edu/brainstorm/){:target="brainstorm"} software for basic data manipulations and file organizations prior to signal processing and analysis for the localization of the EZ.

> "Brainstorm is a collaborative, open-source application dedicated to the analysis of brain recordings:
MEG, EEG, fNIRS, ECoG, depth electrodes and animal electrophysiology."

If you are unfamilar with Brainstorm, you can catch up quickly by going through the Brainstorm's tutorials [here](http://neuroimage.usc.edu/brainstorm/Tutorials){:target="bst_tutorial"}.

EZF will import selected data segments into its own workspace directly from the Brainstorm's database. But you need to perform the following steps in Brainstorm before importing data to our EZF software for further analysis:

* Linking/Reviewing/Visualizing the raw (stereotactic) Electroencephalography (EEG/SEEG) data.
* Delete any nuisance channel if exists.
* Switching to bipolar montage. A back-to-back stitching referential montage is highly recommended (also known as bipolar 2 montage in [Brainstorm](http://neuroimage.usc.edu/brainstorm/){:target="brainstorm"}, e.g. X1-X2, X2-X3, X3-X4, ...).
* For **each** subject and for **each** seizure recording, you need to collect:
	* Seizure data:
		* Select a data segment that contains the seizure.
		* 40 seconds or longer is recommended with seizure onset centered at 0, i.e. data including 20 seconds before the seizure onset and 20 seconds after.
		* Export this data segment into the database and give a name of your own choice following the word "SZ" (case sensitive, both "S" and "Z" are capital), e.g. "SZ1_my_own_name".
	* Background data:
		* Select a data segment that was a few minutes before the seizure onset.
		* This data segment should not contain any seizure or obvious artifact / spikes.
		* 40 seconds or longer is recommended.
		* Export this data segment into the database and name it **exactly** same as the name for the seizure segment except that the starting word "SZ" should be replaced with "BG", e.g. "BG1_my_own_name" in order to match the SZ name above.
* "SZ" and "BG" segments must appear as a pair
* You may collect data of multiple seizures for a subject and collect data for multiple subjects under the same protocol.
* Double check your channel information and make sure it exists under both "SZ" condition and "BG" condition and the type for your desired channels is **SEEG**. It's ok to have other types of channels together with the SEEG channels, e.g. ECG, REF, DC, etc. Just leave them as they are and the EZF software will not pick them up.

The figure below shows an example of a typical Brainstorm protocol folder that follows the requirements above. In this example:
* 11 subjects' data were collected.
* Three subjects folder were expanded to illustrate the naming convention of the seizure and background data segments.
* Subject101 had 2 seizures collected, Subject102 had only 1 seizure collected and Subject 103 had 3 seizures collected.
* All "SZ"s and "BG"s were named in pair.

<p align="center">
  <img src="/images/software/EZ_Fingerprint/bst_protocol_panel.png">
</p>

<div class="pagination">
	<a class="left" href="/software/EZ_Fingerprint/ezf_tutorial"><i class="fa fa-arrow-circle-left"></i> Tutorial </a>
	<a class="right" href="/software/EZ_Fingerprint/tutorial/ezf_setup"> Setup <i class="fa fa-arrow-circle-right"></i></a>
</div>


