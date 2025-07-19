---
layout: publication
title: 'Beyond Generation: Unlocking Universal Editing Via Self-supervised Fine-tuning'
authors: Chen Harold Haodong, Yang Harry, Lim Ser-nam
conference: Trends in Biotechnology
year: 2024
bibkey: chen2024beyond
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.02114'}]
tags: [Training Techniques, Evaluation, Efficiency And Optimization, Fine Tuning,
  Datasets]
---
Recent advances in video generation have outpaced progress in video editing,
which remains constrained by several limiting factors, namely: (a) the task's
dependency on supervision severely limits generality, (b) an unnecessary
artificial separation between the generation and editing task, and (c) the high
computational costs of training a video model. In this work, we propose UES
(Unlocking Universal Editing via Self-Supervision), a lightweight
self-supervised fine-tuning strategy that transforms generation models into
unified generation-editing systems through self-supervised semantic alignment.
Our approach establishes a dual-conditioning mechanism where original
video-text pairs jointly provide visual and textual semantics, enabling
structured learning of intrinsic spatiotemporal correspondences. Key advantages
include: (i) Universality through supervision-free adaptation to diverse
editing tasks, (ii) Unification of generation and editing applicable to most
text(+image)-to-video model, and (iii) Efficiency via lightweight fine-tune
that reduces tunable parameters by 92.67%. To enable systematic evaluation, we
introduce OmniBench-99, a comprehensive benchmark spanning 99 videos across
humans/animals, environments, and objects, comprising 4 editing types and 8
scenarios. Extensive experiments show UES enables models without inherent
editing capability to perform powerful and universal editing while preserving
or even enhancing their original generation performance.