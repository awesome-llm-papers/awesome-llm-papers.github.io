---
layout: publication
title: On Learning Universal Representations Across Languages
authors: Xiangpeng Wei, Rongxiang Weng, Yue Hu, Luxi Xing, Heng Yu, Weihua Luo
conference: Arxiv
year: 2021
bibkey: wei2020learning
citations: 62
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2007.15960'}]
tags: ["Datasets", "Evaluation", "Model Architecture"]
short_authors: Wei et al.
---
Recent studies have demonstrated the overwhelming advantage of cross-lingual
pre-trained models (PTMs), such as multilingual BERT and XLM, on cross-lingual
NLP tasks. However, existing approaches essentially capture the co-occurrence
among tokens through involving the masked language model (MLM) objective with
token-level cross entropy. In this work, we extend these approaches to learn
sentence-level representations and show the effectiveness on cross-lingual
understanding and generation. Specifically, we propose a Hierarchical
Contrastive Learning (HiCTL) method to (1) learn universal representations for
parallel sentences distributed in one or multiple languages and (2) distinguish
the semantically-related words from a shared cross-lingual vocabulary for each
sentence. We conduct evaluations on two challenging cross-lingual tasks, XTREME
and machine translation. Experimental results show that the HiCTL outperforms
the state-of-the-art XLM-R by an absolute gain of 4.2% accuracy on the XTREME
benchmark as well as achieves substantial improvements on both of the
high-resource and low-resource English-to-X translation tasks over strong
baselines.