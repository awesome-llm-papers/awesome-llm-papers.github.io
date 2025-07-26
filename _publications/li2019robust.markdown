---
layout: publication
title: Robust Navigation With Language Pretraining And Stochastic Sampling
authors: Xiujun Li, Chunyuan Li, Qiaolin Xia, Yonatan Bisk, Asli Celikyilmaz, Jianfeng
  Gao, Noah Smith, Yejin Choi
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: li2019robust
citations: 85
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.02244'}]
tags: ["EMNLP", "Training Techniques"]
short_authors: Li et al.
---
Core to the vision-and-language navigation (VLN) challenge is building robust
instruction representations and action decoding schemes, which can generalize
well to previously unseen instructions and environments. In this paper, we
report two simple but highly effective methods to address these challenges and
lead to a new state-of-the-art performance. First, we adapt large-scale
pretrained language models to learn text representations that generalize better
to previously unseen instructions. Second, we propose a stochastic sampling
scheme to reduce the considerable gap between the expert actions in training
and sampled actions in test, so that the agent can learn to correct its own
mistakes during long sequential action decoding. Combining the two techniques,
we achieve a new state of the art on the Room-to-Room benchmark with 6%
absolute gain over the previous best result (47% -> 53%) on the Success Rate
weighted by Path Length metric.