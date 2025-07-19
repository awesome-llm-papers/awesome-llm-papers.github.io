---
layout: publication
title: How Large Language Models Encode Context Knowledge? A Layer-wise Probing Study
authors: Ju et al.
conference: Nature
year: 2024
bibkey: ju2024how
citations: 1447
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.16061'}]
tags: [RAG, GPT, Model Architecture, Reinforcement Learning, Datasets]
---
Previous work has showcased the intriguing capability of large language
models (LLMs) in retrieving facts and processing context knowledge. However,
only limited research exists on the layer-wise capability of LLMs to encode
knowledge, which challenges our understanding of their internal mechanisms. In
this paper, we devote the first attempt to investigate the layer-wise
capability of LLMs through probing tasks. We leverage the powerful generative
capability of ChatGPT to construct probing datasets, providing diverse and
coherent evidence corresponding to various facts. We employ \\(\mathcal V\\)-usable
information as the validation metric to better reflect the capability in
encoding context knowledge across different layers. Our experiments on
conflicting and newly acquired knowledge show that LLMs: (1) prefer to encode
more context knowledge in the upper layers; (2) primarily encode context
knowledge within knowledge-related entity tokens at lower layers while
progressively expanding more knowledge within other tokens at upper layers; and
(3) gradually forget the earlier context knowledge retained within the
intermediate layers when provided with irrelevant evidence. Code is publicly
available at https://github.com/Jometeorie/probing_llama.