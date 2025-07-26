---
layout: publication
title: 'Stop Overthinking: A Survey On Efficient Reasoning For Large Language Models'
authors: Yang Sui, Yu-neng Chuang, Guanchu Wang, Jiamu Zhang, Tianyi Zhang, Jiayi
  Yuan, Hongyi Liu, Andrew Wen, Shaochen, Zhong, Hanjie Chen, Xia Hu
conference: No Venue
year: 2025
bibkey: sui2025stop
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2503.16419'}]
tags: ["Efficiency", "Survey Paper"]
short_authors: Sui et al.
---
Large Language Models (LLMs) have demonstrated remarkable capabilities in complex tasks. Recent advancements in Large Reasoning Models (LRMs), such as OpenAI o1 and DeepSeek-R1, have further improved performance in System-2 reasoning domains like mathematics and programming by harnessing supervised fine-tuning (SFT) and reinforcement learning (RL) techniques to enhance the Chain-of-Thought (CoT) reasoning. However, while longer CoT reasoning sequences improve performance, they also introduce significant computational overhead due to verbose and redundant outputs, known as the "overthinking phenomenon". In this paper, we provide the first structured survey to systematically investigate and explore the current progress toward achieving efficient reasoning in LLMs. Overall, relying on the inherent mechanism of LLMs, we categorize existing works into several key directions: (1) model-based efficient reasoning, which considers optimizing full-length reasoning models into more concise reasoning models or directly training efficient reasoning models; (2) reasoning output-based efficient reasoning, which aims to dynamically reduce reasoning steps and length during inference; (3) input prompts-based efficient reasoning, which seeks to enhance reasoning efficiency based on input prompt properties such as difficulty or length control. Additionally, we introduce the use of efficient data for training reasoning models, explore the reasoning capabilities of small language models, and discuss evaluation methods and benchmarking.

https://huggingface.co/discussions/paper/67dcdbfd71027d42fa46e439