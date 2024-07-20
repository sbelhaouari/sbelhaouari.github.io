---
layout: project
title: "Computer Aided Diagnosis System based on Machine Learning Techniques for Lung Cancer"	
subtitle: "Improving Lung Cancer Detection Using Wavelet-Based Feature Extraction and Cluster-KNN"
---
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

**Abstract.**
This paper presents a novel Computer Aided Diagnosis (CAD) system for lung cancer utilizing advanced machine learning techniques. The system incorporates a feature extraction phase using Wavelet Transforms (WT) with Haar, Daubechies (db1), and Symlet (sym3) functions, followed by a two-stage feature selection based on variance and energy metrics, defined as $$\text{Var_mod} = \frac{1}{n} \sum_{i=1}^{n} \left(\mu_i - \mu_T\right)^2$$ and $$E = \sum_{i=1}^{N} x_i^2$$. Classification is performed using a hybrid Cluster-K-Nearest Neighbor (C-KNN) algorithm, combining K-means and K-NN, enhancing accuracy by minimizing intra-cluster variance and maximizing inter-cluster variance. Evaluation on the JSRT dataset yields a peak accuracy of 96.58% with db1 at level 3, highlighting the effectiveness of the proposed method. The unique clustering and classification strategy significantly reduces false positives and negatives, presenting a robust approach for lung nodule detection. Future work will explore additional wavelet functions and the application of Curvelet Transforms to further augment diagnostic precision.
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
	url="/assets/projects/MachineLearningDetection/mldetection.png"
	width="100%"
%}
