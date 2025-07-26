---
layout: publication
title: A Knowledge-enhanced Pretraining Model For Commonsense Story Generation
authors: Jian Guan, Fei Huang, Zhihao Zhao, Xiaoyan Zhu, Minlie Huang
conference: Transactions of the Association for Computational Linguistics
year: 2020
bibkey: guan2020knowledge
citations: 235
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2001.05139'}]
tags: ["Evaluation", "Fine-Tuning", "Model Architecture"]
short_authors: Guan et al.
---
Story generation, namely generating a reasonable story from a leading
context, is an important but challenging task. In spite of the success in
modeling fluency and local coherence, existing neural language generation
models (e.g., GPT-2) still suffer from repetition, logic conflicts, and lack of
long-range coherence in generated stories. We conjecture that this is because
of the difficulty of associating relevant commonsense knowledge, understanding
the causal relationships, and planning entities and events with proper temporal
order. In this paper, we devise a knowledge-enhanced pretraining model for
commonsense story generation. We propose to utilize commonsense knowledge from
external knowledge bases to generate reasonable stories. To further capture the
causal and temporal dependencies between the sentences in a reasonable story,
we employ multi-task learning which combines a discriminative objective to
distinguish true and fake stories during fine-tuning. Automatic and manual
evaluation shows that our model can generate more reasonable stories than
state-of-the-art baselines, particularly in terms of logic and global
coherence.