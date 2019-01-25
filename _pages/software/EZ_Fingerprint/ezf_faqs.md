---
title: "FAQs ~ EZ Fingerprint"
category: "ezf"
permalink: /software/EZ_Fingerprint/ezf_faqs
layout: single
author_profile: false
date: 2018-04-12
---

# FAQs

<br/>We will answer some of the most commonly asked questions here and try to keep the FAQ list updated.

## My download link expired, what happened?

Your personal download link sent to your e-mail address will be valid for 3 times within an hour since your request. If your download link is expired, just request another one again from [here](/software/EZ_Fingerprint/ezf_download).

## The auto-update process failed and I could not start EZF. What should I do?

Errors may occur during the auto-update due to some compatibility issue. The easiest and fastest way to fix it is:

1. Locate the [installation folder](#installation_folder) and completely delete the previously installed EZF. If there are multiple installation folders, such as "EZFingerprint", "EZFingerprint 1", etc., delete all of them. (**Warning: Only delete the EZF software folder if your workspace is not setup to be the same folder. If they are the same, move all your data, including the "SubInfo.mat", to some other place before the deletion. See [here](/software/EZ_Fingerprint/tutorial/ezf_setup#ws_dir) for how to manipulate your workspace.**)

2. Re-install EZF. Click [here](/software/EZ_Fingerprint/ezf_install) for the installation instruction. If you don't have the installation file "EZFingerprint.mlappinstall" anymore, no worry, just re-download it from [here](/software/EZ_Fingerprint/ezf_download).

3. Start EZF and just select the workspace folder, you are back to work.


## <a name="installation_folder">Where is the EZF software installed?</a>

The default installation folder is shown below if you haven't changed it before.

* Windows - %USERPROFILE%/Documents/MATLAB/Add-Ons/Apps.
* Mac/Linux - $home/Documents/MATLAB/Add-Ons/Apps.

See [this page](https://www.mathworks.com/help/matlab/ref/userpath.html){:target="matlab_userpath"} for the default user path or you can open the folder using MATLAB GUI as explained [here](https://www.mathworks.com/help/matlab/matlab_env/manage-your-add-ons.html){:target="matlab_addon"}.

## What if I uninstalled EZF via clicking the MATLAB icon and how can I clean up the left-overs?

First, you need to find the [EZF installation directory](#installation_folder).

Then, locate the "EZFingerprint" folder and delete it.

## I couldn't perform the factory reset and what if I mis-typed the factoryreset?

Make sure you are under the "**Misc**" tab. Other tab will not activate the factory reset function. If you mis-typed the word "factoryreset", just forget what you have typed and restart from the beginning. There is no need to hit any other button to activate it.

## Do you collect any personal information?

See our [privacy policy](/software/EZ_Fingerprint/ezf_privacy) for details.


<div class="pagination">
	<a class="left" href="/software/EZ_Fingerprint/ezf_about"><i class="fa fa-arrow-circle-left"></i> About </a>
</div>