---
layout: publication
title: 'Bielik V3 Small: Technical Report'
authors: "Krzysztof Ociepa, \u0141ukasz Flis, Remigiusz Kinas, Krzysztof Wr\xF3bel,\
  \ Adrian Gwo\u017Adziej"
conference: No Venue
year: 2025
bibkey: ociepa2025bielik
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2505.02550'}]
tags: ["Applications", "Datasets", "Efficiency", "Evaluation", "Training Techniques"]
short_authors: Ociepa et al.
---
We introduce Bielik v3, a series of parameter-efficient generative text models (1.5B and 4.5B) optimized for Polish language processing. These models demonstrate that smaller, well-optimized architectures can achieve performance comparable to much larger counterparts while requiring substantially fewer computational resources. Our approach incorporates several key innovations: a custom Polish tokenizer (APT4) that significantly improves token efficiency, Weighted Instruction Cross-Entropy Loss to balance learning across instruction types, and Adaptive Learning Rate that dynamically adjusts based on training progress. Trained on a meticulously curated corpus of 292 billion tokens spanning 303 million documents, these models excel across multiple benchmarks, including the Open PL LLM Leaderboard, Complex Polish Text Understanding Benchmark, Polish EQ-Bench, and Polish Medical Leaderboard. The 4.5B parameter model achieves results competitive with models 2-3 times its size, while the 1.5B model delivers strong performance despite its extremely compact profile. These advances establish new benchmarks for parameter-efficient language modeling in less-represented languages, making high-quality Polish language AI more accessible for resource-constrained applications.

https://huggingface.co/discussions/paper/6819ef0c2ff435c58da4d892