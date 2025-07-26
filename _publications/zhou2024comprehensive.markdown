---
layout: publication
title: A Comprehensive Evaluation Of Large Language Models On Aspect-based Sentiment
  Analysis
authors: Changzhi Zhou, Dandan Song, Yuhang Tian, Zhijing Wu, Hao Wang, Xinyu Zhang,
  Jun Yang, Ziyi Yang, Shuhao Zhang
conference: International Journal of Machine Learning and Cybernetics
year: 2024
bibkey: zhou2024comprehensive
citations: 160
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.02279'}]
tags: ["Datasets", "Evaluation"]
short_authors: Zhou et al.
---
Recently, Large Language Models (LLMs) have garnered increasing attention in
the field of natural language processing, revolutionizing numerous downstream
tasks with powerful reasoning and generation abilities. For example, In-Context
Learning (ICL) introduces a fine-tuning-free paradigm, allowing out-of-the-box
LLMs to execute downstream tasks by analogy learning without any fine-tuning.
Besides, in a fine-tuning-dependent paradigm where substantial training data
exists, Parameter-Efficient Fine-Tuning (PEFT), as the cost-effective methods,
enable LLMs to achieve excellent performance comparable to full fine-tuning.
  However, these fascinating techniques employed by LLMs have not been fully
exploited in the ABSA field. Previous works probe LLMs in ABSA by merely using
randomly selected input-output pairs as demonstrations in ICL, resulting in an
incomplete and superficial evaluation. In this paper, we shed light on a
comprehensive evaluation of LLMs in the ABSA field, involving 13 datasets, 8
ABSA subtasks, and 6 LLMs. Specifically, we design a unified task formulation
to unify ``multiple LLMs for multiple ABSA subtasks in multiple paradigms.''
For the fine-tuning-dependent paradigm, we efficiently fine-tune LLMs using
instruction-based multi-task learning. For the fine-tuning-free paradigm, we
propose 3 demonstration selection strategies to stimulate the few-shot
abilities of LLMs. Our extensive experiments demonstrate that LLMs achieve a
new state-of-the-art performance compared to fine-tuned Small Language Models
(SLMs) in the fine-tuning-dependent paradigm. More importantly, in the
fine-tuning-free paradigm where SLMs are ineffective, LLMs with ICL still
showcase impressive potential and even compete with fine-tuned SLMs on some
ABSA subtasks.