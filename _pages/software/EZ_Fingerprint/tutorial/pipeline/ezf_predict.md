---
title: "Pipeline ~ EZ Fingerprint"
category: "ezf_pl"
permalink: /software/EZ_Fingerprint/tutorial/pipeline/ezf_predict
layout: single
author_profile: false
date: 2018-04-12
---

# Prediction

<br/>Once you believe your model is reasonably good after some intensive training and testing, you may want to actually use it to predict EZ contacts for some new subjects, who have never been to any resection surgery or who had a unsuccessful resection surgery before and are still have seizures. The prediction may provide you some additional information about the location of the EZ.

Note that the prediction does not require any [label of resection](/software/EZ_Fingerprint/tutorial/pipeline/ezf_label#lr). However, you may find it very useful to have the labels of resection for those subjects who had a unsuccessful resection previously, so that you can compare the prediction result with the resected area.

<p align="center">
  <img src="/images/software/EZ_Fingerprint/predict.png" style="max-width: 70%;">
</p>

Similar to [testing](/software/EZ_Fingerprint/tutorial/pipeline/ezf_test) section, you need to:

* Choose any model you have trained before and want to test here by clicking the `Browse` button.

* Adjust the `Voting Agreement` as needed. Note changing this will effectively change the other two, one in the [cross-validation](/software/EZ_Fingerprint/tutorial/pipeline/ezf_train#cv) section, one in the [testing](/software/EZ_Fingerprint/tutorial/pipeline/ezf_test) section as well. They share the same parameter.

* Click `Show Model` if you want to look at the parameters used in the model you selected above.

* Click `Predict` to see the prediction result in the table below.

	The results are in a format of:

	Predicted EZ Contacts:	| # agreed / # total 	| predicted score
	---						|---					|---
	R3-R4:					| 2/3					| 0.19

	* Column 1: The name of the predicted EZ contacts.
	* Column 2: The number of seizures agreed with the prediction true over the total number of seizures
	* Column 3: The sum of the predicted scores from the classifier over all seizures. The larger the more likely the contact is a EZ contacts and vice versa. Zero score means no preference of the prediction.

There is one extra option:

* Display Predicted EZ with TF:

	If this option is ticked, then when you press `Predict` button, if there is any contact that is predicted to be an EZ contact, a (normalized) TF plot will show up with different colors of the name of the contact.

	If the label of resection is provided, then

	* Blue: Contacts inside the resected region but not predicted as EZ (false negative).
	* Red: Contacts outside the resected region but predicted as EZ (false positive).
	* Blue + Red = Purple: Contacts inside the resected region also predicted as EZ (true positive).
	* Black as usual: Contacts outside the resected region also not predicted as EZ (true negative).

	If the label of resection is not provided, then only red and black contacts are shown for prediction result.

<div class="pagination">
	<a class="left" href="/software/EZ_Fingerprint/tutorialezf_test"><i class="fa fa-arrow-circle-left"></i> Testing </a>
	<a class="right" href="/software/EZ_Fingerprint/tutorial/ezf_misc"> Miscellaneous <i class="fa fa-arrow-circle-right"></i></a>
</div>

