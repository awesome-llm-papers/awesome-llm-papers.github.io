---
layout: publication
title: Are Vision Llms Road-ready? A Comprehensive Benchmark For Safety-critical Driving
  Video Understanding
authors: Zeng et al.
conference: 2012 IEEE Conference on Computer Vision and Pattern Recognition
year: 2025
bibkey: zeng2025are
citations: 9882
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.14526'}]
tags: [Datasets, Tools, Evaluation, CVPR, Reinforcement Learning, Security, Applications,
  Multimodal Models, Responsible AI]
---
Vision Large Language Models (VLLMs) have demonstrated impressive
capabilities in general visual tasks such as image captioning and visual
question answering. However, their effectiveness in specialized,
safety-critical domains like autonomous driving remains largely unexplored.
Autonomous driving systems require sophisticated scene understanding in complex
environments, yet existing multimodal benchmarks primarily focus on normal
driving conditions, failing to adequately assess VLLMs' performance in
safety-critical scenarios. To address this, we introduce DVBench, a pioneering
benchmark designed to evaluate the performance of VLLMs in understanding
safety-critical driving videos. Built around a hierarchical ability taxonomy
that aligns with widely adopted frameworks for describing driving scenarios
used in assessing highly automated driving systems, DVBench features 10,000
multiple-choice questions with human-annotated ground-truth answers, enabling a
comprehensive evaluation of VLLMs' capabilities in perception and reasoning.
Experiments on 14 SOTA VLLMs, ranging from 0.5B to 72B parameters, reveal
significant performance gaps, with no model achieving over 40% accuracy,
highlighting critical limitations in understanding complex driving scenarios.
To probe adaptability, we fine-tuned selected models using domain-specific data
from DVBench, achieving accuracy gains ranging from 5.24 to 10.94 percentage
points, with relative improvements of up to 43.59%. This improvement
underscores the necessity of targeted adaptation to bridge the gap between
general-purpose VLLMs and mission-critical driving applications. DVBench
establishes an essential evaluation framework and research roadmap for
developing VLLMs that meet the safety and robustness requirements for
real-world autonomous systems. We released the benchmark toolbox and the
fine-tuned model at: https://github.com/tong-zeng/DVBench.git.