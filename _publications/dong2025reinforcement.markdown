---
layout: publication
title: Reinforcement Pre-training
authors: Qingxiu Dong, Li Dong, Yao Tang, Tianzhu Ye, Yutao Sun, Zhifang Sui, Furu
  Wei
conference: No Venue
year: 2025
bibkey: dong2025reinforcement
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.08007'}]
tags: ["Reinforcement Learning", "Training Techniques"]
short_authors: Dong et al.
---
In this work, we introduce Reinforcement Pre-Training (RPT) as a new scaling paradigm for large language models and reinforcement learning (RL). Specifically, we reframe next-token prediction as a reasoning task trained using RL, where it receives verifiable rewards for correctly predicting the next token for a given context. RPT offers a scalable method to leverage vast amounts of text data for general-purpose RL, rather than relying on domain-specific annotated answers. By incentivizing the capability of next-token reasoning, RPT significantly improves the language modeling accuracy of predicting the next tokens. Moreover, RPT provides a strong pre-trained foundation for further reinforcement fine-tuning. The scaling curves show that increased training compute consistently improves the next-token prediction accuracy. The results position RPT as an effective and promising scaling paradigm to advance language model pre-training.

https://huggingface.co/discussions/paper/684794553ec10bdd8ab4de21