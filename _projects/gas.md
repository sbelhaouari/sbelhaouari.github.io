---
layout: project
title: "Advanced Statistical Metrics for Gas Identification System With Quantification Feedback"	
subtitle: "Enhanced Gas Identification Using Cluster-k-NN and Advanced Statistical Metrics"
---
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

**Abstract.**
This paper introduces a novel gas identification method based on the Cluster-k-Nearest Neighbor (C-k-NN) algorithm, integrating k-NN's accuracy with k-means clustering efficiency. Feature selection leverages new statistical metrics, specifically $$\text{Metric1}_j(l,k) = \frac{| \bar{x}_j(l) - \bar{x}_j(k) |}{\sqrt{ \frac{S_j(l)^2}{n_l} + \frac{S_j(k)^2}{n_k} }}$$ and $$\text{Metric2}_j(l,k) = 1 - A_{\text{overlap}}(l,k)$$, where $$A_{\text{overlap}}(l,k) = \int_{-\infty}^{+\infty} \min(\phi_l(x), \phi_k(x)) dx$$. The proposed Tree C-k-NN achieves 100% accuracy by minimizing classification time and misclassification. The approach is validated on six gases, with a performance of 98.7% for C-k-NN and 100% for Tree C-k-NN, and further confirmed using public datasets.<br/> &nbsp;&nbsp;&nbsp;&nbsp;
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
	url="/assets/projects/GasIndentification/gas.png"
	width="100%"
%}
