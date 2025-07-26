---
layout: publication
title: 'A Good Prompt Is Worth Millions Of Parameters: Low-resource Prompt-based Learning
  For Vision-language Models'
authors: Woojeong Jin, Yu Cheng, Yelong Shen, Weizhu Chen, Xiang Ren
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
bibkey: jin2021good
citations: 68
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.08484'}]
tags: ["Applications", "Few-Shot", "Fine-Tuning", "Prompting", "Training Techniques"]
short_authors: Jin et al.
---
Large pre-trained vision-language (VL) models can learn a new task with a
handful of examples and generalize to a new task without fine-tuning. However,
these VL models are hard to deploy for real-world applications due to their
impractically huge sizes and slow inference speed. To solve this limitation, we
study prompt-based low-resource learning of VL tasks with our proposed method,
FewVLM, relatively smaller than recent few-shot learners. For FewVLM, we
pre-train a sequence-to-sequence transformer model with prefix language
modeling (PrefixLM) and masked language modeling (MaskedLM). Furthermore, we
analyze the effect of diverse prompts for few-shot tasks. Experimental results
on VQA show that FewVLM with prompt-based learning outperforms Frozen which is
31x larger than FewVLM by 18.2% point and achieves comparable results to a 246x
larger model, PICa. In our analysis, we observe that (1) prompts significantly
affect zero-shot performance but marginally affect few-shot performance, (2)
models with noisy prompts learn as quickly as hand-crafted prompts given larger
training data, and (3) MaskedLM helps VQA tasks while PrefixLM boosts
captioning performance. Our code is publicly available at
https://github.com/woojeongjin/FewVLM