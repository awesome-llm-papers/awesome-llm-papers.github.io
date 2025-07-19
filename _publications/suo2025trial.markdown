---
layout: publication
title: 'From Trial To Triumph: Advancing Long Video Understanding Via Visual Context
  Sample Scaling And Self-reward Alignment'
authors: Suo et al.
conference: 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: suo2025trial
citations: 84
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.20472'}]
tags: [Security, Reinforcement Learning, CVPR, Datasets]
---
Multi-modal Large language models (MLLMs) show remarkable ability in video
understanding. Nevertheless, understanding long videos remains challenging as
the models can only process a finite number of frames in a single inference,
potentially omitting crucial visual information. To address the challenge, we
propose generating multiple predictions through visual context sampling,
followed by a scoring mechanism to select the final prediction. Specifically,
we devise a bin-wise sampling strategy that enables MLLMs to generate diverse
answers based on various combinations of keyframes, thereby enriching the
visual context. To determine the final prediction from the sampled answers, we
employ a self-reward by linearly combining three scores: (1) a frequency score
indicating the prevalence of each option, (2) a marginal confidence score
reflecting the inter-intra sample certainty of MLLM predictions, and (3) a
reasoning score for different question types, including clue-guided answering
for global questions and temporal self-refocusing for local questions. The
frequency score ensures robustness through majority correctness, the
confidence-aligned score reflects prediction certainty, and the typed-reasoning
score addresses cases with sparse key visual information using tailored
strategies. Experiments show that this approach covers the correct answer for a
high percentage of long video questions, on seven datasets show that our method
improves the performance of three MLLMs.