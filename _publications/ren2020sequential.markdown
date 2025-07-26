---
layout: publication
title: Sequential Recommendation With Self-attentive Multi-adversarial Network
authors: Ruiyang Ren, Zhaoyang Liu, Yaliang Li, Wayne Xin Zhao, Hui Wang, Bolin Ding,
  Ji-rong Wen
conference: Proceedings of the 43rd International ACM SIGIR Conference on Research
  and Development in Information Retrieval
year: 2020
bibkey: ren2020sequential
citations: 89
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.10602'}]
tags: ["Model Architecture", "SIGIR"]
short_authors: Ren et al.
---
Recently, deep learning has made significant progress in the task of
sequential recommendation. Existing neural sequential recommenders typically
adopt a generative way trained with Maximum Likelihood Estimation (MLE). When
context information (called factor) is involved, it is difficult to analyze
when and how each individual factor would affect the final recommendation
performance. For this purpose, we take a new perspective and introduce
adversarial learning to sequential recommendation. In this paper, we present a
Multi-Factor Generative Adversarial Network (MFGAN) for explicitly modeling the
effect of context information on sequential recommendation. Specifically, our
proposed MFGAN has two kinds of modules: a Transformer-based generator taking
user behavior sequences as input to recommend the possible next items, and
multiple factor-specific discriminators to evaluate the generated sub-sequence
from the perspectives of different factors. To learn the parameters, we adopt
the classic policy gradient method, and utilize the reward signal of
discriminators for guiding the learning of the generator. Our framework is
flexible to incorporate multiple kinds of factor information, and is able to
trace how each factor contributes to the recommendation decision over time.
Extensive experiments conducted on three real-world datasets demonstrate the
superiority of our proposed model over the state-of-the-art methods, in terms
of effectiveness and interpretability.