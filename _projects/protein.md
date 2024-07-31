---
layout: project
title: "Efficient Feature Selection and Classification of Protein Sequence Data in Bioinformatics"	
subtitle: "Enhanced Accuracy in Protein Classification via Statistical Metric-Based Feature Selection"
---
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

**Abstract.**
Bioinformatics requires efficient classification of protein sequences to predict their structure and function. We propose a statistical metric-based feature selection technique combined with an n-gram encoding method to improve classification accuracy. Protein sequences are encoded using descriptors of lengths 1, 2, and 3 amino acids, resulting in a feature vector space $$ \mathbf{X} = \{X_1, X_2, \ldots, X_{8420}\} $$. The statistical metric for feature selection is defined as $$ V_d (j) = \min_{p \neq q} \left\{ \frac{|X_p(j) - X_q(j)|}{\sqrt{\frac{S_p^2(j)}{N_{\text{Total}}} + \frac{S_q^2(j)}{N_{\text{Total}}}}} \right\} $$, where $$ S^2_i(j) $$ represents the variance of the $$j$$-th feature in the $$i$$-th superfamily. This technique reduces feature dimensionality and enhances classification accuracy by approximately 15% to 20% across various datasets, outperforming traditional alignment-based methods. Experimental results on datasets from the UniProt database demonstrate the effectiveness of our approach, achieving an accuracy of up to 96% with neural network classifiers.
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
	url="/assets/projects/ProteinFeatureSelection/protein.png"
	width="100%"
%}
