---
layout: project
title: "Multi-Cluster Jumping Particle Swarm Optimization for Fast Convergence"	
subtitle: "A Novel Approach for Fast Convergence in High-Dimensional Optimization"
---
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

**Abstract.**
The Multi-Cluster Jumping Particle Swarm Optimization (MCJPSO) algorithm significantly improves convergence speed and global search efficiency in high-dimensional optimization problems. The algorithm partitions the particle swarm into clusters, each maintaining its own cluster best position $$c_i(t)$$, and introduces a jumping strategy to escape local minima. Particle velocities are updated as $$v_i(t+1) = \omega v_i(t) + c_1 \text{rand}(p_i(t)$$ $$- x_i(t)) + c_2 \text{rand}(g(t) - x_i(t)) + c_3 \text{rand}(c_i(t) - x_i(t)) + J_i(C_J)$$, where the jump function $$J_i(C_J) = $$ $$\log \left( \frac{C_J}{0.1 \cdot \text{acceptance}} \right)^\alpha \left( \frac{C_J}{0.1 \cdot \text{acceptance}} + 1 \right)^{-1} + \epsilon \text{rand}_N$$ ensures dynamic relocation when stagnation is detected. Semi-random initialization distributes particles across the search space, maximizing exploration. Benchmark tests on twelve functions confirm MCJPSO's superior performance in convergence speed and reliability, making it ideal for large-scale optimization tasks.
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
