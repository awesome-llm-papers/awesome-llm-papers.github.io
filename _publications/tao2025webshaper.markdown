---
layout: publication
title: 'Webshaper: Agentically Data Synthesizing Via Information-seeking Formalization'
authors: Zhengwei Tao, Jialong Wu, Wenbiao Yin, Junkai Zhang, Baixuan Li, Haiyang
  Shen, Kuan Li, Liwen Zhang, Xinyu Wang, Yong Jiang, Pengjun Xie, Fei Huang, Jingren
  Zhou
conference: No Venue
year: 2025
bibkey: tao2025webshaper
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2507.15061'}]
tags: ["Agentic", "Tools"]
short_authors: Tao et al.
---
The advent of Large Language Model (LLM)-powered agents has revolutionized artificial intelligence by enabling solutions to complex, open-ended tasks through web-based information-seeking (IS) capabilities. The scarcity of high-quality training data has limited the development of IS agents. Existing approaches typically adopt an information-driven paradigm that first collects web data and then generates questions based on the retrieval. However, this may lead to inconsistency between information structure and reasoning structure, question and answer. To mitigate, we propose a formalization-driven IS data synthesis framework WebShaper to construct a dataset. WebShaper systematically formalizes IS tasks through set theory. Central to the formalization is the concept of Knowledge Projections (KP), which enables precise control over reasoning structure by KP operation compositions. During synthesis, we begin by creating seed tasks, then use a multi-step expansion process. At each step, an agentic Expander expands the current formal question more complex with retrieval and validation tools based on our formalization. We train our model on the synthesized dataset. Experiment results demonstrate that WebShaper achieves state-of-the-art performance among open-sourced IS agents on GAIA and WebWalkerQA benchmarks.

https://huggingface.co/discussions/paper/687ef39133947f780d9b4a8c