---
layout: publication
title: 'I Have Covered All The Bases Here: Interpreting Reasoning Features In Large
  Language Models Via Sparse Autoencoders'
authors: Andrey Galichin, Alexey Dontsov, Polina Druzhinina, Anton Razzhigaev, Oleg
  Y. Rogov, Elena Tutubalina, Ivan Oseledets
conference: No Venue
year: 2025
bibkey: galichin2025i
additional_links: [{name: Code, url: 'https://github.com/AIRI-Institute/SAE-Reasoning'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/67e25fea8e6c927eb7794b25'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2503.18878'}]
tags: ["Has Code"]
short_authors: Galichin et al.
---
Large Language Models (LLMs) have achieved remarkable success in natural language processing. Recent advances have led to the developing of a new class of reasoning LLMs; for example, open-source DeepSeek-R1 has achieved state-of-the-art performance by integrating deep thinking and complex reasoning. Despite these impressive capabilities, the internal reasoning mechanisms of such models remain unexplored. In this work, we employ Sparse Autoencoders (SAEs), a method to learn a sparse decomposition of latent representations of a neural network into interpretable features, to identify features that drive reasoning in the DeepSeek-R1 series of models. First, we propose an approach to extract candidate ''reasoning features'' from SAE representations. We validate these features through empirical analysis and interpretability methods, demonstrating their direct correlation with the model's reasoning abilities. Crucially, we demonstrate that steering these features systematically enhances reasoning performance, offering the first mechanistic account of reasoning in LLMs. Code available at https://github.com/AIRI-Institute/SAE-Reasoning

https://huggingface.co/discussions/paper/67e25fea8e6c927eb7794b25