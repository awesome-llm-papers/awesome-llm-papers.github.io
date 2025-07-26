---
layout: publication
title: 'How Instruction And Reasoning Data Shape Post-training: Data Quality Through
  The Lens Of Layer-wise Gradients'
authors: Ming Li, Yanhong Li, Ziyue Li, Tianyi Zhou
conference: No Venue
year: 2025
bibkey: li2025how
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2504.10766'}]
tags: ["Training Techniques"]
short_authors: Li et al.
---
As the post-training of large language models (LLMs) advances from instruction-following to complex reasoning tasks, understanding how different data affect finetuning dynamics remains largely unexplored. In this paper, we present a spectral analysis of layer-wise gradients induced by low/high-quality instruction and reasoning data for LLM post-training. Our analysis reveals that widely-studied metrics for data evaluation, e.g., IFD, InsTag, Difficulty, and Reward, can be explained and unified by spectral properties computed from gradients' singular value decomposition (SVD). Specifically, higher-quality data are usually associated with lower nuclear norms and higher effective ranks. Notably, effective rank exhibits better robustness and resolution than nuclear norm in capturing subtle quality differences. For example, reasoning data achieves substantially higher effective ranks than instruction data, implying richer gradient structures on more complex tasks. Our experiments also highlight that models within the same family share similar gradient patterns regardless of their sizes, whereas different model families diverge significantly. Providing a unified view on the effects of data quality across instruction and reasoning data, this work illuminates the interplay between data quality and training stability, shedding novel insights into developing better data exploration strategies for post-training.

https://huggingface.co/discussions/paper/67ff11503026f8abc4bf7fed