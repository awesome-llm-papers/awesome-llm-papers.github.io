---
layout: publication
title: Dataset And Neural Recurrent Sequence Labeling Model For Open-domain Factoid
  Question Answering
authors: Peng Li, Wei Li, Zhengyan He, Xuguang Wang, Ying Cao, Jie Zhou, Wei Xu
conference: Arxiv
year: 2016
bibkey: li2016dataset
citations: 78
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1607.06275'}]
tags: ["Datasets"]
short_authors: Li et al.
---
While question answering (QA) with neural network, i.e. neural QA, has
achieved promising results in recent years, lacking of large scale real-word QA
dataset is still a challenge for developing and evaluating neural QA system. To
alleviate this problem, we propose a large scale human annotated real-world QA
dataset WebQA with more than 42k questions and 556k evidences. As existing
neural QA methods resolve QA either as sequence generation or
classification/ranking problem, they face challenges of expensive softmax
computation, unseen answers handling or separate candidate answer generation
component. In this work, we cast neural QA as a sequence labeling problem and
propose an end-to-end sequence labeling model, which overcomes all the above
challenges. Experimental results on WebQA show that our model outperforms the
baselines significantly with an F1 score of 74.69% with word-based input, and
the performance drops only 3.72 F1 points with more challenging character-based
input.