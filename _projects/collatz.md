---
layout: project
title: "From Collatz Conjecture to chaos and hash function"	
subtitle: "Leveraging Chaotic Systems for Enhanced Hash Functions in Cryptographic Applications"
---
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

**Abstract.**
The nonlinear properties of chaos present promising approaches for enhancing cryptographic systems. This study introduces a novel chaos-based hash function leveraging the Collatz Conjecture, sine infinity, and chaos theory. The function, defined as:
$$
x_{n+1} = 10M \cdot 
\begin{cases} 
R_K (f(x_n) \sin(g(x_n)) + x_n) & \text{if } x_n \in (R - Z) \\
\left(\frac{x_n}{2^j}\right) \cdot P_{2j+1} & \text{if } \text{mod}(x_n, 2^j) = 0, 3 \leq j \leq 5 \\
\left(R(f(x_n)) \sin(g(x_n))\right) + x_n & \text{if } \text{mod}(x_n, 2^2) = 0 \\
\left(\frac{x_n}{2}\right) \cdot P_2 + 1 & \text{if } \text{mod}(x_n, 2) = 0 \\
x_n \cdot P_{\text{mod}(x_n, NP)} + 1 & \text{if } \text{mod}(x_n, 2) = 1
\end{cases}
$$
\\
enhances ergodicity and entropy, crucial for cryptographic applications. Performance evaluations indicate superior collision resistance and uniformity compared to SHA-2 and SHA-3. The proposed hash function achieves an average hamming distance of 50.33\% and exhibits robust security properties under various datasets and conditions.
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
	url="/assets/projects/CollatzHash/collatz.png"
	width="100%"
%}
