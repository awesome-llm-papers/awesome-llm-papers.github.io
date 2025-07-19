---
layout: publication
title: Detecting Benchmark Contamination Through Watermarking
authors: Sander et al.
conference: 'Proceedings International Conference on Information Technology: Coding
  and Computing'
year: 2025
bibkey: sander2025detecting
citations: 64
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.17259'}]
tags: [Training Techniques, Alt, Evaluation, Datasets]
---
Benchmark contamination poses a significant challenge to the reliability of
Large Language Models (LLMs) evaluations, as it is difficult to assert whether
a model has been trained on a test set. We introduce a solution to this problem
by watermarking benchmarks before their release. The embedding involves
reformulating the original questions with a watermarked LLM, in a way that does
not alter the benchmark utility. During evaluation, we can detect
``radioactivity'', \ie traces that the text watermarks leave in the model
during training, using a theoretically grounded statistical test. We test our
method by pre-training 1B models from scratch on 10B tokens with controlled
benchmark contamination, and validate its effectiveness in detecting
contamination on ARC-Easy, ARC-Challenge, and MMLU. Results show similar
benchmark utility post-watermarking and successful contamination detection when
models are contaminated enough to enhance performance, e.g. \\(p\\)-val \\(=10^\{-3\}\\)
for +5\\(%\\) on ARC-Easy.