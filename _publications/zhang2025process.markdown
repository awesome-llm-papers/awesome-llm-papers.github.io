---
layout: publication
title: Process-based Self-rewarding Language Models
authors: Shimao Zhang, Xiao Liu, Xin Zhang, Junxiao Liu, Zheheng Luo, Shujian Huang,
  Yeyun Gong
conference: No Venue
year: 2025
bibkey: zhang2025process
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2503.03746'}]
tags: ["Efficiency", "Training Techniques"]
short_authors: Zhang et al.
---
Large Language Models have demonstrated outstanding performance across various downstream tasks and have been widely applied in multiple scenarios. Human-annotated preference data is used for training to further improve LLMs' performance, which is constrained by the upper limit of human performance. Therefore, Self-Rewarding method has been proposed, where LLMs generate training data by rewarding their own outputs. However, the existing self-rewarding paradigm is not effective in mathematical reasoning scenarios and may even lead to a decline in performance. In this work, we propose the Process-based Self-Rewarding pipeline for language models, which introduces long-thought reasoning, step-wise LLM-as-a-Judge, and step-wise preference optimization within the self-rewarding paradigm. Our new paradigm successfully enhances the performance of LLMs on multiple mathematical reasoning benchmarks through iterative Process-based Self-Rewarding, demonstrating the immense potential of self-rewarding to achieve LLM reasoning that may surpass human capabilities.

https://huggingface.co/discussions/paper/67c991abe7dba9cdf9f41e96