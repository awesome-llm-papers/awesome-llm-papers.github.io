---
layout: publication
title: Conditional Teacher-student Learning
authors: Zhong Meng, Jinyu Li, Yong Zhao, Yifan Gong
conference: ICASSP 2019 - 2019 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)
year: 2019
bibkey: meng2019conditional
citations: 89
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.12399'}]
tags: ["ICASSP"]
short_authors: Meng et al.
---
The teacher-student (T/S) learning has been shown to be effective for a
variety of problems such as domain adaptation and model compression. One
shortcoming of the T/S learning is that a teacher model, not always perfect,
sporadically produces wrong guidance in form of posterior probabilities that
misleads the student model towards a suboptimal performance. To overcome this
problem, we propose a conditional T/S learning scheme, in which a "smart"
student model selectively chooses to learn from either the teacher model or the
ground truth labels conditioned on whether the teacher can correctly predict
the ground truth. Unlike a naive linear combination of the two knowledge
sources, the conditional learning is exclusively engaged with the teacher model
when the teacher model's prediction is correct, and otherwise backs off to the
ground truth. Thus, the student model is able to learn effectively from the
teacher and even potentially surpass the teacher. We examine the proposed
learning scheme on two tasks: domain adaptation on CHiME-3 dataset and speaker
adaptation on Microsoft short message dictation dataset. The proposed method
achieves 9.8% and 12.8% relative word error rate reductions, respectively, over
T/S learning for environment adaptation and speaker-independent model for
speaker adaptation.