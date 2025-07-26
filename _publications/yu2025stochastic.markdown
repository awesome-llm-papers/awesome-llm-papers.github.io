---
layout: publication
title: 'The Stochastic Parrot On Llm''s Shoulder: A Summative Assessment Of Physical
  Concept Understanding'
authors: Mo Yu, Lemao Liu, Junjie Wu, Tsz Ting Chung, Shunchi Zhang, Jiangnan Li,
  Dit-yan Yeung, Jie Zhou
conference: No Venue
year: 2025
bibkey: yu2025stochastic
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2502.08946'}]
tags: ["Fine-Tuning", "In Context Learning", "Model Architecture"]
short_authors: Yu et al.
---
In a systematic way, we investigate a widely asked question: Do LLMs really understand what they say?, which relates to the more familiar term Stochastic Parrot. To this end, we propose a summative assessment over a carefully designed physical concept understanding task, PhysiCo. Our task alleviates the memorization issue via the usage of grid-format inputs that abstractly describe physical phenomena. The grids represents varying levels of understanding, from the core phenomenon, application examples to analogies to other abstract patterns in the grid world. A comprehensive study on our task demonstrates: (1) state-of-the-art LLMs, including GPT-4o, o1 and Gemini 2.0 flash thinking, lag behind humans by ~40%; (2) the stochastic parrot phenomenon is present in LLMs, as they fail on our grid task but can describe and recognize the same concepts well in natural language; (3) our task challenges the LLMs due to intrinsic difficulties rather than the unfamiliar grid format, as in-context learning and fine-tuning on same formatted data added little to their performance.

https://huggingface.co/discussions/paper/67aeb181cb3be2cefd46ed4c