---
layout: project
title: "Unsupervised outlier detection in multidimensional data"	
subtitle: "Efficient and Robust Outlier Detection Using Unidimensional Distance Space and Joint Probability Density Estimation"
---
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

**Abstract.**
Detection and removal of outliers in high-dimensional data is critical for robust machine learning performance. This paper introduces novel unsupervised statistical methods for outlier detection, leveraging data compactness and transformation to unidimensional distance space using D-k-NN. The distance vector, $$d_k \in \mathbb{R}$$, transforms $$N$$-dimensional data, with extreme values calculated as $$LE_{dk} = Q1_{dk} - c_1(Q2_{dk} - Q1_{dk})$$ and $$UE_{dk} = Q3_{dk} + c_2(Q3_{dk} - Q2_{dk})$$, optimizing outlier identification. Joint probability density estimation based on normal distributions is utilized, where $$\zeta = \beta Q3_{dk}$$ and $$f(x,y) = \frac{1}{2\pi \zeta I} e^{-\left( \frac{(x-x_i)^2 + (y-y_i)^2}{2\zeta^2} \right)}$$. Comprehensive performance analysis on benchmark datasets demonstrates superiority over state-of-the-art methods in scenarios with non-normal or mixed noise distributions.
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
	url="/assets/projects/JumpingParticle/particle.png"
	width="100%"
%}
