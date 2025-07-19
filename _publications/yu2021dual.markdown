---
layout: publication
title: Dual-branch Attention-in-attention Transformer For Single-channel Speech Enhancement
authors: Yu et al.
conference: ICASSP 2022 - 2022 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)
year: 2021
bibkey: yu2021dual
citations: 55
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.06467'}]
tags: [Attention Mechanism, Transformer, ICASSP, Model Architecture, Time Series]
---
Curriculum learning begins to thrive in the speech enhancement area, which
decouples the original spectrum estimation task into multiple easier sub-tasks
to achieve better performance. Motivated by that, we propose a dual-branch
attention-in-attention transformer dubbed DB-AIAT to handle both coarse- and
fine-grained regions of the spectrum in parallel. From a complementary
perspective, a magnitude masking branch is proposed to coarsely estimate the
overall magnitude spectrum, and simultaneously a complex refining branch is
elaborately designed to compensate for the missing spectral details and
implicitly derive phase information. Within each branch, we propose a novel
attention-in-attention transformer-based module to replace the conventional
RNNs and temporal convolutional networks for temporal sequence modeling.
Specifically, the proposed attention-in-attention transformer consists of
adaptive temporal-frequency attention transformer blocks and an adaptive
hierarchical attention module, aiming to capture long-term temporal-frequency
dependencies and further aggregate global hierarchical contextual information.
Experimental results on Voice Bank + DEMAND demonstrate that DB-AIAT yields
state-of-the-art performance (e.g., 3.31 PESQ, 95.6% STOI and 10.79dB SSNR)
over previous advanced systems with a relatively small model size (2.81M).