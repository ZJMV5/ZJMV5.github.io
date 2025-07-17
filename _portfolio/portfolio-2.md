---
title: "Joint angle-range estimation for the wideband sonar based on atomic norm minimization"
excerpt: "<img src='/images/阵列示意图_eng.png'>"
collection: portfolio
---

In order to achieve two-dimensional localization with wideband sonar, the joint angle-range estimation for
wideband LFM pulse sonar was studied. Based on the atomic norm minimization theory, gridless joint
angle-range estimation algorithms were proposed for both single-pulse and multi-pulse scenarios. Simulation
results showed that the proposed gridless algorithms can effectively suppress the impact of aliasing. Furthermore, since they are not affected by grid mismatch, they outperform the grid-based algorithms at high SNRs.
The proposed multi-pulse algorithm successfully eliminates the influence of range migration, achieves coherent accumulation across multiple pulses, and performs better than the single-pulse algorithm, especially
at low SNRs.

> **Remark**: From the viewpoint of the signal model, this work can be viewed as an extension of the [previous study](https://zjmv5.github.io/portfolio/portfolio-1/), where the frequencies of the received  signals were assumed to be low. In this study, the frequencies were much higher and exhibited band-pass properties.  Although the techniques developed in the previous study can also be applied to this scenario, their complexity is too high for implementation. To address this problem, we designed a novel mapping operator that greatly reduces the complexity of the algorithm and thus facilitates its implementation.

 The main ideas and results are presented in my Master’s thesis. Recently, I have been adding more details and preparing to organize this work into a journal paper.
