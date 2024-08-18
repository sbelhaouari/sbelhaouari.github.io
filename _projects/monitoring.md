---
layout: project
title: "An Efficient Wireless Sensor Network-based Water Quality Monitoring System"	
subtitle: "Reusable, Energy-Efficient WSN for Real-Time Water Quality Monitoring"
---
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

**Abstract.**
This paper presents a reusable, self-configurable, and energy-efficient Wireless Sensor Network (WSN)-based water quality monitoring system. The proposed framework employs Zigbee-based sensor motes and integrates a Web-based information portal with a sleep scheduling mechanism to enhance network lifetime. Experimental results demonstrate the real-time monitoring capability and the effectiveness of the sleep scheduling mechanism in extending network longevity. Unique contributions include the design of a multi-hop routing protocol, $$ E = \sum_{i=1}^{n} \frac{P_i \cdot T_i}{L_i} $$, optimizing data aggregation and communication, and the implementation of an energy-efficient sleep schedule $$ S = \sqrt[n]{\prod_{i=1}^{n} \frac{U_i}{V_i}} $$ to minimize power consumption. Simulation results validate that the framework significantly outperforms traditional WSNs in terms of network lifetime and real-time data accuracy.
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
	url="/assets/projects/WaterQualityMonitoring/monitoring.png"
	width="100%"
%}
