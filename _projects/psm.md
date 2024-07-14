---
layout: project
title: "Data Mining of Protein Sequences with Amino Acid Position-Based Feature Encoding Technique"	
subtitle: "Novel Amino Acid Position-Based Encoding for Protein Sequence Classification"
---
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

**Abstract.**
We propose a novel amino acid position-based feature encoding technique for the classification of protein sequences, achieving a significant improvement in classification accuracy. Each amino acid's occurrence positions in a sequence are encoded into a fixed-length numeric feature vector, where the mean $$\mu_{i} = \frac{1}{n} \sum_{j=1}^{n} p_{ij}$$ and variance $$\sigma_{i}^{2} = \frac{1}{n} \sum_{j=1}^{n} (p_{ij} - \mu_{i})^2$$ are computed for each amino acid. Our experiments on Yeast protein sequences using a decision tree classifier yielded a classification accuracy of 85.9%, outperforming previous methods. The proposed technique efficiently encodes sequence data, enabling accurate predictions of protein structure and function from primary sequences. This methodology demonstrates robustness, reliability, and high accuracy, providing a significant advancement in the computational biology domain.
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
	url="/assets/projects/ProteinSequenceMining/psm.png"
	width="100%"
%}
