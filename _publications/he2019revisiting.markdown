---
layout: publication
title: Revisiting Self-training For Neural Sequence Generation
authors: Junxian He, Jiatao Gu, Jiajun Shen, Marc'aurelio Ranzato
conference: Arxiv
year: 2019
bibkey: he2019revisiting
citations: 152
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.13788'}]
tags: ["Training Techniques"]
short_authors: He et al.
---
Self-training is one of the earliest and simplest semi-supervised methods.
The key idea is to augment the original labeled dataset with unlabeled data
paired with the model's prediction (i.e. the pseudo-parallel data). While
self-training has been extensively studied on classification problems, in
complex sequence generation tasks (e.g. machine translation) it is still
unclear how self-training works due to the compositionality of the target
space. In this work, we first empirically show that self-training is able to
decently improve the supervised baseline on neural sequence generation tasks.
Through careful examination of the performance gains, we find that the
perturbation on the hidden states (i.e. dropout) is critical for self-training
to benefit from the pseudo-parallel data, which acts as a regularizer and
forces the model to yield close predictions for similar unlabeled inputs. Such
effect helps the model correct some incorrect predictions on unlabeled data. To
further encourage this mechanism, we propose to inject noise to the input
space, resulting in a "noisy" version of self-training. Empirical study on
standard machine translation and text summarization benchmarks shows that noisy
self-training is able to effectively utilize unlabeled data and improve the
performance of the supervised baseline by a large margin.