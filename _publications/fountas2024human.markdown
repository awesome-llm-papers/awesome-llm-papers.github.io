---
layout: publication
title: Human-like Episodic Memory For Infinite Context Llms
authors: Zafeirios Fountas, Martin A Benfeghoul, Adnan Oomerjee, Fenia Christopoulou,
  Gerasimos Lampouras, Haitham Bou-ammar, Jun Wang
conference: No Venue
year: 2024
bibkey: fountas2024human
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2407.09450'}]
tags: ["Memory & Context"]
short_authors: Fountas et al.
---
Large language models (LLMs) have shown remarkable capabilities, but still struggle with processing extensive contexts, limiting their ability to maintain coherence and accuracy over long sequences. In contrast, the human brain excels at organising and retrieving episodic experiences across vast temporal scales, spanning a lifetime. In this work, we introduce EM-LLM, a novel approach that integrates key aspects of human episodic memory and event cognition into LLMs, enabling them to effectively handle practically infinite context lengths while maintaining computational efficiency. EM-LLM organises sequences of tokens into coherent episodic events using a combination of Bayesian surprise and graph-theoretic boundary refinement in an on-line fashion. When needed, these events are retrieved through a two-stage memory process, combining similarity-based and temporally contiguous retrieval for efficient and human-like access to relevant information. Experiments on the LongBench dataset demonstrate EM-LLM's superior performance, outperforming the state-of-the-art InfLLM model with an overall relative improvement of 4.3% across various tasks, including a 33% improvement on the PassageRetrieval task. Furthermore, our analysis reveals strong correlations between EM-LLM's event segmentation and human-perceived events, suggesting a bridge between this artificial system and its biological counterpart. This work not only advances LLM capabilities in processing extended contexts but also provides a computational framework for exploring human memory mechanisms, opening new avenues for interdisciplinary research in AI and cognitive science.

https://huggingface.co/discussions/paper/66948c1c3cd89359e445218e