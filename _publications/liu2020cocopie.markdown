---
layout: publication
title: 'Cocopie: Making Mobile AI Sweet As PIE --compression-compilation Co-design
  Goes A Long Way'
authors: Liu et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2020
bibkey: liu2020cocopie
citations: 59
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2003.06700'}]
tags: [Tools, Transformer, Model Architecture, Efficiency And Optimization, Reinforcement
    Learning, Applications, AAAI, Pruning]
---
Assuming hardware is the major constraint for enabling real-time mobile
intelligence, the industry has mainly dedicated their efforts to developing
specialized hardware accelerators for machine learning and inference. This
article challenges the assumption. By drawing on a recent real-time AI
optimization framework CoCoPIE, it maintains that with effective
compression-compiler co-design, it is possible to enable real-time artificial
intelligence on mainstream end devices without special hardware. CoCoPIE is a
software framework that holds numerous records on mobile AI: the first
framework that supports all main kinds of DNNs, from CNNs to RNNs, transformer,
language models, and so on; the fastest DNN pruning and acceleration framework,
up to 180X faster compared with current DNN pruning on other frameworks such as
TensorFlow-Lite; making many representative AI applications able to run in
real-time on off-the-shelf mobile devices that have been previously regarded
possible only with special hardware support; making off-the-shelf mobile
devices outperform a number of representative ASIC and FPGA solutions in terms
of energy efficiency and/or performance.