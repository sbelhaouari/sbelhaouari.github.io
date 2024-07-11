---
layout: project
title: "Bird’s Eye View feature selection for high-dimensional datas"	
subtitle: "Evolutionary Algorithms and Reinforcement Learning for Effective High-Dimensional Feature Selection"
---
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

**Abstract.**
In this study, we introduce the Bird’s Eye View (BEV) feature selection technique for high-dimensional data, integrating Evolutionary Algorithms with Genetic Algorithms, Dynamic Markov Chains, and Reinforcement Learning to enhance classification performance. The BEV model iteratively refines feature subsets by leveraging state transitions and probability updates governed by a reward mechanism, significantly reducing dimensionality while maintaining high accuracy. The fitness function $$f(F_{t,s})$$, defined as $$\min_{1 \leq i \leq K} \left( \frac{TP_i}{TP_i + \sum_{j \neq i} FP_{ij}} \right)$$, optimizes classifier performance. Experimental results on ten high-dimensional datasets demonstrate superior accuracy and feature reduction compared to state-of-the-art methods. For instance, on the Lung Cancer dataset, BEV achieved a 100\% classification accuracy with only 12.1 features on average. These results underscore BEV's potential in effectively handling high-dimensional feature selection problems.
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
	url="/assets/projects/BirdsEyeView/bev.png"
	width="100%"
%}
