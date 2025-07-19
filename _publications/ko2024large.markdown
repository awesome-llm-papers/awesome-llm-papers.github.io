---
layout: publication
title: Large Language Models Can Be Strong Self-detoxifiers
authors: Ko et al.
conference: Proceedings of the 2023 Conference on Empirical Methods in Natural Language
  Processing
year: 2024
bibkey: ko2024large
citations: 73
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.03818'}]
tags: [RAG, EMNLP, Training Techniques, GPT, Alt, Prompting, Evaluation, Model Architecture,
  Reinforcement Learning, Fine Tuning, Datasets]
---
Reducing the likelihood of generating harmful and toxic output is an
essential task when aligning large language models (LLMs). Existing methods
mainly rely on training an external reward model (i.e., another language model)
or fine-tuning the LLM using self-generated data to influence the outcome. In
this paper, we show that LLMs have the capability of self-detoxification
without the use of an additional reward model or re-training. We propose
\textit\{Self-disciplined Autoregressive Sampling (SASA)\}, a lightweight
controlled decoding algorithm for toxicity reduction of LLMs. SASA leverages
the contextual representations from an LLM to learn linear subspaces
characterizing toxic v.s. non-toxic output in analytical forms. When
auto-completing a response token-by-token, SASA dynamically tracks the margin
of the current output to steer the generation away from the toxic subspace, by
adjusting the autoregressive sampling strategy. Evaluated on LLMs of different
scale and nature, namely Llama-3.1-Instruct (8B), Llama-2 (7B), and GPT2-L
models with the RealToxicityPrompts, BOLD, and AttaQ benchmarks, SASA markedly
enhances the quality of the generated sentences relative to the original models
and attains comparable performance to state-of-the-art detoxification
techniques, significantly reducing the toxicity level by only using the LLM's
internal representations.