---
layout: publication
title: 'Kodcode: A Diverse, Challenging, And Verifiable Synthetic Dataset For Coding'
authors: Zhangchen Xu, Yang Liu, Yueqin Yin, Mingyuan Zhou, Radha Poovendran
conference: No Venue
year: 2025
bibkey: xu2025kodcode
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67c907ee7568a12737ad4633'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2503.02951'}]
tags: ["Datasets"]
short_authors: Xu et al.
---
We introduce KodCode, a synthetic dataset that addresses the persistent challenge of acquiring high-quality, verifiable training data across diverse difficulties and domains for training Large Language Models for coding. Existing code-focused resources typically fail to ensure either the breadth of coverage (e.g., spanning simple coding tasks to advanced algorithmic problems) or verifiable correctness (e.g., unit tests). In contrast, KodCode comprises question-solution-test triplets that are systematically validated via a self-verification procedure. Our pipeline begins by synthesizing a broad range of coding questions, then generates solutions and test cases with additional attempts allocated to challenging problems. Finally, post-training data synthesis is done by rewriting questions into diverse formats and generating responses under a test-based reject sampling procedure from a reasoning model (DeepSeek R1). This pipeline yields a large-scale, robust and diverse coding dataset. KodCode is suitable for supervised fine-tuning and the paired unit tests also provide great potential for RL tuning. Fine-tuning experiments on coding benchmarks (HumanEval(+), MBPP(+), BigCodeBench, and LiveCodeBench) demonstrate that KodCode-tuned models achieve state-of-the-art performance, surpassing models like Qwen2.5-Coder-32B-Instruct and DeepSeek-R1-Distill-Llama-70B.

https://huggingface.co/discussions/paper/67c907ee7568a12737ad4633