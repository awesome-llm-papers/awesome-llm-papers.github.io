---
layout: publication
title: Wait, We Don't Need To "wait"! Removing Thinking Tokens Improves Reasoning
  Efficiency
authors: Chenlong Wang, Yuanning Feng, Dongping Chen, Zhaoyang Chu, Ranjay Krishna,
  Tianyi Zhou
conference: No Venue
year: 2025
bibkey: wang2025wait
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.08343'}]
tags: ["Efficiency"]
short_authors: Wang et al.
---
Recent advances in large reasoning models have enabled complex, step-by-step reasoning but often introduce significant overthinking, resulting in verbose and redundant outputs that hinder efficiency. In this study, we examine whether explicit self-reflection, signaled by tokens such as "Wait" and "Hmm", is necessary for advanced reasoning. We propose NoWait, a simple yet effective approach that disables explicit self-reflection by suppressing these tokens during inference. Extensive experiments on ten benchmarks across textual, visual, and video reasoning tasks show that NoWait reduces chain-of-thought trajectory length by up to 27%-51% in five R1-style model series, without compromising model utility. NoWait thus offers a plug-and-play solution for efficient and utility-preserving multimodal reasoning.

https://huggingface.co/discussions/paper/684ae1f5dbd21a9cc27b0f40