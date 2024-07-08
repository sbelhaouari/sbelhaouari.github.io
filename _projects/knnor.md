---
layout: project
title: "KNNOR: An oversampling technique for imbalanced datasets"	
subtitle: "Enhancing Minority Class Representation in Imbalanced Datasets with Advanced K-Nearest Neighbor Oversampling"
---
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

**Abstract.**
Imbalanced datasets significantly hinder ML model performance. Existing techniques like SMOTE and ADASYN struggle with 'within class imbalance' and the 'small disjunct problem'. We propose K-Nearest Neighbor Oversampling (KNNOR), which sorts minority class points by distance to their $$k$$th nearest neighbor, generates synthetic points iteratively, and validates them using k-nearest neighbor classification. This method ensures reliable oversampling, avoiding noise amplification. For example, given minority data points $$\{x_1, x_2, x_3\}$$, the new point $$x_{new}$$ is calculated as $$x_{new} = x_i + \alpha \cdot (x_i - x_{near}) \text{ for } i \in \{1, 2, 3\}, \alpha \in [0, 1]$$. Experimental results show that KNNOR ranks first across several datasets and classifiers, demonstrating superior performance compared to ten top oversamplers. The method is available as an open-source Python library.
<br/> &nbsp;&nbsp;&nbsp;&nbsp;
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
	url="/assets/projects/KNNOROversampling/knnor.png"
	width="100%"
%}
