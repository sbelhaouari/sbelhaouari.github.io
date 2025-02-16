---
layout: project
title: "Bio-Inspired Adaptive Neurons For Dynamic Weighting In Artificial Neural Networks"	
subtitle: "Bridging the Gap Between Biological and Artificial Neurons Through Adaptive Weighting"
---
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

**Abstract.**
Traditional neural networks employ fixed weights during inference, limiting their ability to adapt to changing input conditions, unlike biological neurons that adjust signal strength dynamically based on stimuli. This discrepancy between artificial and biological neurons constrains neural network flexibility and adaptability. To bridge this gap, we propose a novel framework for adaptive neural networks, where neuron weights are modeled as functions of the input signal, allowing the network to adjust dynamically in real-time. Importantly, we achieve this within the same traditional architecture of an Artificial Neural Network, maintaining structural familiarity while introducing dynamic adaptability. In our research, we apply Chebyshev polynomials as one of the many possible decomposition methods to achieve this adaptive weighting mechanism, with polynomial coefficients learned during training.  Out of the 145 datasets tested, our adaptive Chebyshev neural network demonstrated a marked improvement over an equivalent MLP in approximately 83% of cases, performing strictly better on 121 datasets. In the remaining 24 datasets, the performance of our algorithm matched that of the MLP, highlighting its ability to generalize standard neural network behavior while offering enhanced adaptability. As a generalized form of the MLP, this model seamlessly retains MLP performance where needed while extending its capabilities to achieve superior accuracy across a wide range of complex tasks. These results underscore the potential of adaptive neurons to enhance generalization, flexibility, and robustness in neural networks, particularly in applications with dynamic or non-linear data dependencies.
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

**Comparison of decision boundaries** <br/>
{%
	include image_with_caption.html
	url="/assets/projects/inputDepWeighting/saheart_combined_plot.png"
	width="100%"
%}

The top row displays the actual class distribution, followed by the decision boundaries of the MLP and Chebyshev models. The bottom row shows misclassifications for each model, with pink regions indicating errors.