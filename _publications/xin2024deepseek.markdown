---
layout: publication
title: 'Deepseek-prover-v1.5: Harnessing Proof Assistant Feedback For Reinforcement
  Learning And Monte-carlo Tree Search'
authors: Huajian Xin, Z. Z. Ren, Junxiao Song, Zhihong Shao, Wanjia Zhao, Haocheng
  Wang, Bo Liu, Liyue Zhang, Xuan Lu, Qiushi Du, Wenjun Gao, Qihao Zhu, Dejian Yang,
  Zhibin Gou, Z. F. Wu, Fuli Luo, Chong Ruan
conference: No Venue
year: 2024
bibkey: xin2024deepseek
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2408.08152'}]
tags: ["Evaluation", "Fine-Tuning", "Reinforcement Learning", "Training Techniques"]
short_authors: Xin et al.
---
We introduce DeepSeek-Prover-V1.5, an open-source language model designed for theorem proving in Lean 4, which enhances DeepSeek-Prover-V1 by optimizing both training and inference processes. Pre-trained on DeepSeekMath-Base with specialization in formal mathematical languages, the model undergoes supervised fine-tuning using an enhanced formal theorem proving dataset derived from DeepSeek-Prover-V1. Further refinement is achieved through reinforcement learning from proof assistant feedback (RLPAF). Beyond the single-pass whole-proof generation approach of DeepSeek-Prover-V1, we propose RMaxTS, a variant of Monte-Carlo tree search that employs an intrinsic-reward-driven exploration strategy to generate diverse proof paths. DeepSeek-Prover-V1.5 demonstrates significant improvements over DeepSeek-Prover-V1, achieving new state-of-the-art results on the test set of the high school level miniF2F benchmark (63.5%) and the undergraduate level ProofNet benchmark (25.3%).

https://huggingface.co/discussions/paper/66bebba1c55655c7150bb3ac