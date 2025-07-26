---
layout: publication
title: 'KGPT: Knowledge-grounded Pre-training For Data-to-text Generation'
authors: Wenhu Chen, Yu Su, Xifeng Yan, William Yang Wang
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: chen2020kgpt
citations: 102
additional_links: [{name: Code, url: 'https://github.com/wenhuchen/KGPT'}, {name: Paper,
    url: 'https://arxiv.org/abs/2010.02307'}]
tags: ["Applications"]
short_authors: Chen et al.
---
Data-to-text generation has recently attracted substantial interests due to
its wide applications. Existing methods have shown impressive performance on an
array of tasks. However, they rely on a significant amount of labeled data for
each task, which is costly to acquire and thus limits their application to new
tasks and domains. In this paper, we propose to leverage pre-training and
transfer learning to address this issue. We propose a knowledge-grounded
pre-training (KGPT), which consists of two parts, 1) a general
knowledge-grounded generation model to generate knowledge-enriched text. 2) a
pre-training paradigm on a massive knowledge-grounded text corpus crawled from
the web. The pre-trained model can be fine-tuned on various data-to-text
generation tasks to generate task-specific text. We adopt three settings,
namely fully-supervised, zero-shot, few-shot to evaluate its effectiveness.
Under the fully-supervised setting, our model can achieve remarkable gains over
the known baselines. Under zero-shot setting, our model without seeing any
examples achieves over 30 ROUGE-L on WebNLG while all other baselines fail.
Under the few-shot setting, our model only needs about one-fifteenth as many
labeled examples to achieve the same level of performance as baseline models.
These experiments consistently prove the strong generalization ability of our
proposed framework https://github.com/wenhuchen/KGPT.