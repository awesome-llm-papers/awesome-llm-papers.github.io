---
layout: publication
title: 'Humaneval-v: Benchmarking High-level Visual Reasoning With Complex Diagrams
  In Coding Tasks'
authors: Fengji Zhang, Linquan Wu, Huiyu Bai, Guancheng Lin, Xiao Li, Xiao Yu, Yue
  Wang, Bei Chen, Jacky Keung
conference: No Venue
year: 2024
bibkey: zhang2024humaneval
additional_links: [{name: Code, url: 'https://github.com/HumanEval-V/HumanEval-V-Benchmark'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/67107f90de5ba28c43c8c510'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2410.12381'}]
tags: ["Datasets", "Evaluation"]
short_authors: Zhang et al.
---
Understanding and reasoning over diagrams is a fundamental aspect of human intelligence. While Large Multimodal Models (LMMs) have demonstrated impressive capabilities across various tasks, existing benchmarks lack comprehensive evaluation of their diagram interpretation and reasoning abilities, particularly in coding contexts. We present HumanEval-V, a rigorous benchmark of human-annotated coding tasks that spans six task types and evaluates diverse visual reasoning capabilities. Each task features carefully crafted diagrams paired with function signatures and test cases, employing novel code generation tasks to thoroughly assess models' diagram comprehension. Through extensive experiments with 22 LMMs, we find that even top-performing models achieve modest success rates, with Claude 3.5 Sonnet reaching only 36.8% pass@1, highlighting substantial room for improvement. Our analysis reveals that current LMMs struggle with spatial transformations, topological relationships, and dynamic patterns that humans find intuitive. These findings provide valuable insights for advancing LMMs' visual reasoning abilities. We have open-sourced our code and benchmark at https://github.com/HumanEval-V/HumanEval-V-Benchmark.

https://huggingface.co/discussions/paper/67107f90de5ba28c43c8c510