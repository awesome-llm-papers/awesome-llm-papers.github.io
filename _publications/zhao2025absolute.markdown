---
layout: publication
title: 'Absolute Zero: Reinforced Self-play Reasoning With Zero Data'
authors: Andrew Zhao, Yiran Wu, Yang Yue, Tong Wu, Quentin Xu, Yang Yue, Matthieu
  Lin, Shenzhi Wang, Qingyun Wu, Zilong Zheng, Gao Huang
conference: No Venue
year: 2025
bibkey: zhao2025absolute
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/681ab9baf43603c60cab881a'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2505.03335'}]
tags: ["Reinforcement Learning", "Training Techniques"]
short_authors: Zhao et al.
---
Reinforcement learning with verifiable rewards (RLVR) has shown promise in enhancing the reasoning capabilities of large language models by learning directly from outcome-based rewards. Recent RLVR works that operate under the zero setting avoid supervision in labeling the reasoning process, but still depend on manually curated collections of questions and answers for training. The scarcity of high-quality, human-produced examples raises concerns about the long-term scalability of relying on human supervision, a challenge already evident in the domain of language model pretraining. Furthermore, in a hypothetical future where AI surpasses human intelligence, tasks provided by humans may offer limited learning potential for a superintelligent system. To address these concerns, we propose a new RLVR paradigm called Absolute Zero, in which a single model learns to propose tasks that maximize its own learning progress and improves reasoning by solving them, without relying on any external data. Under this paradigm, we introduce the Absolute Zero Reasoner (AZR), a system that self-evolves its training curriculum and reasoning ability by using a code executor to both validate proposed code reasoning tasks and verify answers, serving as an unified source of verifiable reward to guide open-ended yet grounded learning. Despite being trained entirely without external data, AZR achieves overall SOTA performance on coding and mathematical reasoning tasks, outperforming existing zero-setting models that rely on tens of thousands of in-domain human-curated examples. Furthermore, we demonstrate that AZR can be effectively applied across different model scales and is compatible with various model classes.

https://huggingface.co/discussions/paper/681ab9baf43603c60cab881a