---
layout: project
title: "A novel Time-Frequency decomposition"	
subtitle: "Transforming Time Series into Richer Images for Enhanced Classification"
---
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

**Abstract.**
This thesis explores significant advancements in EEG signal processing to enhance the understanding of brain function and dysfunction. It begins with an examination of EEG signal acquisition, preprocessing, and feature extraction, comparing various state-of-the-art methods for noise reduction, artifact removal, and feature selection. The integration of advanced machine learning algorithms, such as deep learning models, is investigated to improve the accuracy and efficiency of EEG analysis. The study aims to develop innovative strategies for deciphering EEG patterns associated with neurological conditions like epilepsy, Parkinson’s disease, Alzheimer’s, murmur, and stress disorders, presenting several case studies. Emphasizing real-time EEG analysis, the research also paves the way for wearable EEG devices for continuous brain activity monitoring, potentially revolutionizing healthcare through early detection and personalized treatment plans. By leveraging cutting-edge techniques, the thesis advances the understanding of neurological disorders, leading to more accurate diagnoses and improved patient care.
<br/> &nbsp;&nbsp;&nbsp;&nbsp;
<!-- In this work, we propose a new experimental design for testing whether SUTVA holds, without making any assumptions on how treatment effects may spill over between the treatment and the control group.
To achieve this, we simultaneously run both a completely randomized and a cluster-based randomized experiment, and then we compare the difference of the resulting estimates. We present a statistical test for measuring the significance of this difference and offer theoretical bounds on the Type I error rate.
<br/> &nbsp;&nbsp;&nbsp;&nbsp;
We provide practical guidelines for implementing our methodology on large-scale experimentation platforms.
Importantly, the proposed methodology can be applied to settings in which a network is not necessarily observed but, if available, can be used in the analysis.
Finally, we deploy this design to LinkedIn's experimentation platform and apply it to two online experiments, highlighting the presence of network effects and bias in standard A/B testing approaches in a real-world setting. -->

This work is part of a multi-paper series.
In the thesis <a href="https://www.proquest.com/docview/2869193924?pq-origsite=gscholar&fromopenview=true&sourcetype=Dissertations%20&%20Theses" target="_blank">thesis</a> we introduce the methodology and main results of Progressive Fourier Transform, we give another implementation in this <a href="https://ieeexplore.ieee.org/document/10385485/authors#authors" target="_blank">paper</a>. We then take the idea further in the form of Forward–Backward Fourier transform  in this <a href="https://www.nature.com/articles/s41598-024-54416-y" target="_blank">paper</a>.

**Illustration of the proposed experimental design.** <br/>
{%
	include image_with_caption.html
	url="/assets/projects/TimeFreqDecom/TFD.png"
	width="100%"
%}
<!-- **(A)** Graph of all units and the connections between them; the dashed circles represent (equally-sized) clusters. <br/>
**(B)** Assigning clusters to treatment arms: completely randomized (CR) and cluster-based randomized assignment (CBR). <br/>
**(C)** Assigning units to treatment buckets---treatment and control---using the corresponding strategy. <br/>
**(D)** Computing the treatment effect within each treatment arm: $$\hat \mu_{cr}$$ and $$\hat \mu_{cbr}$$, and variance: $$\hat \sigma^2_{cr}$$ and $$\hat \sigma^2_{cbr}$$. <br/>
**(E)** Computing the difference of the estimates from each treatment arm: $$\Delta = \hat \mu_{cr} - \hat \mu_{cbr}$$, and the total variance: $$\hat \sigma^2 = \hat \sigma^2_{cr} + \hat \sigma^2_{cbr}$$. <br/> -->

<!-- **Short video describing the work. Recorded for KDD'17.** <br/>
<iframe width="560" height="315" src="https://www.youtube.com/embed/E3yiKJCgLE4" frameborder="0" allowfullscreen></iframe> -->
