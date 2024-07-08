---
layout: project
title: "Divide Well to Merge Better: A Novel Clustering Algorithm"	
subtitle: "An Enhanced Non-Parametric Approach for Optimized Clustering"
---
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

**Abstract.**
In this paper, we propose a novel non-parametric clustering algorithm based on a divide-and-merge strategy. The Division phase optimizes the number of sub-clusters using an enhanced K-means algorithm, calculating variance reductions to determine optimal splits: $$D_{c_j}(k) = \left\{ \frac{|V_{c_j}(k+1) - V_{c_j}(k)|}{V_{c_j}(k)} : k = 1, 2, \ldots, l - 1 \right\}$$ and $$O_j = \arg\max_{j} \left\{ k : D_{c_j}(k) \ge T_{\text{init}} \right\}$$. The Merging phase leverages Gaussian Mixture Models to estimate joint probability densities of projected data points, $$f_{C_J}(x) = \sum_{i=1}^{G} \frac{w_i}{\sigma_i \sqrt{2\pi}} e^{-\frac{(x - \mu_i)^2}{2\sigma_i^2}} $$ with $$ \sum_{i=1}^{G} w_i = 1$$, and calculates the overlap region for merging decisions. Extensive evaluation on 20 benchmark datasets, including synthetic and real data, demonstrates the algorithm's superiority in discovering clusters of varying shapes and densities, outperforming state-of-the-art methods.
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
	url="/assets/projects/DivideWellMerge/divide.png"
	width="100%"
%}
