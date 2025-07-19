---
layout: publication
title: 'Mastering Collaborative Multi-modal Data Selection: A Focus On Informativeness,
  Uniqueness, And Representativeness'
authors: Yu et al.
conference: IEEE Transactions on Cybernetics
year: 2024
bibkey: yu2024mastering
citations: 146
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.06293'}]
tags: [Tools, Training Techniques, Fine Tuning, Evaluation, RAG, Ethics and Bias,
  Datasets, Reinforcement Learning]
---
Instruction tuning fine-tunes pre-trained Multi-modal Large Language Models
(MLLMs) to handle real-world tasks. However, the rapid expansion of visual
instruction datasets introduces data redundancy, leading to excessive
computational costs. We propose a collaborative framework, DataTailor, which
leverages three key principles--informativeness, uniqueness, and
representativeness--for effective data selection. We argue that a valuable
sample should be informative of the task, non-redundant, and represent the
sample distribution (i.e., not an outlier). We further propose practical ways
to score against each principle, which automatically adapts to a given dataset
without tedious hyperparameter tuning. Comprehensive experiments on various
benchmarks demonstrate that DataTailor achieves 100.8% of the performance of
full-data fine-tuning with only 15% of the data, significantly reducing
computational costs while maintaining superior results. This exemplifies the
"Less is More" philosophy in MLLM development.