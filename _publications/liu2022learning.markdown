---
layout: publication
title: Learning Trajectory-aware Transformer For Video Super-resolution
authors: Liu et al.
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2022
bibkey: liu2022learning
citations: 84
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.04216'}]
tags: [Attention Mechanism, Alt, Evaluation, CVPR, Transformer, Tokenization, Model
    Architecture, Datasets]
---
Video super-resolution (VSR) aims to restore a sequence of high-resolution
(HR) frames from their low-resolution (LR) counterparts. Although some progress
has been made, there are grand challenges to effectively utilize temporal
dependency in entire video sequences. Existing approaches usually align and
aggregate video frames from limited adjacent frames (e.g., 5 or 7 frames),
which prevents these approaches from satisfactory results. In this paper, we
take one step further to enable effective spatio-temporal learning in videos.
We propose a novel Trajectory-aware Transformer for Video Super-Resolution
(TTVSR). In particular, we formulate video frames into several pre-aligned
trajectories which consist of continuous visual tokens. For a query token,
self-attention is only learned on relevant visual tokens along spatio-temporal
trajectories. Compared with vanilla vision Transformers, such a design
significantly reduces the computational cost and enables Transformers to model
long-range features. We further propose a cross-scale feature tokenization
module to overcome scale-changing problems that often occur in long-range
videos. Experimental results demonstrate the superiority of the proposed TTVSR
over state-of-the-art models, by extensive quantitative and qualitative
evaluations in four widely-used video super-resolution benchmarks. Both code
and pre-trained models can be downloaded at
https://github.com/researchmm/TTVSR.