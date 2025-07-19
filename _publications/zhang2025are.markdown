---
layout: publication
title: Are Mlms Trapped In The Visual Room?
authors: Zhang et al.
conference: 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: zhang2025are
citations: 72
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.23272'}]
tags: [RAG, Masked Language Model, Tools, Evaluation, CVPR, Reinforcement Learning,
  Datasets]
---
Can multi-modal large models (MLMs) that can ``see'' an image be said to ``understand'' it? Drawing inspiration from Searle's Chinese Room, we propose the \textbf\{Visual Room\} argument: a system may process and describe every detail of visual inputs by following algorithmic rules, without genuinely comprehending the underlying intention. This dilemma challenges the prevailing assumption that perceptual mastery implies genuine understanding. In implementation, we introduce a two-tier evaluation framework spanning perception and cognition. The perception component evaluates whether MLMs can accurately capture the surface-level details of visual contents, where the cognitive component examines their ability to infer sarcasm polarity. To support this framework, We further introduce a high-quality multi-modal sarcasm dataset comprising both 924 static images and 100 dynamic videos. All sarcasm labels are annotated by the original authors and verified by independent reviewers to ensure clarity and consistency. We evaluate eight state-of-the-art (SoTA) MLMs. Our results highlight three key findings: (1) MLMs demonstrate high accuracy in visual perception; (2) even with correct perception, MLMs exhibit an average error rate of ~17.1% in sarcasm understanding, revealing a significant gap between seeing and understanding; (3) this gap stems from weaknesses in context integration, emotional reasoning, and pragmatic inference. This work provides empirical grounding for the proposed Visual Room argument and offers a new evaluation paradigm for MLMs.