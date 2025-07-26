---
layout: publication
title: 'SFT Memorizes, RL Generalizes: A Comparative Study Of Foundation Model Post-training'
authors: Tianzhe Chu, Yuexiang Zhai, Jihan Yang, Shengbang Tong, Saining Xie, Dale
  Schuurmans, Quoc V. Le, Sergey Levine, Yi Ma
conference: No Venue
year: 2025
bibkey: chu2025sft
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2501.17161'}]
tags: ["Fine-Tuning", "Reinforcement Learning", "Training Techniques"]
short_authors: Chu et al.
---
Supervised fine-tuning (SFT) and reinforcement learning (RL) are widely used post-training techniques for foundation models. However, their roles in enhancing model generalization capabilities remain unclear. This paper studies the difference between SFT and RL on generalization and memorization, focusing on text-based rule variants and visual variants. We introduce GeneralPoints, an arithmetic reasoning card game, and adopt V-IRL, a real-world navigation environment, to assess how models trained with SFT and RL generalize to unseen variants in both textual and visual domains. We show that RL, especially when trained with an outcome-based reward, generalizes across both rule-based textual and visual variants. SFT, in contrast, tends to memorize training data and struggles to generalize out-of-distribution scenarios. Further analysis reveals that RL improves the model's underlying visual recognition capabilities, contributing to its enhanced generalization in the visual domain. Despite RL's superior generalization, we show that SFT remains essential for effective RL training; SFT stabilizes the model's output format, enabling subsequent RL to achieve its performance gains. These findings demonstrates the capability of RL for acquiring generalizable knowledge in complex, multi-modal tasks.

https://huggingface.co/discussions/paper/6799b39d15f4661561c229e6