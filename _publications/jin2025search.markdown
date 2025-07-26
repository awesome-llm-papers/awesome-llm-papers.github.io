---
layout: publication
title: 'Search-r1: Training Llms To Reason And Leverage Search Engines With Reinforcement
  Learning'
authors: Bowen Jin, Hansi Zeng, Zhenrui Yue, Dong Wang, Hamed Zamani, Jiawei Han
conference: No Venue
year: 2025
bibkey: jin2025search
additional_links: [{name: Code, url: 'https://github.com/PeterGriffinJin/Search-R1'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/67d238ae7d0fc37e671feb7c'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2503.09516'}]
tags: ["Has Code", "RAG", "Reinforcement Learning", "Training Techniques"]
short_authors: Jin et al.
---
Efficiently acquiring external knowledge and up-to-date information is essential for effective reasoning and text generation in large language models (LLMs). Retrieval augmentation and tool-use training approaches where a search engine is treated as a tool lack complex multi-turn retrieval flexibility or require large-scale supervised data. Prompting advanced LLMs with reasoning capabilities during inference to use search engines is not optimal, since the LLM does not learn how to optimally interact with the search engine. This paper introduces Search-R1, an extension of the DeepSeek-R1 model where the LLM learns -- solely through reinforcement learning (RL) -- to autonomously generate (multiple) search queries during step-by-step reasoning with real-time retrieval. Search-R1 optimizes LLM rollouts with multi-turn search interactions, leveraging retrieved token masking for stable RL training and a simple outcome-based reward function. Experiments on seven question-answering datasets show that Search-R1 improves performance by 26% (Qwen2.5-7B), 21% (Qwen2.5-3B), and 10% (LLaMA3.2-3B) over SOTA baselines. This paper further provides empirical insights into RL optimization methods, LLM choices, and response length dynamics in retrieval-augmented reasoning. The code and model checkpoints are available at https://github.com/PeterGriffinJin/Search-R1.

https://huggingface.co/discussions/paper/67d238ae7d0fc37e671feb7c