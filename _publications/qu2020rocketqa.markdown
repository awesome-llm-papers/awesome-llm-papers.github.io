---
layout: publication
title: 'Rocketqa: An Optimized Training Approach To Dense Passage Retrieval For Open-domain
  Question Answering'
authors: Yingqi Qu, Yuchen Ding, Jing Liu, Kai Liu, Ruiyang Ren, Wayne Xin Zhao, Daxiang
  Dong, Hua Wu, Haifeng Wang
conference: 'Proceedings of the 2021 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2021
bibkey: qu2020rocketqa
citations: 296
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.08191'}]
tags: ["Model Architecture", "NAACL", "Retrieval Systems", "Training Techniques"]
short_authors: Qu et al.
---
In open-domain question answering, dense passage retrieval has become a new
paradigm to retrieve relevant passages for finding answers. Typically, the
dual-encoder architecture is adopted to learn dense representations of
questions and passages for semantic matching. However, it is difficult to
effectively train a dual-encoder due to the challenges including the
discrepancy between training and inference, the existence of unlabeled
positives and limited training data. To address these challenges, we propose an
optimized training approach, called RocketQA, to improving dense passage
retrieval. We make three major technical contributions in RocketQA, namely
cross-batch negatives, denoised hard negatives and data augmentation. The
experiment results show that RocketQA significantly outperforms previous
state-of-the-art models on both MSMARCO and Natural Questions. We also conduct
extensive experiments to examine the effectiveness of the three strategies in
RocketQA. Besides, we demonstrate that the performance of end-to-end QA can be
improved based on our RocketQA retriever.