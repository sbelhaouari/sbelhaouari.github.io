---
layout: project
title: "A statistical based feature extraction method for breast cancer diagnosis in digital mammogram using multiresolution representation"	
subtitle: "Optimizing Mammogram Analysis with Multiresolution Feature Extraction"
---
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

**Abstract.**
This paper introduces a novel feature extraction method for breast cancer diagnosis in digital mammograms using multiresolution representations. The proposed method transforms mammogram images into coefficient vectors via wavelet and curvelet transforms, constructing a matrix where each row represents an image and each column a coefficient. Feature significance is ranked using a statistical t-test, optimizing the feature set to maximize classification accuracy. Support Vector Machine (SVM) classifiers distinguish between normal and abnormal tissues, as well as benign and malignant tumors. The feature capability to differentiate classes is given by $$CT = \frac{m_a - m_b}{\sqrt{\left(\frac{s_a^2}{n_a}\right) + \left(\frac{s_b^2}{n_b}\right)}}$$. Validation using the MIAS dataset achieved classification accuracy rates of 94.79% with 1238 features and 100% with 150 features for wavelets, and 95.67% with 5663 features and 100% with 333 features for curvelets, demonstrating the efficacy of the method in improving diagnostic accuracy.
<!-- In this work, we propose a new experimental design for testing whether SUTVA holds, without making any assumptions on how treatment effects may spill over between the treatment and the control group.
To achieve this, we simultaneously run both a completely randomized and a cluster-based randomized experiment, and then we compare the difference of the resulting estimates. We present a statistical test for measuring the significance of this difference and offer theoretical bounds on the Type I error rate.
<br/> &nbsp;&nbsp;&nbsp;&nbsp;
We provide practical guidelines for implementing our methodology on large-scale experimentation platforms.
Importantly, the proposed methodology can be applied to settings in which a network is not necessarily observed but, if available, can be used in the analysis.
Finally, we deploy this design to LinkedIn's experimentation platform and apply it to two online experiments, highlighting the presence of network effects and bias in standard A/B testing approaches in a real-world setting. -->

<!-- This work is part of a two-paper series.
In the <a href="https://arxiv.org/abs/1704.01190" target="_blank">first paper</a> we introduce the methodology and main theoretical results and
in the <a href="{{ '/assets/publications/2017_detecting_network_effects/paper.pdf' | prepend: site.baseurl }}" target="_blank">second paper</a> we present implementation guidelines for using the methodology on large-scale experimentation platforms. -->

**Illustration of the proposed experimental design.** <br/>
{%
	include image_with_caption.html
	url="/assets/projects/MammogramFeatureExtraction/mfe.png"
	width="100%"
%}
