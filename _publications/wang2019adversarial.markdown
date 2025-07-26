---
layout: publication
title: Adversarial Domain Adaptation For Machine Reading Comprehension
authors: Huazheng Wang, Zhe Gan, Xiaodong Liu, Jingjing Liu, Jianfeng Gao, Hongning
  Wang
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: wang2019adversarial
citations: 60
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.09209'}]
tags: ["Datasets", "Fine-Tuning", "Model Architecture", "Training Techniques"]
short_authors: Wang et al.
---
In this paper, we focus on unsupervised domain adaptation for Machine Reading
Comprehension (MRC), where the source domain has a large amount of labeled
data, while only unlabeled passages are available in the target domain. To this
end, we propose an Adversarial Domain Adaptation framework (AdaMRC), where
(\\(i\\)) pseudo questions are first generated for unlabeled passages in the target
domain, and then (\\(ii\\)) a domain classifier is incorporated into an MRC model
to predict which domain a given passage-question pair comes from. The
classifier and the passage-question encoder are jointly trained using
adversarial learning to enforce domain-invariant representation learning.
Comprehensive evaluations demonstrate that our approach (\\(i\\)) is generalizable
to different MRC models and datasets, (\\(ii\\)) can be combined with pre-trained
large-scale language models (such as ELMo and BERT), and (\\(iii\\)) can be
extended to semi-supervised learning.