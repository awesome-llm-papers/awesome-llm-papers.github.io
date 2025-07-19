---
layout: publication
title: Evidence Sentence Extraction For Machine Reading Comprehension
authors: Wang et al.
conference: Proceedings of the 23rd Conference on Computational Natural Language Learning
  (CoNLL)
year: 2019
bibkey: wang2019evidence
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1902.08852'}]
tags: [Reinforcement Learning, Tools, Datasets]
---
Remarkable success has been achieved in the last few years on some limited
machine reading comprehension (MRC) tasks. However, it is still difficult to
interpret the predictions of existing MRC models. In this paper, we focus on
extracting evidence sentences that can explain or support the answers of
multiple-choice MRC tasks, where the majority of answer options cannot be
directly extracted from reference documents.
  Due to the lack of ground truth evidence sentence labels in most cases, we
apply distant supervision to generate imperfect labels and then use them to
train an evidence sentence extractor. To denoise the noisy labels, we apply a
recently proposed deep probabilistic logic learning framework to incorporate
both sentence-level and cross-sentence linguistic indicators for indirect
supervision. We feed the extracted evidence sentences into existing MRC models
and evaluate the end-to-end performance on three challenging multiple-choice
MRC datasets: MultiRC, RACE, and DREAM, achieving comparable or better
performance than the same models that take as input the full reference
document. To the best of our knowledge, this is the first work extracting
evidence sentences for multiple-choice MRC.