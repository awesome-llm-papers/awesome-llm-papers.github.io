---
layout: publication
title: 'Envisioning Beyond The Pixels: Benchmarking Reasoning-informed Visual Editing'
authors: Xiangyu Zhao, Peiyuan Zhang, Kexian Tang, Hao Li, Zicheng Zhang, Guangtao
  Zhai, Junchi Yan, Hua Yang, Xue Yang, Haodong Duan
conference: No Venue
year: 2025
bibkey: zhao2025envisioning
additional_links: [{name: Code, url: 'https://github.com/PhoenixZ810/RISEBench'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/67ef4be4985aa66b67021ef2'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2504.02826'}]
tags: ["Evaluation", "Tools"]
short_authors: Zhao et al.
---
Large Multi-modality Models (LMMs) have made significant progress in visual understanding and generation, but they still face challenges in General Visual Editing, particularly in following complex instructions, preserving appearance consistency, and supporting flexible input formats. To address this gap, we introduce RISEBench, the first benchmark for evaluating Reasoning-Informed viSual Editing (RISE). RISEBench focuses on four key reasoning types: Temporal, Causal, Spatial, and Logical Reasoning. We curate high-quality test cases for each category and propose an evaluation framework that assesses Instruction Reasoning, Appearance Consistency, and Visual Plausibility with both human judges and an LMM-as-a-judge approach. Our experiments reveal that while GPT-4o-Native significantly outperforms other open-source and proprietary models, even this state-of-the-art system struggles with logical reasoning tasks, highlighting an area that remains underexplored. As an initial effort, RISEBench aims to provide foundational insights into reasoning-aware visual editing and to catalyze future research. Though still in its early stages, we are committed to continuously expanding and refining the benchmark to support more comprehensive, reliable, and scalable evaluations of next-generation multimodal systems. Our code and data will be released at https://github.com/PhoenixZ810/RISEBench.

https://huggingface.co/discussions/paper/67ef4be4985aa66b67021ef2