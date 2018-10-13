---
title: "Pipeline ~ EZ Fingerprint"
category: "ezf_pl"
permalink: /software/EZ_Fingerprint/tutorial/pipeline/ezf_test
layout: single
author_profile: false
date: 2018-04-12
---

# Testing

<br/>Very similar to the [classifier training](/software/EZ_Fingerprint/tutorial/pipeline/ezf_train#ct) section, but instead of testing the performance within the training group of subjects using cross-validation, here we test the model on a completely different group of subjects. Note that testing on subjects that had been used for training will make the result meaningless. **You must always have your training and testing group disjoint**. Again, **ALWAYS DISJOINT**.

<p align="center">
  <img src="/images/software/EZ_Fingerprint/test.png" style="max-width: 70%;">
</p>

This tab should look familiar to you, at least most of the parts.

* Choose any model you have trained before and want to test here by clicking the `Browse` button.

* Adjust the `Voting Agreement` as needed. Note changing this will effectively change the other one in the [cross-validation](/software/EZ_Fingerprint/tutorial/pipeline/ezf_train#cv) section as well. They share the same parameter.

* Click `Show Model` if you want to look at the parameters used in the model you selected above.

* Click `Test` to see the testing result in the table below.

* Finally, we provide a `Export CSV` function that allows you to export your testing results to a csv file. This is a similar function to the one in the [labeling](/software/EZ_Fingerprint/tutorial/pipeline/ezf_label#lr) section, but now with one more column showing the predicted label for each contact.

<div class="pagination">
	<a class="left" href="/software/EZ_Fingerprint/tutorial/pipeline/ezf_train"><i class="fa fa-arrow-circle-left"></i> Training </a>
	<a class="right" href="/software/EZ_Fingerprint/tutorial/pipeline/ezf_predict"> Prediction <i class="fa fa-arrow-circle-right"></i></a>
</div>
