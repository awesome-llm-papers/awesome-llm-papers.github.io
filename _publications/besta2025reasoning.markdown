---
layout: publication
title: 'Reasoning Language Models: A Blueprint'
authors: "Maciej Besta, Julia Barth, Eric Schreiber, Ales Kubicek, Afonso Catarino,\
  \ Robert Gerstenberger, Piotr Nyczyk, Patrick Iff, Yueling Li, Sam Houliston, Tomasz\
  \ Sternal, Marcin Copik, Grzegorz Kwa\u015Bniewski, J\xFCrgen M\xFCller, \u0141\
  ukasz Flis, Hannes Eberhard, Hubert Niewiadomski, Torsten Hoefler"
conference: No Venue
year: 2025
bibkey: besta2025reasoning
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2501.11223'}]
tags: ["Reinforcement Learning", "Survey Paper", "Tools", "Training Techniques"]
short_authors: Besta et al.
---
Reasoning language models (RLMs), also known as Large Reasoning Models (LRMs), such as OpenAI's o1 and o3, DeepSeek-V3, and Alibaba's QwQ, have redefined AI's problem-solving capabilities by extending large language models (LLMs) with advanced reasoning mechanisms. Yet, their high costs, proprietary nature, and complex architectures - uniquely combining Reinforcement Learning (RL), search heuristics, and LLMs - present accessibility and scalability challenges. To address these, we propose a comprehensive blueprint that organizes RLM components into a modular framework, based on a survey and analysis of all RLM works. This blueprint incorporates diverse reasoning structures (chains, trees, graphs, and nested forms), reasoning strategies (e.g., Monte Carlo Tree Search, Beam Search), RL concepts (policy, value models and others), and supervision schemes (Output-Based and Process-Based Supervision). We also provide detailed mathematical formulations and algorithmic specifications to simplify RLM implementation. By showing how schemes like LLaMA-Berry, QwQ, Journey Learning, and Graph of Thoughts fit as special cases, we demonstrate the blueprint's versatility and unifying potential. To illustrate its utility, we introduce x1, a modular implementation for rapid RLM prototyping and experimentation. Using x1 and a literature review, we provide key insights, such as multi-phase training for policy and value models, and the importance of familiar training distributions. Finally, we outline how RLMs can integrate with a broader LLM ecosystem, including tools and databases. Our work demystifies RLM construction, democratizes advanced reasoning capabilities, and fosters innovation, aiming to mitigate the gap between "rich AI" and "poor AI" by lowering barriers to RLM development and experimentation.

https://huggingface.co/discussions/paper/6790772d8d7df822f1fb4493