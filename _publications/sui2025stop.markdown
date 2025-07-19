---
layout: publication
title: 'Stop Overthinking: A Survey On Efficient Reasoning For Large Language Models'
authors: Sui et al.
conference: 'Findings of the Association for Computational Linguistics: ACL 2023'
year: 2025
bibkey: sui2025stop
citations: 153
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.16419'}]
tags: [Prompting, Survey Paper, Training Techniques, Efficiency And Optimization,
  Evaluation, Fine Tuning, Agentic, ACL, Datasets, Reinforcement Learning]
---
Large Language Models (LLMs) have demonstrated remarkable capabilities in
complex tasks. Recent advancements in Large Reasoning Models (LRMs), such as
OpenAI o1 and DeepSeek-R1, have further improved performance in System-2
reasoning domains like mathematics and programming by harnessing supervised
fine-tuning (SFT) and reinforcement learning (RL) techniques to enhance the
Chain-of-Thought (CoT) reasoning. However, while longer CoT reasoning sequences
improve performance, they also introduce significant computational overhead due
to verbose and redundant outputs, known as the "overthinking phenomenon". In
this paper, we provide the first structured survey to systematically
investigate and explore the current progress toward achieving efficient
reasoning in LLMs. Overall, relying on the inherent mechanism of LLMs, we
categorize existing works into several key directions: (1) model-based
efficient reasoning, which considers optimizing full-length reasoning models
into more concise reasoning models or directly training efficient reasoning
models; (2) reasoning output-based efficient reasoning, which aims to
dynamically reduce reasoning steps and length during inference; (3) input
prompts-based efficient reasoning, which seeks to enhance reasoning efficiency
based on input prompt properties such as difficulty or length control.
Additionally, we introduce the use of efficient data for training reasoning
models, explore the reasoning capabilities of small language models, and
discuss evaluation methods and benchmarking.