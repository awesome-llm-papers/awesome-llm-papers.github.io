---
layout: publication
title: 'FLM-101B: An Open LLM And How To Train It With $100K Budget'
authors: Xiang Li, Yiqun Yao, Xin Jiang, Xuezhi Fang, Xuying Meng, Siqi Fan, Peng
  Han, Jing Li, Li Du, Bowen Qin, Zheng Zhang, Aixin Sun, Yequan Wang
conference: No Venue
year: 2023
bibkey: li2023flm
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2309.03852'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Li et al.
---
Large language models (LLMs) have achieved remarkable success in NLP and multimodal tasks. Despite these successes, their development faces two main challenges: (i) high computational cost; and (ii) difficulty in conducting fair and objective evaluations. LLMs are prohibitively expensive, making it feasible for only a few major players to undertake their training, thereby constraining both research and application opportunities. This underscores the importance of cost-effective LLM training. In this paper, we utilize a growth strategy to significantly reduce LLM training cost. We demonstrate that an LLM with 101B parameters and 0.31TB tokens can be trained on a 100K budget. We also adopt a systematic evaluation paradigm for the IQ evaluation of LLMs, in complement to existing evaluations that focus more on knowledge-oriented abilities. We introduce our benchmark including evaluations on important aspects of intelligence including symbolic mapping, itrule understanding, pattern mining, and anti-interference. Such evaluations minimize the potential impact of memorization. Experimental results show that our model FLM-101B, trained with a budget of 100K, achieves comparable performance to powerful and well-known models, eg GPT-3 and GLM-130B, especially in the IQ benchmark evaluations with contexts unseen in training data. The checkpoint of FLM-101B will be open-sourced at https://huggingface.co/CofeAI/FLM-101B.

https://huggingface.co/discussions/paper/64fa7f4ab961d0d12c6d45b2