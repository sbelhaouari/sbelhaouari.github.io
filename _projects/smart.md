---
layout: project
title: "Smart Pruning of Deep Neural Networks"	
subtitle: "Efficient Pruning of Deep Neural Networks Using Polynomial Curve Fitting and Evolutionary Algorithms"
---
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

**Abstract.**
This paper explores advanced methods for pruning deep neural networks, leveraging curve fitting and the evolution of weights to enhance model efficiency without significantly sacrificing accuracy. The proposed methodology employs polynomial curve fitting to approximate the weight distribution, followed by an evolutionary algorithm to iteratively refine the pruned model. Formally, given a weight matrix $$W$$, we approximate $$W \approx \sum_{i=0}^{n} a_i x^i$$, where $$a_i$$ are the polynomial coefficients. The evolutionary pruning process iteratively adjusts $$W$$ to minimize the loss function $$L(W)$$, subject to a sparsity constraint $$\|W\|_0 \leq k$$. Experimental results demonstrate that this approach achieves a substantial reduction in model size while maintaining performance metrics comparable to the unpruned network.
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
	url="/assets/projects/SmartPruning/smart.png"
	width="100%"
%}
