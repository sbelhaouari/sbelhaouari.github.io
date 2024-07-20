---
layout: project
title: "IJCB 2022 Mobile Behavioral Biometrics Competition (MobileB2C)"	
subtitle: "Benchmarking Mobile Behavioral Biometrics for Continuous Authentication"
---
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

**Abstract.**
This paper details the IJCB 2022 Mobile Behavioral Biometrics Competition (MobileB2C), which benchmarks mobile user authentication systems using behavioral biometric traits acquired during typical Human-Computer Interaction (HCI). The competition utilized the BehavePassDB database and involved four tasks: keystroke, text reading, gallery swiping, and tapping, incorporating data from touchscreen and background sensors. The HBKU CS Lab Team employed a novel approach using Discrete Wavelet Transform (DWT) to deconstruct signals into wavelet-basis functions. Let the wavelet transform be denoted as $$D[a, b] = \frac{1}{\sqrt{b}} \sum_{m=0}^{p-1} f[tm] \phi \left(\frac{tm - a}{b}\right)$$ where \(a\) and \(b\) are integers representing translation and compression, respectively. Post DWT, the data are recursively averaged and transformed into image representations, which are input into a siamese neural network with contrastive loss, represented by $$c_{A_j}^i, c_{B_j}^i = W(D_j^i)$$. This method demonstrated superior performance in gallery swiping and tapping tasks with AUC scores of 61.54% and 59.58%, respectively, confirming the efficacy of the proposed biometric authentication system.
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
	url="/assets/projects/IJCB2022/ijcb.png"
	width="100%"
%}
